#Object-Oriented Design Reviews

From [_Stack Overflow_](http://stackoverflow.com/questions/1100819/how-do-you-design-object-oriented-projects):

>The steps that I use for initial design (getting to a class diagram), are:
- Requirements gathering. Talk to the client and factor out the use cases to define what functionality the software should have.
- Compose a narrative of the individual use cases.
- Go through the narrative and highlight nouns (person, place, thing), as candidate classes and verbs (actions), as methods / behaviors.
- Discard duplicate nouns and factor out common functionality.
- Create a class diagram. Examples are NetBeans (Sun), Eclipse, and ArgoUML. Whiteboards work, too.
- Apply OOD principles to organize your classes (factor out common functionality, build hierarchies, etc.)

##General Questions
Going object-by-object:

- Does this object make sense? Can I explain it in English without any weirdness going on?
- Is there another way I could configure this object so it would make *even more* sense as an English description?
- Am I asking this object to do too much? Could I refactor the object so it doesn't have to do all these things?
- Would it makes sense to create a whole new Class to do this, or does this seem like the sort of thing this object would do?

##OOD Heuristics
We will discuss these in a *lot* more detail later on - for now, the 'SOLID' principles can be used as an extension to code review material.

See [here](http://www.codeproject.com/Articles/567768/Object-Oriented-Design-Principles) for an article on this.