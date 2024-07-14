## Abstract
## Introduction

Software development and construction share many parallels and have historically been treated mostly the same. This historically extends to the project lifecycles. In the early days of software developers had to write large amounts of their code on paper because computer time was scarce and machines where still slow. Just like construction the job of the architect and the construction worker (programmer) were separated because both jobs called for a different skillset. The project got constructed on paper iterated on by multiple experts in different phases and ultimately constructed with the difference being that one field worked with steel and concrete and the other with text inputs.

In construction one of the most popular design approaches is the waterfall concept where the project flows down the different steps and then ends in a maintenance loop. Until recently software had to be treated similar because once shipped updates where bound to significant effort. With the internet the need for fully thought out products in software mostly vanished reducing the time from the drawing board to the customer significantly. While software and construction still share similarities the field of software engineering has evolved in a different direction. With CICD it's becoming increasingly popular to develop the product with the customer, continuously iterating and refining it.

Companies picked up on this and largely switched to agile developments techniques that are specifically designed to accommodate the new dynamic style of development. It is now significantly cheaper to bring a product to the customer and is even more normal to find beta state applications that are intentionally rapidly developing and instable. Because of software frameworks and libraries most base functionality is ready for production reducing the need for writing new software to the unique aspects of the projects.

Somewhere in this transition the traditional visualization tools lost most of their relevance. It's a significant overhead to update a UML diagram every time a library gets updated. And automatic tools never really gained traction in industry applications. While most traditional developers have to learn about UML diagrams and flowcharts during their education a significant chunk self thought developers don't. With modern tools it's not important enough to take the time to visualize the codebase until there is a good enough reason for it.

This report researches modern alternatives to the traditional visualization tools for software architecture discussing their advantages and drawbacks in comparison to traditional approaches and if there even is the need to use them anymore.

## Traditional Visualizations

Traditional visualization tools for software architecture are manually created. They specifically serve as a previous step to actually writing code and help picking up on unwanted dependencies, architectural code smells and other architectural issues. For example it's easy to see if demeters law was followed because in an UML Class diagrams its easy to spot violating connections between classes. Especially in the early days it was significantly faster to work out the rough code structure before writing the first line of code. The owner of the product specified what the code should do and developers constructed the architecture around that. Lastly programmers typed the code and fixed any errors emerging. If the code worked as intended and was tested enough it was ready to ship on a physical medium. If afterwards issues emerged it was logistically hard to bring a patch to the customer. 
### UML Diagrams

UML (Class) diagrams are a great tool to design the architecture of a application. While unnecessary on smaller projects its a great way to iterate on it before existing code prevents changes. In UML Diagrams the future code gets structured in classes planning out architectural patterns, needed methods, coupling and communication between classes and instances. Afterwards most of the code writing is simple enough to get handled asynchronously because the interface and shape is already defined. They are a great tool for teachers to test the understanding of students about architectural patterns without having to 
### Flow Charts
### Gnatt Diagrams
## Modern Visualizations
### Code City
### gource.io
## Conclusion