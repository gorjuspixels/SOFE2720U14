# Software Requirements - Midterm Review

__Software Engineering__ is an engineering discipline that is concerned with __with all aspects of software production__ 

Software __does not wear out__ but __deteriorates__

## Software Applications

### System software
![USB key](http://www.clker.com/cliparts/7/e/2/b/13486078491409878523USB%20Drive%20Icon.svg.med.png "USB icon")
- Collection of programs written to service other programs
- Examples: __compilers__, __editors__, __drivers__..

### Application software
![Bank](http://icons.iconarchive.com/icons/icons-land/gis-gps-map/256/Bank-icon.png "Bank icon")
- Standalone software that solves specific business need
- Examples: __Payroll systems__, __accounting system__, __banking system__..

### Engineering/scientific software
![AUTOCAD](http://pat.ca/wp-content/uploads/2013/03/autocad-2014-badge-200px.png "AUTOCAD")
- "Number crunching" algorithms
- Examples: __numerical analysis__, CAD, __system simulation__..

### Embedded software
![ATM](http://icons.iconarchive.com/icons/designcontest/ecommerce-business/256/atm-money-icon.png "ATM")

- Resides in ROM & is used to control products and systems for the customer
- Examples: __cars__, __ATM__, __washing machines__..

### Personal computer software

![Microsoft Word Icon](http://cdn5.groovypost.com/wp-content/uploads/2012/07/image224.png "Microsoft Word")
- Provides a specific capability for use by many different customers
- Examples: __word processors__, __spreadsheets__, db management..

### A.I. software:
![Computer Brain](http://hotdigitalnews.com/wp-content/uploads/2013/06/NeuralNetwork.jpg "Computer Brain")
- Utilize non-numeric algorithms to solve complex problems
- Examples: __patten recognition__, __language recognition__, __neural networks__..

## __Software Engineering__

Is a collection of techniques, methodologies, and tools that help with the production of software

A high quality software system developed with a given budget before a given deadline while change occurs

## Software Live Cycle Modeling

There are many different models to deal with the problems of defining activities and associating them with each other

![Comparison of all life cycle models](http://s22.postimg.org/3lkp3uwk1/Selection_083.png)

### Waterfall Life Cycle Model
![Waterfall Diagram](http://oi58.tinypic.com/eiqk2g.jpg)

- Each phase is considered complete only after the __documentation__ is finalized
- If changes are necessary as a result of a __feedback__ loop, the phase is complete after the documentation has been modified

Advantages | Disadvantages
--- | ---
Proper documentation for each phase | Specification documents are lengthy
Proper milestones | Software Development is iterative

#### Moving Target Problem

- A change in the requirements while the software is being developed
- Any change could cause a _regression fault_
- If there are too many changes, entire product may have to be redesigned
- __Change is inevitable__
- __Changes are always needed__
- No solution to this problem

### Rapid Prototyping Model

![Rapid prototyping model diagram](http://s1.postimg.org/4odasu0n3/Selection_078.png)
- Linear model
- Rapid prototype is simply creating a prototype that is functionally equivalent to a subset of the products
- Build a rapid prototype and let client/users interact with it
- __Disadvantage__: once client actual needs are determined, prototype is discarded

### Spiral Model

![Spiral Model diagram](http://s10.postimg.org/h4aw1n2ix/Selection_079.png)
- Rapid prototyping + risk analysis preceding each phase
- If all risks cannot be mitigated, the project is terminated

### Iterative and Incremental Life Cycle Model
#### Iterative Approach

- Lifecycle is composed of multiple iterations in sequence
- Each iteration is like a mini project
- Software from all teams is integrated into a release at the end of each iteration

##### Timeboxed Iterations

- __Timeboxing means__
	+ Set an iteration end dae
	+ Date for iteration __cannot__ be changed
	+ Timebox lengths do not have to be equal
- Once requests for an iteration are chosen, __no changes can be done__

#### Incremental Approach

- Each iteration is performance tunning
- Allows the system to grow incrementally with new features
- Software resulting from each iteration is __not__ a prototype or proof of concept, but a __subset__ of the final system

![Iterative Life Cycle](http://s17.postimg.org/3yv0t7fy7/Selection_080.png)

__Miller's Law:__
- To handle large amounts of information, use _stepwise refinement_
	+ Concentrate on the aspects that are currently the most important
	+ Postpone aspects that are currently less critical
	+ __Incremental approach__

__Risk Driven Iterative Planning__
- Choose the riskiest and difficult elements at early iterations

__Client-Driven Iterative Planning__
- Choice of features for iterations is given by the client	


### Rvolutionary & Adaptive Life Cycle Models

#### Evolutionary

- Requirements, plans, estimates, and solution evolve over the course of the iterations
	+ Don't have to define up-front specifications
	+ Suitable with the pattern of __unpredictable discovery and change__

#### Adaptive

- Elements __adapt__ based on the prior work (feedback, tests, developers, etc)
- Similar to evolutionary but more emphasis on __feedback__

### Code-and-Fix Life Cycle Model
![Life Cycle diagram](http://s28.postimg.org/cvn5enw19/Selection_081.png)
- No design
- No specifications
- The easiest way to develop software
- The most expensive way for maintenance
- Mainly used in small projects

### Open-Source Life Cycle Model
![Open Source Life Cycle](http://s7.postimg.org/rimaq5trv/Selection_082.png)

__First Informal Phase__
- An individual builds an initial version
- If there is public interest, users become co-developers
- Co-developers work voluntarily on an open-source project in their spare time

__Second Informal Phase__
- Reporting and correcting bugs
- This phase depends on post-delivery maintenance

___

# The Descipline of Software Engineering Design


Software Product Design | Software Engineering Design
--- | ---
Styling | Technical mechanism
Function & usability | Code and algorithms
Manufacturability | The workings of the product
Manageability | Sub-systems and their constituent parts


## UML

__Activity__ - specification of a parameterized sequence of behaviour
- Used to show the workflow from start to finish
- Shown as a round-cornered rectangle
- Can be broken down into actions

__Actions__

![Action UML](http://www.sparxsystems.com/images/screenshots/uml2_tutorial/ad07.GIF)

- Represents a single step within an activity. Actions are denoted by round-cornered rectangles.

__Action Constraints__

![Action Constraints](http://www.sparxsystems.com/images/screenshots/uml2_tutorial/ad01.GIF)

Constraints can be attached to an action.

__Control Flow__

![Control Flow](http://www.sparxsystems.com/images/screenshots/uml2_tutorial/ad06.GIF)

A control flow shows the flow of control from one action to the next. Its notation is a line with an arrowhead.

__Initial Node__

![Initial Node](http://www.sparxsystems.com/images/screenshots/uml2_tutorial/ad14.GIF)

An initial or start node is defined by a black circle.

__Final Node__

![Final Node](http://www.sparxsystems.com/images/screenshots/uml2_tutorial/ad04.GIF)

Activity final node is defined as a circle with a smaller black circle inside.

__Activity Parameter__

- Object nodes placed on activity symbol boundaries to indicate data or object inputs/output
- Can contain data or object name

__Decision & Merge Nodes__

![Decision & Merge Nodes](http://www.sparxsystems.com/images/screenshots/uml2_tutorial/ad08.GIF)

- Diamond shaped
- Decision node has guard conditions which allows to control the flow

__Fork & Join Nodes__

![Fork & Join Nodes](http://www.sparxsystems.com/images/screenshots/uml2_tutorial/ad10.GIF)

- Indicates the start and end of concurrent threads of control

__Exception Handlers__

![Exception Handlers](http://www.sparxsystems.com/images/screenshots/uml2_tutorial/ad11.GIF)

- Modelled by a "lightning" arrow

___

## Software Design Activities

__6 Steps__:

__1. Analyize the problem__
- Obtain info about the problem and break it down
- Outcome: produce a clear problem statement to guide the remainder of the process
	
__2. Generate/Improve Candidate Solutions__
- Generate one or more possible solutions or improve the ones generated before

__3. Evaluate Candidate Solutions__
- Evaluate newly generated or improved solutions

__4. Select Solutions__
- Rank the solutions, select the best one or select a few for further improvement

__5. Iterate__
- If misunderstanding is discovered, return to step 1 to correct it
- If none of the solutions is adequate, return to step 2 to improve the best solutions or generate new ones

__6. Finalize the Design__
- Make sure that the design process and the final solutions are well documented and deliver the finished design

___

## Software Design Management

#### Project Management Activities

- __Planning__ - formulating a scheme for doing a project.
- __Organizing__ - Structuring people in the project and assigning them authorities and responsibilities
- __Staffing__ - filling the positions in an organizational structure and keeping them filled
- __Tracking__ - observing the progress of work and adjusting work and plans accordingly
- __Leading__ - Directing and supporting people doing project

### Project Planning

- How much work must be done and the resources needed to do it
- __Estimation__ - calculation of the approximate cost, effort, time or resources required to achieve some end
- __Risk Analysis__ - identifying, understing, and assessing risks

### Project Organization and Staffing

- __Organizational structures:__ organize people
	+ Project organization
	+ Functional organization
	+ Matrix organization

- __Team structures:__ ways people make decisions
	+ Hierarchical teams
	+ Democratic teams

- __Staffing:__ filling the roles
	+ Often the single most important factor in success is having good people to do the work

### Project Tracking

- Projects may not go as planned for many reasons
- Plans must be adjusted

### Leading a Project

- Direction is needed to follow plans, use resources efficiently, etc.
- Directing people is not enough - people need inspiration, help, a friendly work environment, emotional support, etc.

___

# Context of Software Product Design

#### Product Categories
Type | Description | Examples
--- | --- | ---
New | Different from anything else in the product line | Tax preparation product in a line of a ccounting products
Derivative | Similar to one or more existing product in the product line | Database management system for individual users in a line of systems for corporate users
Maintenance Release | New release of an existing product | Third release of a spreadsheet

