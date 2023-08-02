# Design Strategies


### Structured Desing:

Structured design is a software design methodology that aims to break down a complex system into smaller, manageable modules. It focuses on hierarchical organization and uses techniques such as top-down design and stepwise refinement to design the system in a structured and systematic manner. The key principles of structured design include modularity, cohesion, and data independence.Overall, structured design breaks down a complex system into modules, using hierarchical and stepwise refinement techniques for a well-organised and efficient design. 

### Function oriented design: 

Function-oriented design is a programming approach that structures software based on functions or procedures. It focuses on decomposing the problem into smaller functions, each performing a specific task. In this design, the emphasis is on functional decomposition and less on data organisation. It is commonly associated with procedural programming languages.In summary, function-oriented design organises software around functions, emphasising procedural decomposition of tasks. 

### Object oriented design:

Object-oriented design is a programming approach that organizes software around "objects" representing real-world entities or concepts. It emphasizes encapsulation, abstraction, inheritance, and polymorphism to create modular, flexible, and maintainable systems. 

**What do we mean by coupling and cohesion when discussing structured design?**


Coupling and cohesion are two important concepts in structured design that describe the relationships between modules within a software system:
    
Cohesion measures the strength of the relationship among elements within a module, while coupling gauges the level of interaction and dependency between different modules in a software system. In the context of structured design, it is desirable to achieve high cohesion within modules and minimize coupling between them to enhance code maintainability and flexibility. 

**What is the difference between top-down and bottom-up design? Which best describes a function oriented design?**


In top-down design, the development process starts with an overall view of the system and then gradually decomposes it into smaller, more manageable modules or sub-systems. The decomposition continues until each module represents a specific function or task. The focus is on breaking down the problem into smaller parts and creating a hierarchical structure. It is called "top-down" because it starts from the top-level view and works its way down to the details.
        
In bottom-up design, the development process begins with small, individual components or modules, and then these modules are gradually combined to form larger modules or the complete system. The focus is on building individual components first and then assembling them to create higher-level structures. It is called "bottom-up" because it starts from the lower-level components and builds up to the system level.
        
A function-oriented design aligns more with the bottom-up design approach. It involves designing and developing individual functions or procedures that perform specific tasks. These functions are then combined to create higher-level functions or subroutines, eventually building the entire software system.
        
**In which design methodology would a class diagram be most useful?**

A class diagram is most useful in the context of object-oriented design (OOD) methodology. Class diagrams are a fundamental tool used in OOD to visualize and represent the static structure of a software system in terms of classes, their attributes, and their relationships.

In OOD, classes are the building blocks that represent real-world entities or abstract concepts, encapsulating data and behaviour. The class diagram provides a graphical representation of these classes and their relationships, helping developers and stakeholders to understand the system's structure and design.

### 

- 1. Classes: The main entities in the system, each representing an object or concept.
            
- 2. Attributes: The data members or properties of each class.
            
- 3. Methods: The behaviours or operations that each class can perform.
            
- 4. Associations: Relationships between classes, such as one-to-one, one-to-many, or many-to-many relationships.
            
- 5. Inheritance: Hierarchical relationships between classes, indicating the inheritance of attributes and methods from one class to another.
            
- 6. Aggregation and Composition: Relationships that show how classes are connected through whole-part relationships.

**What are the four pillars of object-oriented programming? Give a single-sentence description of each.**


1. Encapsulation: Bundling data (attributes) and methods (behaviour) together within a class, hiding the internal details and allowing controlled access to the object's state.
                
2. Abstraction: Focusing on essential characteristics of objects while hiding unnecessary details to simplify and represent real-world entities or concepts in a software system.
                
3. Inheritance: Allowing a class (subclass) to inherit properties and behaviours from another class (superclass), promoting code reuse and creating hierarchical relationships between classes.
                
4. Polymorphism: The ability of different classes to be treated as objects of a common superclass, enabling the same interface to be used for different data types or objects with different implementations. 


**What is the strategy pattern? How would its implementation differ between a functional and object-oriented system?**

In the Strategy Pattern, there are typically three main components:
                    
## Context: 
The context is the class that contains a reference to the strategy object and interacts with it through a common interface.

## Strategy: 
The strategy is an interface or abstract class that defines a common set of methods or operations that all concrete strategies must implement.

## Concrete Strategies:
These are the actual algorithm implementations that implement the strategy interface. Each concrete strategy provides a different behaviour to solve a particular problem.

## Implementation in a functional system:

In a functional system, the strategy pattern can be implemented using higher-order functions or function pointers. The context will take a function as an argument, which represents the selected strategy. Different functions can be passed to the context, providing different behaviours. The context will then execute the chosen strategy function when needed.
                    
## Implementation in an object-oriented system:

In an object-oriented system, the strategy pattern is implemented by defining an interface or an abstract class representing the strategy. Each concrete strategy is then implemented as a separate class that inherits from the common strategy interface. The context class holds a reference to the strategy interface and delegates the task to the selected concrete strategy.


***Imagine your is creating a new online payment system. In order to gain maximum market, share it can't be tied to a particular sector - it needs to work just as well when ordering a takeaway as when buying a new coat. Which design methodology would you suggest following? Give some justification for your decision.*** 

I would follow the "User-Centered Design" methodology to create an online payment system that works seamlessly across sectors. This approach focuses on user needs, flexibility, and iterative improvements, making it user-friendly, accessible, and market-ready for various industries.

Another reason why this methodology would be is because it focuses mainly on:
### 
- Focus on User Needs
- Flexibility and Adaptability
- Iterative Design Process
- Inclusive Design
- Reduce Friction in User Experience
- Consistency in User Interface
- Marketing and Brand Perception