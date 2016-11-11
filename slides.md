# Take-Home Coding Challenges

## Intro

###Who are you?

- Name
- Front end / back end / full stack?
- Language or tool specialization?
- What’s something you’re working on / learning in your free time?

### Workshop Objectives

- Communicate with potential employers using appropriate technical terms.  
- Demonstrate knowledge of software construction patterns and best practices.
- Consider design and implementation alternatives, and make decisions based on relevant characteristics of the problem and available tools.
- Demonstrate awareness of real-world technical development practices and concerns related to the target company, including testing and security.  

##Technical Interview Process

### HR Phone Screen (20 - 30 min)

- Are you the person on your resume?
- Are your expectations reasonable?
- Example: Explain `this` in JavaScript or `self` in Ruby.

### Technical Phone Screen (20 - 60 min)

- Do you have the skills you claim on your resume?
- Can you speak with our engineers?
- Example: Write some code to find out if a number is prime.

### In-Depth Technical Interview(s): take-home coding challenge or onsite (2+ hours)

- How much training or ramp-up time would you need to get started?
- What would it be like to work on code you wrote?
- How well will you work with the existing codebase?

**Examples:**

- Parse the given log file to find the total number of errors with status codes in the 500s.
- Design and code a system for tracking users’ budgets.
- Implement a front end based on a mockup image.


## Tips for the Take-Home Coding Challenge

**Consider this a project someone else will pick up and work on.**

- What has made it easier for you to pick up and work with others’ code in the past? (What makes a good library?)

- What practices make it easier to work in groups with others?

### Best Practices: Workflow and Documentation

####Document, document, document

- Prove your work can speak for itself; you may not get a chance to explain later!
- Consider Readme *required*
- In-code documentation (comments, variable names)
- Bonus: documentation tools like rdoc or jsdoc (overkill on short time limit projects)

####Source control / version control

- Source control is *required* (and submit your .git and .gitignore)
- Commit every decent chunk of work with descriptive commit messages

####Testing

- Testing is a *huge bonus*, often required (rspec, chai, selenium)
- Even if you don’t have time to write tests, mention testing in readme

### Best Practices: Drilling Down on Documentation

**Readme: everything necessary to run and extend this code**
- Project name and description/goal
- Dependencies (language, libraries - think fresh computer but technical user)
- Instructions to download and run code (given dependencies listed earlier)
- Specifically for take-home coding challenge:
  - document decision making / problem solving
  - what would you do with more time

**Comments**
- Comments resolve ambiguities and clarify your code
- Generally comment for each function, anything required to work with a library
- Remove old code blocks

### Best Practices: Code

####Code organization
- Stay DRY; encapsulate using functions (descriptive names, ~16 lines)
- Use OOP if grouping related behaviors and information
- For large/complex projects, explain what each directory or file is for

####Code style
- Avoid too many anonymous functions, callback hell (go for easy to read)
- Follow language conventions

####Error handling and exceptions
- Program should work in normal use cases (as laid out in prompt)
- Fail gracefully in other cases (error message, not freezing computer)
- Guess what errors may happen and address in code or documentation

### Keep the Company and Role in Mind

#### What does the company do and need?
- Do they work with sensitive data? (security/privacy)
- Do they handle tons of real-time updates? (speed/scalability)
- Do they handle data that affects lives or livelihoods? (reliability)

####What technologies does the company use?
- If you’re comfortable using their tools in the time limit, show that off!
- If not, explain the benefits of the tools you’ve chosen to work with.

####What is the specific role you’re applying for?
- Full stack? Don’t forget to pay attention to front end and styling.
- *Never* forget user experience or testing.

## Coding Challenge Attack Plan

### Sample Coding Challenge


> Design and implement a site to help a person track his or her budget. Start out by assuming there will only be one user for the app.

> The user should be able to see their balance and enter in transactions that reduce or increase the amount of money available.

> Submit a compressed project directory by email to coding.challenge@company.org.  You have three days to work on this challenge.


**What stands out about this coding challenge description?**

- Will this be a website or a mobile app?
- When is this due? Do I count weekends? Do I need to have it in by 5:00pm or would 11:59pm be okay?
- Where is the income/spending data coming from? Some API?
- What kind of compressed file: .zip, .rar, .7z?


### Steps for Approaching a Coding Challenge

####When you get the coding challenge...

- **Clarify:**
  - how much time you have to complete the challenge
  - how to submit
  - whether to publish on GitHub
  - how to handle ambiguities: check in, or make a decision and document it?
- Immediately start a readme.
- If there is a built-in timer (should be obvious before you start), set aside a block of uninterrupted time to work on the challenge.
- Read **all** of the challenge instructions carefully. List ambiguities in your readme.
- Make sure you can access any files, links, or other resources they’re asking you to use.
- Note any terms you don’t know. Look these up!
- If you are unsure what you're being asked to do, talk to a colleague. If you’re still unsure, ask the recruiter.

 > You can also ask "If I find ambiguities, should I ask you about those or resolve them and document my decision?"

####Planning

- In your readme, write a sentence that says what your submission will do.
- Choose which technologies you’ll use to complete the challenge.  Write a brief explanation of your choice in your readme.
- Favor technologies actually used by the company, but make sure you can comfortably complete the task in the time given. This is probably not the time to learn a new language or unfamiliar framework.  
- If you would make different choices in a real scenario, write that too!

####Coding
- Pay attention to your code style, commenting, variable names. Try to match any given example code or style specifications.
- Prioritize basic functionality, but think through where errors might occur. Note these in your readme and/or comments.
- Make git commits with descriptive commit messages after every major portion of the task.  
- Check that your solution works by running through all of the features required by the prompt.

####After coding
- Package your submission in the format the company wants and write instructions for how the evaluators should run it.
- Try to open and run your submission according to the instructions in your readme.


####If you have extra time...
- Add more documentation (especially if you ran into problems/realized mistakes):
  - What problems did you run into?
  - What were your solutions, or what did you try? What about your approach was awesome?
  - What if anything would you do differently now that you’ve worked on the challenge?
  - What is your code sample missing because of time constraints?
- Write tests (unless TDD was required).
- Refactor.
- Work on bonuses.


## Sample Take Home Challenge Scoring System

100 + 10 points available

Award:
- 50 points for code that works and meets prompt requirements
- 20 points for code style (indentation, naming, following language conventions, comments)
- 20 points for code organization (separation of concerns, reusability, DRY)
- 10 points for readme
- 10 bonus points for tests

## Heirarchy of Importance

Weights vary from company to company, but here's how those priorities shake out:

A. Meeting the technical requirements.
B. Well-organized code (with a framework, OOP, or at least functions).
C. Clean, easy to read code.
E. Documentation (more important for larger projects).
F. Tests (important if required, nice to have if not). 

In evaluting your coding challenge today, we'll also look at:  
1. Problem Solving - while not specifically listed, it's one of the main things companies are trying to evaluate. Problem Solving is strongly tied to meeting technical requirements, to documentation, and to code organization.
1. Workflow - version control can help organize any project and is especially important if coding will take more than one sitting. 
2. Company knowledge - this is a "nice to have" that WDI alumns are often well equipped to show off because of informational interviews. 
