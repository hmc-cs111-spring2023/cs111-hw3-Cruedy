# Interview project

## The user and a language

This section describes who the project would serve and why a language might be a
good way to meet their needs.

_I interviewed a swimmer who struggles with keeping track of times to leave for swimming sets when she has a complicated interval. A language that would be able to track integers with different bases. Like for tracking times for swimmers, the language can use base-60._

### What's the need?
### What need is met by your idea? Who are you helping? What is that person's experience like now? What would their experience be like if you could help them?

_This language would help anyone who needs to keep track of a bunch of times, and needs to get those times quickly before they start tracking the next time. I would be helping athletes whose sports are time based. Currently the person I interviewed struggles with getting those times correct, so she misses her intervals for swimming. They would know when to leave for the next interval without having to calculate the time to leave herself._

### Why a language?
### Why is a DSL appropriate for your user(s)? How does it address the need?
_A DSL is appropriate because this language wouldn't be doing anything besides tracking times or numbers that are different bases. This addresses the original need because it can be set to be on base-60._

### Why you?
### What excites you about this idea? How did you come up with it?
_I based this language off of assembly code, which is base 2. I'm excited about this idea because it seems easy to implement, and I also struggle with keeping track of swimming intervals._

### Domain
### Describe the project's domain in five words.
_Counting, Tracking, Changing Base, Timing_

### Interface (syntax)
### How might the user interact with the language? What does programming look like? Why is this the right way to interact with the problem domain?
_The user would set the base to whatever is useful for them(i this specific case base 60), and create a function based on a start time and the number of times that needs to be tracked. Programmin this language would be very simple cause there are only a few things that need to be changed. This seems like the easy language to implement to solve the problem._

### Operation (semantics)
### What might happen when a program runs? How does a program interact with the user? What kinds of errors might occur, and how might they be communicated to the user?
_The program waits for an external source to reach the start number given, then it tracks times based on the interval. There could be type errors based on what the input needs to be for the program. The program will just describe the error type and say where the error's source is._

### Expressiveness
### What should be easy to do in this language? What should be possible, but difficult? What should be impossible or very difficult?
_I should be easy to loop in this language based on a value(like a for loop). If maybe be difficult to create non numerical booleans. It would probably be impossible to work with strings in this lanugage._

### Related work
### Are there any other DSLs in this domain? If not, describe how you know there aren't and conjecture why not. If so, describe them and provide links. How well do they address the need? Are there any particularly admirable qualities of the language? Are there parts of the language you think could be improved?
_The most similar language I can think of is machine code, which is in base 2, but I dont think machine code is a DSL. I don't think there are any other languages that work with numbers of different bases._

## The Project
## This section examines whether the idea makes for a good CS 111 project.
_This doesn't seem like a difficult language to implement, but I think it woudl be a little to specific, so I'm not sure it's the best language for this project._

### Suitability
### If someone were to work on this project, what percentage of their time would be spent directly engaging in the **language** aspects of this project (e.g.,making language design decisions), as opposed to "systems" aspects of the project (e.g., implementing a complicated semantics that doesn't require a lot of language design)?
_I think that most of the time would be spent on the system aspects of this language because creatign the language doesn't seem that complicated itself._

### Scope
### How big an idea is this? How ambitious is this project?
_This language isn't that ambitious because I think I could just code the language in python using simple functions._

### Benefits and drawbacks
### Why might this be a good idea for a project? Why might this not be a good idea project?
_I think this project would be easy to implement, but I don't think it would be that useful for many people._
