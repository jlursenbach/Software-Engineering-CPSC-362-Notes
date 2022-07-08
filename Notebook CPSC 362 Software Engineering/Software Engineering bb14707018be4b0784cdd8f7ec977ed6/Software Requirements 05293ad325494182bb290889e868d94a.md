# Software Requirements

[L02_Requirements.pdf](Software%20Requirements%2005293ad325494182bb290889e868d94a/L02_Requirements.pdf)

# Recap from last class:

<aside>
ℹ️ Requirements:

</aside>

<aside>
ℹ️ **Architecture:** Designs how the modules will be structured. Even before the coding, this develops the shape and format of what will be the final product. It makes software development a very simple and systematic task

Architect decides: you develop this module, that module etc.

</aside>

<aside>
ℹ️ Design: Creating the code

</aside>

<aside>
ℹ️ Implementation: Coding

</aside>

<aside>
ℹ️ Testing: 
-unit testing:
- - the developer does unit testing and creates immediate tests for production. 

Test cases are created both for specific customer requirements, and single module tests are constructed while coder is writing the code.

sometimes testing is actually outsourced to other businesses

</aside>

<aside>
ℹ️ Deploy: 
Staging: a process before launching publicly, that runs the product in a pseudo-real life situation. Ensures no catastrophic failures on launch

</aside>

<aside>
ℹ️ Maintenance

</aside>

Quality Insurance

- in mission critical situations, quality is the number 1 concern
- -

## QUALITY CHARACTERISTICS:

### Meeting customer requirements

1. functional
    1. Does it work
2. nonfunctional
    1. does it work like I want it to
    2. ex: scalability

### Easy to Maintain

1. Easy to understand
2. easy to change the code
3. easy to extend

### Reusability

# Defining Software Requirements:

<aside>
ℹ️ What are the features which are required for the final product?

</aside>

A condition or capability that must be met or possessed by a system or
system component to satisfy a contract, standard, specification, or other
formally imposed documents

Software Requirements Specification (SRS) is written requirements for a software
system.

## Types of requirements

### Functional requirements

- The software functionalities, satisfying the business requirements.

### Developer (functional requirements)

- Implements functions from the viewpoint of the system. Provides internal behavior, algorithms, storage which all support and create the experience that is defined in the use case

### Nonfunctional requirements

- Characteristics (quality attributes and constraints) that a system must exhibit or restriction
it must respect.
    - Quality Attributes (performance, availability, scalability, efficiency, security,
    usability, integrity, robustness, etc.)
    - Constraints to be met (e.g., legal compliance)

## Requirements Development Process

![Untitled](Software%20Requirements%2005293ad325494182bb290889e868d94a/Untitled.png)

- Incremental, iterative, and interleaved
    - incremental
    - iterative
    - interleaved

each time you go through the cycle, remembre the requirements may incrementally change. You generally will not have caught all of the requirements in teh first iteration of the planning process.

 

## Writing Requirements

### Use/Stakeholder requirements (use case or story)

- Descriptions of how the user will use, typically written in use case or user story
    - to create a product for a marketplace, you need to understand how the marketplace works
    - you might end up knowing the business better than the people in that business, because they don’t have to (or can’t) spend time understanding their entire business.
- Example: “The registered users log into the system with ID and password.”

### System requirements

- Descriptions of system features
    - Functional requirements for system feature or functions, written in terms of input,
    processing, and output (or stimulus/response sequence)
    - Non-functional requirements for quality attributes such as scalability, efficiency
- Example: “The system must allow the users to log into their account when they
enter ID and password.”
    - Requirement descriptions for developer
- Use case or user story can be used for both user and system requirements.

### Requirements analysis modeling for complex requirements

- Context diagram, activity diagram, data flow diagram, use case diagram

## Requirements Map

![Untitled](Software%20Requirements%2005293ad325494182bb290889e868d94a/Untitled%201.png)

## Use Cases vs Functional Requirements

## Some Words to Avoid in writing requirements

Minimize, maximize, optimize
User-friendly, rapid, easy, simple, intuitive, efficient, flexible,
robust
Seamless, transparent, graceful
Improved, state-of-the-art, superior
Sufficient, adequate, at least
Reasonable, where appropriate, to the extent possible, if
necessary
Few, several, some, many
Etc., including, and/or
Optionally and many other adverbs
Support
Symbols or abbreviations, i.e. (that is), e.g. (for example)

## Use Cases*

- external program behavior and appearance. Takes the viewpoint of the customer
    - example of use case **(*essential elements*)**:
        - ***ID*:**
        - ***Name*:**
        - Description: (optional some times)
        - ***Primary Actor*:**
        - Preconditions:
        - Postconditions:
        - ***Main Success Scenario (flow)*:**
    - graphical representation:
        
        ![Untitled](Software%20Requirements%2005293ad325494182bb290889e868d94a/Untitled%202.png)
        

## User Story*

<aside>
ℹ️ a brief description of feature for the
end user commonly used in agile process.

</aside>

### Key Elements:

- Story id and name (action word)
- User (actor)
- Feature description for the user, doing a function
(task or steps to perform) to achieve a goal
    - Non-functional requirements can be specified as constraints
    - 

Informal story cards:

![Untitled](Software%20Requirements%2005293ad325494182bb290889e868d94a/Untitled%203.png)

A well structured story card:

![Untitled](Software%20Requirements%2005293ad325494182bb290889e868d94a/Untitled%204.png)

What should a story card countain:

- Story identifier and name
- Story Description
    - a sentence ot two that describes the feature int he customer name
- Story Type
    - C = customer domain
    - T = technology domain
- Estimated work/effort
    - the estimated work or effort needed to deliver the story.
    - Includes time for
        - requirements gathering
        - design
        - coding
        - testing
        - documentation
    - Estimated value points (described in chapter 8)
    - Requirements uncertainty:
        - Erratic
        - fluctuating
        - routine
        - stable
    - Story dependencies:
        - what dependencies could influence the implimentation sequencing
    - Acceptance tests:
        - What are the criteria the customer team will use to accept or reject the story

![Untitled](Software%20Requirements%2005293ad325494182bb290889e868d94a/Untitled%205.png)

## Pros and cons of Use Cases and Stories

### Pros:

- Use cases works well for:
    - End-user applications
    - Websites
    - Devices that require user interactions
    - Services provided by one system to another

### Cons:

- Use cases aren’t as valuable for:
    - Batch processes
    - Computation-intensive systems
    - Database or data processing projects

# Requirements Analysis Modeling

<aside>
ℹ️ Diagrams aren’t used a lot in software development. They’re usually only used for complex systems that are hard to understand. For simple projects they can be a waste of time. If you do create one, you can connect it to the user story or function requirement

</aside>

- Unified Modeling Language (UML) building blocks for use case diagram:
    - Circle: use case; Human shape: actor, Box: subsystem, system boundary;
    Line: association between actor and use case; Arrow: the direction of initiation,
    also indicating primary actor→ and →secondary actor.
    - Use case names are typically written: Active verb + Object
    - an example:
        
        ![Untitled](Software%20Requirements%2005293ad325494182bb290889e868d94a/Untitled%206.png)
        

## Requirements Analysis Model

![Untitled](Software%20Requirements%2005293ad325494182bb290889e868d94a/Untitled%207.png)

| • R1: all processes have both input
and output
• R2: all processes are connected to
either other processes entities or
database
• R3: all processes have unique
names & numbering, e.g., subprocesses shall follow the
numbering scheme of the parent
process
• R5: Information continuity must be
kept. Information Continuity: The
net I/O to the refinement must
remain the same.
• R6: The refinement per level
should be 3 ~7. |
| --- |

<aside>
ℹ️ THERE ARE A NUMBER OF DIAGRAMS CURRENTLY MISSING. Lecture pages 12-19

</aside>