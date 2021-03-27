<h1 align="center"> Basic Tutorial of Project Design </h1>

# Content

1. [Project Status](#projectstatus)
2. [About the Project](#abouttheproject)
3. [Project Description](#projectdescription)
4. [Chapter 1: Project Scope](#chapter1)
    - [Chapter 1 - Part 1: Project Scope Diagram](#chapter1part1)
    - [Chapter 1 - Part 2: Project Scope Example](#chapter1part2)
5. [Chapter 2: Project Description](#chapter2)
    - [Chapter 2 - Part 1: Detailing the Project](#chapter2part1)
    - [Chapter 2 - Part 2: Example of Project Detaling](#chapter2part2)
    - [Chapter 2 - Part 3: Entities and Entities Attribute in Description](#chapter2part3)
6. [Chapter 3: Project Use Case](#chapter3)
    - [Chapter 3 - Part 1: Use Case](#chapter3part1)
    - [Chapter 3 - Part 2: Use Case Example](#chapter3part2)
7. [Chapter 4: Project Wireframe](#chapter4)
    - [Chapter 4 - Part 1: Project Wireframe Design](#chapter4part1)
    - [Chapter 4 - Part 2: How to Make a Wireframe](#chapter4part2)
    - [Chapter 4 - Part 3: The Real Wireframe](#chapter4part3)
8. [Chapter 5: Project Domain Model](#chapter5)
    - [Chapter 5 - Part 1: Phases of a Project](#chapter5part1)
    - [Chapter 5 - Part 2: Domain Model Abstraction Level](#chapter5part2)
    - [Chapter 5 - Part 3: Conceptual Domain Model (Business)](#chapter5part3)
    - [Chapter 5 - Part 4: Conceptual Domain Model (System)](#chapter5part4)
    - [Chapter 5 - Part 5: Logical Level Domain Model (Relational)](#chapter5part5)
    - [Chapter 5 - Part 6: Logical Level Domain Model (Object Oriented)](#chapter5part6)
    - [Chapter 5 - Part 7: Physical Level Domain Model (Relational)](#chapter5part7)
    - [Chapter 5 - Part 8: Physical Level Domain Model (Object Oriented)](#chapter5part8)
    - [Chapter 5 - Part 9: The Example Domain Model](#chapter5part9)
9. [Usage](#usage)
10. [Contributors](#contributors)
11. [Contributing](#contributing)
12. [Roadmap](#roadmap)
13. [To Do](#todo)
14. [Contacts](#contacts)
15. [License](#license)

# Project Status <a name="projectstatus"></a>

Project Status: Concluded :heavy_check_mark:

# About the Project <a name="abouttheproject"></a>

This project have a propose to introduce the reader to basic concepts in (put the theme her)

[![Project][project-shield]][project-url] <!-- Put the link of the github page of the tutorial her -->

# Project Description <a name="projectdescription"></a>

This project have the object to introduce the reader the basics of "How to start and create a software" in the development world. I think, many of us, have the skills of programm (knowledge in oriented object programm language, relational database, Front-end tools like HTML, CSS and Javascript) but don't have the basics of how to get the ideia that is in the head and pass to a paper.

This tutorial will show a basic way in step-by-step form how to start simple project.
  
## <a name="chapter1"></a>Chapter 1: Project Scope

#### <a name="chapter1part1"></a>Chapter 1 - Part 1: Project Scope Diagram

The Project Scope is the first part of how to elaborate a project.

In the project scope, we will elaborate the delimitations of the project, what is part of the project and what is not and another aspects like goals, deliveries, tasks, responsabilities, deadlines and costs.

<div align="center"><img src="/img/chapter1/project-scope-w1296-h720.jpg" width=1080 height=600><br><sub>Fig 1 - Project Scope Phases</sub></div>

#### <a name="chapter1part2"></a>Chapter 1 - Part 2: Project Scope Example

In the example below, we will make a scope of a simple project.

| Project Scope Statement                                  |                                                               |                           
|:---------------------------------------------------------|--------------------------------------------------------------:|
| **Project Name**                                         | Order registration and delivery system for a pizzeria         |
| **Project Sponsor**                                      | John Ries, CEO                                                |
| **Project Manager**                                      | Vitor Garcia                                                  |
| **Date of Approval**                                     | 06/30/2019                                                    |
| **Last Updated**                                         | 06/15/2019                                                    |

1. **Scope Description**

    Purpose of the project is to optimize the delivery and order register client in GoodPi Pizzeria located in São Paulo, Brazil.

2. **Project Deliverables**

    **major project activities:**
    - project planning
    - requirement specification
    - software installation
    - adjust software to client’s needs
    - training of pizzeria employers and couriers staff

    **deliverables:**
    - project schedule
    - requirement specification document
    - ready-to-use system
    - training plan
    - training manual

3. **Acceptance Criteria**

    Successful move to new system solution over the weekend (10/27/19 – 10/28/19).

4. **Constraints**

    Due to delivery commitments to customers the system transition must be performed during the weekend.

5. **Assumptions**

    InventoryMaster consultants take over installation and configuration of software.

## <a name="chapter2"></a>Chapter 2: Project Description

#### <a name="chapter2part1"></a>Chapter 2 - Part 1: Detailing the Project

After make the project scope, we have to make a detail description of the project.

Make a description of the project is put all the details of the software (what he will have, the entities and the relation with them). Just make a simple description and pay attention in this details.

<div align="center"><img src="img/chapter2/project-description-w686-h622.jpg" width=660 height=600><br><sub>Fig 2 - Project Description Example</sub></div>

#### <a name="chapter2part2"></a>Chapter 2 - Part 2: Example of Project Detaling

In the example below, we will make a basic description of the project we are using like example.

The pizzeria GoodPi, want to implement a order and delivery system. The client enter in the website of the GoodPi and select the product that he want. This product have a id, name, price, description and image. After the client register the order, this order will generate a localization (latitude and longitude) of the client and a moment that will be send to the courier to the delivery and will be generated to the courier a map with the delivery address of the client. The order have a status and a total of the order. Each order have a localization and a order can have multiple products.

#### <a name="chapter2part3"></a>Chapter 2 - Part 3: Entities and Entities Attribute in Description

After the description, check what is will be your entities and entities attributes in the description:

<mark style="background-color: green">Green</mark> = Entity
<mark style="background-color: yellow">Yellow</mark> = Entity Attribute
<mark style="background-color: purple">Purple</mark> = Entity Relation

The pizzeria GoodPi, want to implement a order and delivery system. The client enter in the website of the GoodPi and select the product that he want. This product have a id, name, price, description and image. After the client register the order, this order will generate a localization (latitude and longitude) of the client and a moment that will be send to the courier to the delivery and will be generated to the courier a map with the delivery address of the client. The order have a status and a total of the order. Each order have a localization and a order can have multiple products.

## <a name="chapter3"></a>Chapter 3: Project Use Case

#### <a name="chapter3part1"></a>Chapter 3 - Part 1: Use Case

Lorem ipsum dolor sit amet, consectetur adipiscing elit. Integer accumsan id neque ut tempor. Nulla facilisi. Aliquam eu eros fermentum, commodo est sed, pharetra est. 
Curabitur lacinia blandit turpis rhoncus varius. Proin vulputate orci nulla, nec porttitor nibh consequat in. Suspendisse ac neque ut massa commodo auctor in sed libero. 
Sed tincidunt mauris eu tempor malesuada. Mauris feugiat vitae risus quis iaculis.

<div align="center"><img src="img/chapter3/project-use-case-w1006-h655.jpg" width=300 height=300><br><sub>Fig 3 - Project Use Case</sub></div>

#### <a name="chapter3part2"></a>Chapter 3 - Part 2: Use Case Example

Lorem ipsum dolor sit amet, consectetur adipiscing elit. Integer accumsan id neque ut tempor. Nulla facilisi. Aliquam eu eros fermentum, commodo est sed, pharetra est. 
Curabitur lacinia blandit turpis rhoncus varius. Proin vulputate orci nulla, nec porttitor nibh consequat in. Suspendisse ac neque ut massa commodo auctor in sed libero. 
Sed tincidunt mauris eu tempor malesuada. Mauris feugiat vitae risus quis iaculis.

## <a name="chapter4"></a>Chapter 4: Project Wireframe

#### <a name="chapter4part1"></a>Chapter 4 - Part 1: Project Wireframe Design

Lorem ipsum dolor sit amet, consectetur adipiscing elit. Integer accumsan id neque ut tempor. Nulla facilisi. Aliquam eu eros fermentum, commodo est sed, pharetra est. 
Curabitur lacinia blandit turpis rhoncus varius. Proin vulputate orci nulla, nec porttitor nibh consequat in. Suspendisse ac neque ut massa commodo auctor in sed libero. 
Sed tincidunt mauris eu tempor malesuada. Mauris feugiat vitae risus quis iaculis.

<div align="center"><img src="img/chapter4/project-wireframe-w1295-h511.jpg" width=300 height=300><br><sub>Fig 4 - Project Wireframe</sub></div>

<div align="center"><img src="img/chapter4/project-wireframe-2-w1063-h762.jpg" width=300 height=300><br><sub>Fig 5 - Project Web Wireframe</sub></div>

<div align="center"><img src="img/chapter4/project-wireframe-3-w861-h755.jpg" width=300 height=300><br><sub>Fig 6 - Project Mobile Wireframe</sub></div>

#### <a name="chapter4part2"></a>Chapter 4 - Part 2: How to Make a Wireframe

Lorem ipsum dolor sit amet, consectetur adipiscing elit. Integer accumsan id neque ut tempor. Nulla facilisi. Aliquam eu eros fermentum, commodo est sed, pharetra est. 
Curabitur lacinia blandit turpis rhoncus varius. Proin vulputate orci nulla, nec porttitor nibh consequat in. Suspendisse ac neque ut massa commodo auctor in sed libero. 
Sed tincidunt mauris eu tempor malesuada. Mauris feugiat vitae risus quis iaculis.

#### <a name="chapter4part3"></a>Chapter 4 - Part 3: The Real Wireframe

Lorem ipsum dolor sit amet, consectetur adipiscing elit. Integer accumsan id neque ut tempor. Nulla facilisi. Aliquam eu eros fermentum, commodo est sed, pharetra est. 
Curabitur lacinia blandit turpis rhoncus varius. Proin vulputate orci nulla, nec porttitor nibh consequat in. Suspendisse ac neque ut massa commodo auctor in sed libero. 
Sed tincidunt mauris eu tempor malesuada. Mauris feugiat vitae risus quis iaculis.

<div align="center"><img src="img/chapter4/project-wireframe-4-w1103-h807.jpg" width=300 height=300><br><sub>Fig 7 - Project Real Wireframe</sub></div>

<div align="center"><img src="img/chapter4/project-wireframe-5-w950-h794.jpg" width=300 height=300><br><sub>Fig 8 - Project Real Wireframe</sub></div>

<div align="center"><img src="img/chapter4/project-wireframe-6-w950-h421.jpg" width=300 height=300><br><sub>Fig 9 - Project Real Wireframe</sub></div>

<div align="center"><img src="img/chapter4/project-wireframe-7-w1215-h737.jpg" width=300 height=300><br><sub>Fig 10 - Project Real Wireframe</sub></div>

## <a name="chapter5"></a>Chapter 5: Project Domain Model

#### <a name="chapter5part1"></a>Chapter 5 - Part 1: Phases of a Project

Lorem ipsum dolor sit amet, consectetur adipiscing elit. Integer accumsan id neque ut tempor. Nulla facilisi. Aliquam eu eros fermentum, commodo est sed, pharetra est. 
Curabitur lacinia blandit turpis rhoncus varius. Proin vulputate orci nulla, nec porttitor nibh consequat in. Suspendisse ac neque ut massa commodo auctor in sed libero. 
Sed tincidunt mauris eu tempor malesuada. Mauris feugiat vitae risus quis iaculis.

<div align="center"><img src="img/chapter5/project-phase-w1421-h802.jpg" width=300 height=300><br><sub>Fig 11 - Phases of a Project</sub></div>

<div align="center"><img src="img/chapter5/project-phase-2-w1208-h686.jpg" width=300 height=300><br><sub>Fig 12 - Phases of a Project</sub></div>

#### <a name="chapter5part2"></a>Chapter 5 - Part 2: Domain Model Abstraction Level

Lorem ipsum dolor sit amet, consectetur adipiscing elit. Integer accumsan id neque ut tempor. Nulla facilisi. Aliquam eu eros fermentum, commodo est sed, pharetra est. 
Curabitur lacinia blandit turpis rhoncus varius. Proin vulputate orci nulla, nec porttitor nibh consequat in. Suspendisse ac neque ut massa commodo auctor in sed libero. 
Sed tincidunt mauris eu tempor malesuada. Mauris feugiat vitae risus quis iaculis.

<div align="center"><img src="img/chapter5/project-phase-3-w1190-h601.jpg" width=300 height=300><br><sub>Fig 13 - Domain Model Abstraction Level</sub></div>

<div align="center"><img src="img/chapter5/project-phase-4-w889-h505.jpg" width=300 height=300><br><sub>Fig 14 - Domain Model Abstraction Level</sub></div>

#### <a name="chapter5part3"></a>Chapter 5 - Part 3: Conceptual Domain Model (Business)

Lorem ipsum dolor sit amet, consectetur adipiscing elit. Integer accumsan id neque ut tempor. Nulla facilisi. Aliquam eu eros fermentum, commodo est sed, pharetra est. 
Curabitur lacinia blandit turpis rhoncus varius. Proin vulputate orci nulla, nec porttitor nibh consequat in. Suspendisse ac neque ut massa commodo auctor in sed libero. 
Sed tincidunt mauris eu tempor malesuada. Mauris feugiat vitae risus quis iaculis.

<div align="center"><img src="img/chapter5/project-phase-5-w1427-h806.jpg" width=300 height=300><br><sub>Fig 15 - Conceptual Domain Model (Business)</sub></div>

#### <a name="chapter5part4"></a>Chapter 5 - Part 4: Conceptual Domain Model (System)

Lorem ipsum dolor sit amet, consectetur adipiscing elit. Integer accumsan id neque ut tempor. Nulla facilisi. Aliquam eu eros fermentum, commodo est sed, pharetra est. 
Curabitur lacinia blandit turpis rhoncus varius. Proin vulputate orci nulla, nec porttitor nibh consequat in. Suspendisse ac neque ut massa commodo auctor in sed libero. 
Sed tincidunt mauris eu tempor malesuada. Mauris feugiat vitae risus quis iaculis.

<div align="center"><img src="img/chapter5/project-phase-6-w1441-h811.jpg" width=300 height=300><br><sub>Fig 16 - Conceptual Domain Model (System)</sub></div>

#### <a name="chapter5part5"></a>Chapter 5 - Part 5: Logical Level Domain Model (Relational)

Lorem ipsum dolor sit amet, consectetur adipiscing elit. Integer accumsan id neque ut tempor. Nulla facilisi. Aliquam eu eros fermentum, commodo est sed, pharetra est. 
Curabitur lacinia blandit turpis rhoncus varius. Proin vulputate orci nulla, nec porttitor nibh consequat in. Suspendisse ac neque ut massa commodo auctor in sed libero. 
Sed tincidunt mauris eu tempor malesuada. Mauris feugiat vitae risus quis iaculis.

<div align="center"><img src="img/chapter5/project-phase-7-w1438-h814.jpg" width=300 height=300><br><sub>Fig 17 - Logical Level Domain Model (Relational)</sub></div>

#### <a name="chapter5part6"></a>Chapter 5 - Part 6: Logical Level Domain Model (Object Oriented)

Lorem ipsum dolor sit amet, consectetur adipiscing elit. Integer accumsan id neque ut tempor. Nulla facilisi. Aliquam eu eros fermentum, commodo est sed, pharetra est. 
Curabitur lacinia blandit turpis rhoncus varius. Proin vulputate orci nulla, nec porttitor nibh consequat in. Suspendisse ac neque ut massa commodo auctor in sed libero. 
Sed tincidunt mauris eu tempor malesuada. Mauris feugiat vitae risus quis iaculis.

<div align="center"><img src="img/chapter5/project-phase-8-w1429-h809.jpg" width=300 height=300><br><sub>Fig 18 - Logical Level Domain Model (Object Oriented)</sub></div>

#### <a name="chapter5part7"></a>Chapter 5 - Part 7: Physical Level Domain Model (Relational)

Lorem ipsum dolor sit amet, consectetur adipiscing elit. Integer accumsan id neque ut tempor. Nulla facilisi. Aliquam eu eros fermentum, commodo est sed, pharetra est. 
Curabitur lacinia blandit turpis rhoncus varius. Proin vulputate orci nulla, nec porttitor nibh consequat in. Suspendisse ac neque ut massa commodo auctor in sed libero. 
Sed tincidunt mauris eu tempor malesuada. Mauris feugiat vitae risus quis iaculis.

<div align="center"><img src="img/chapter5/project-phase-9-w1432-h811.jpg" width=300 height=300><br><sub>Fig 19 - Physical Level Domain Model (Relational)</sub></div>

#### <a name="chapter5part8"></a>Chapter 5 - Part 8: Physical Level Domain Model (Object Oriented)

Lorem ipsum dolor sit amet, consectetur adipiscing elit. Integer accumsan id neque ut tempor. Nulla facilisi. Aliquam eu eros fermentum, commodo est sed, pharetra est. 
Curabitur lacinia blandit turpis rhoncus varius. Proin vulputate orci nulla, nec porttitor nibh consequat in. Suspendisse ac neque ut massa commodo auctor in sed libero. 
Sed tincidunt mauris eu tempor malesuada. Mauris feugiat vitae risus quis iaculis.

<div align="center"><img src="img/chapter5/project-phase-10-w1440-h818.jpg" width=300 height=300><br><sub>Fig 20 - Physical Level Domain Model (Object Oriented)</sub></div>

#### <a name="chapter5part9"></a>Chapter 5 - Part 9: The Example Domain Model

Lorem ipsum dolor sit amet, consectetur adipiscing elit. Integer accumsan id neque ut tempor. Nulla facilisi. Aliquam eu eros fermentum, commodo est sed, pharetra est. 
Curabitur lacinia blandit turpis rhoncus varius. Proin vulputate orci nulla, nec porttitor nibh consequat in. Suspendisse ac neque ut massa commodo auctor in sed libero. 
Sed tincidunt mauris eu tempor malesuada. Mauris feugiat vitae risus quis iaculis.

<div align="center"><img src="img/chapter5/conceptual-model-example-w1235-h695.jpg" width=300 height=300><br><sub>Fig 21 - The Example Domain Model</sub></div>

<div align="center"><img src="img/chapter5/conceptual-model-instance-example-w1459-h688.jpg" width=300 height=300><br><sub>Fig 22 - The Example Domain Model</sub></div>


# Usage <a name="usage"></a>

Using this like a bibliography if you want to remember project design concepts. For more information, use this [PDF][pdf-url]

# Contributors <a name="contributors"></a>

| [<img src="https://github.com/vitorstabile.png" width=115 > <br> <sub> Vitor Garcia </sub>][github-url] | 
| :-----------------------------------------------------------------------------------------------------: |

# Contributing <a name="contributing"></a>

Contributions are what make the open source community such an amazing place to be learn, inspire, and create. Any contributions you make are **greatly appreciated**.

1. Fork the Project
2. Create your Feature Branch (`git checkout -b feature/AmazingFeature`)
3. Commit your Changes (`git commit -m 'Add some AmazingFeature'`)
4. Push to the Branch (`git push origin feature/AmazingFeature`)
5. Open a Pull Request

# Roadmap <a name="roadmap"></a>

See the [![Issues][issues-shield]][issues-url]  for a list of proposed features (and known issues).

# To Do <a name="todo"></a>

Project Completed

# Contacts <a name="contacts"></a>

| Vitor Garcia                                     |
| :----------------------------------------------- |
| [![LinkedIn][linkedin-shield]][linkedin-url]     |
| [![Portfolio][portfolio-shield]][portfolio-url]  |
| [![GitHub][github-shield]][github-url]           |

# License <a name="License"></a>

- [![MIT License][license-shield]][license-url]

- Distributed under the MIT License. See `LICENSE` for more information.


<!-- README TUTORIALS -->

<!--

https://dev.to/reginadiana/como-escrever-um-readme-md-sensacional-no-github-4509

-->

<!-- 

Mark Down Guide - Readme Text Format Style

https://www.markdownguide.org/

-->

<!-- 

How to Create your Badges

https://gist.github.com/rupeshtiwari/8558ca0d8ec1c15619e4492dcd6aa81a

-->

<!-- USEFUL LINKS -->

<!--

Free Images Without Copyright

https://unsplash.com/


-->

<!-- MY BADGES -->

[project-shield]: https://img.shields.io/badge/link-project-green.svg
[project-url]: https://github.com/vitorstabile/projects-design-basics
[linkedin-shield]: https://img.shields.io/badge/my-linkedin-blue.svg 
[linkedin-url]: https://www.linkedin.com/in/vitor-stabile-garcia-5b151b67
[portfolio-shield]: https://img.shields.io/badge/my-portfolio-red.svg
[portfolio-url]: https://vitorstabile.github.io
[github-shield]: https://img.shields.io/badge/my-github-green.svg
[github-url]: https://github.com/vitorstabile
[issues-shield]: https://img.shields.io/badge/link-issues-green.svg
[issues-url]: https://github.com/vitorstabile/projects-design-basics/issues
[license-shield]: https://img.shields.io/badge/license-mit-blue.svg 
[license-url]: https://github.com/vitorstabile/projects-design-basics/blob/master/LICENSE.txt
[pdf-url]: https://github.com/vitorstabile/projects-design-basics/blob/master/Apostila%20An%C3%A1lise%20e%20Design%20de%20Sistemas%20-%20Nelio%20Alves%20-%20Ed%202020.pdf
