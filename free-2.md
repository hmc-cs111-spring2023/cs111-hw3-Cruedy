# Free project 2

## The user and a language
### This section describes who the project would serve and why a language might be a good way to meet their needs.

### What's the need?
### What need is met by your idea? Who are you helping? What is that person's experience like now? What would their experience be like if you could help them?
_This DSL would help programmers debug their code. Right now they write unit tests to help debug code. Instead they could use this DSL to help make simple tests for the code they wrote._

### Why a language?
### Why is a DSL appropriate for your user(s)? How does it address the need?
_A DSL is appropriate because there is code written in various different language that need testing. We could use a simple language to make tests for code in various languages._

### Why you?
### What excites you about this idea? How did you come up with it?
_I think that it would be pretty useful if I'm able to create this DSL. I thought of this because the first person I interviewed said they wanted a language that could help them with debugging._

### Domain
### Describe the project's domain in five words.
_Debug, Testing, Cross-language, and Error Checking_

### Interface (syntax)
### How might the user interact with the language? What does programming look like? Why is this the right way to interact with the problem domain?
_The user would write code in the language in the same editor that they used to write the program that they are testing. They would call the function that they write on the various types of tests they want to call._

### Operation (semantics)
### What might happen when a program runs? How does a program interact with the user? What kinds of errors might occur, and how might they be communicated to the user?
_When a program runs, it's tell the user if the code has the correct output. There could be syntac errors, in this case, the testign just wouldn't run properly._

### Expressiveness
### What should be easy to do in this language? What should be possible, but difficult? What should be impossible or very difficult?
_Looping should be easy, so that the user can go through multiple tests at once. I'm not sure if conditions should be easy or difficult. Cause there should be conditions whether the program is correct based on the tests, but I don't know if that should just be built. If should be impossible to change the input(the program)._

### Related work
### Are there any other DSLs in this domain? If not, describe how you know there aren't and conjecture why not. If so, describe them and provide links. How well do they address the need? Are there any particularly admirable qualities of the language? Are there parts of the language you think could be improved?
_I think there is another DSL called Xcode in Eclipse, but it's just meant for Java. 
[Xtext](https://www.eclipse.org/Xtext/)
I think the language should be used for multiple languages._

## The Project
### This section examines whether the idea makes for a good CS 111 project.

### Suitability
### If someone were to work on this project, what percentage of their time would be spent directly engaging in the **language** aspects of this project (e.g., making language design decisions), as opposed to "systems" aspects of the project (e.g., implementing a complicated semantics that doesn't require a lot of language design)?
_I think the time would be split up 50/50 because you have to have it work with multiple systems, but you would have to make the language work across those multiple systems._

### Scope
### How big an idea is this? How ambitious is this project?
_This idea seems pretty ambitious because it's complicated to get a DSL work with functions from different languages._

### Benefits and drawbacks
### Why might this be a good idea for a project? Why might this not be a good idea project?
_I think it's a good idea because it would be useful and if there's a way to make something work with functions from different languages, it wouldn't be too hard to implement. I think it may not be a good idea because it would probably be hard to make it work to debug functions in different languages._
