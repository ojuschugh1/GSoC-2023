# GSoC-2023
# Google Summer of Code
*Project Details and Work done during the GSoC 2023 programme*

## About The Project

**Eclipse Cargo Tracker - Applied Domain-Driven Design Blueprints for Jakarta EE**

The project demonstrates how you can develop applications with Jakarta EE using widely adopted architectural best practices like Domain-Driven Design (DDD). The project is directly based on the well known original Java DDD sample application developed by DDD pioneer Eric Evans' company Domain Language and the Swedish software consulting company Citerus. The cargo example actually comes from Eric Evans' seminal book on DDD. The original application is written in Spring, Hibernate and Jetty whereas the application is built on Jakarta EE.

The application is an end-to-end system for keeping track of shipping cargo. It has several interfaces described in the following sections.

For further details on the project, please visit: https://eclipse-ee4j.github.io/cargotracker/.

A slide deck introducing the fundamentals of the project is available on the official Eclipse Foundation Jakarta EE SlideShare account. A recording of the slide deck is available on the official Jakarta EE YouTube account.

See Eclipse SWTChart on [Eclipse](https://projects.eclipse.org/projects/ee4j.cargotracker), [Github](https://github.com/eclipse-ee4j/cargotracker)  
See this project on [Google Summer of code](https://summerofcode.withgoogle.com/projects/#5104569337511936)  
Mentor - [Reza Rahman](https://github.com/m-reza-rahman)

**Project Accomplished Milestones**

1. 




PRs for addtion of LineChart to the Template Export-

1. [Pull Request 1](https://github.com/eclipse/swtchart/pull/171)

2. [Pull Request 2](https://github.com/eclipse/swtchart/pull/173)

PRs for addition of BarChart to the Template Export-

1. [Pull Request 1](https://github.com/eclipse/swtchart/pull/176)

PRs for addition of ScatterChart to the Template Export-

1. [Pull Request 1](https://github.com/eclipse/swtchart/pull/184)

The above changes added the SVG Template Export option to SWTChart,
However, there were further changes needed for optimized and efficient working of the export option

Following were the PRs related to issues and bug fixing and further optimization-

1. [Pull Request 1](https://github.com/eclipse/swtchart/pull/193)

2. [Pull Request 2](https://github.com/eclipse/swtchart/pull/195)

3. [Pull Request 3](https://github.com/eclipse/swtchart/pull/197)

4. [Pull Request 4](https://github.com/eclipse/swtchart/pull/199)

5. [Pull Request 5](https://github.com/eclipse/swtchart/pull/222)

Here are some final sample exports showcasing the template export at work-

<img src="./Untitled1.svg" height="500" width="500">

<img src="./Untitled2.svg" height="500" width="500">

<img src="./Untitled4.svg" height="500" width="500">

Future work and improvements may include the following-

1. Find a way to remove the Hard Coded Coordinates for better code readability

2. Adding Symbols, Symbol Size and LineStyles to the exported series


## Extending the Export Settings Dialog for Series Selection

The Export Settings Dialog was enhanced and improve to support runtime
selection of series to be exported in various export.

This allows user to easily change the series selection and
control the visibility of a series in the export

PR for the change-

1. [Pull Request 1](https://github.com/eclipse/swtchart/pull/210)

### A screenshot of the feature

<img src="./Screenshot from 2020-07-24 15-21-21.png" height="500" width="500">


## Performance Improvement in R-Script Export Option

There were improvements in R-Script regarding styling 
, addition of different symbols and improvement in the scatter plot.

PRs for the above changes-

1. [Pull Request 1](https://github.com/eclipse/swtchart/pull/216)

2. [Pull Request 2](https://github.com/eclipse/swtchart/pull/219)

3. [Pull Request 3](https://github.com/eclipse/swtchart/pull/226)

Here are the screenshots for the improvements 

<img src="./Screenshot from 2020-08-07 16-32-36.png" height="500" width="500">

<img src="./Screenshot from 2020-08-21 13-27-30.png" height="500" width="500">

<img src="./Screenshot from 2020-08-21 13-52-14.png" height="500" width="500">

<img src="./Screenshot from 2020-08-21 13-53-44.png" height="500" width="500">

### Contact information-<br> 

Name- Ojus Chugh <br>

Mail- ojuschugh@gmail.com <br>

Github- https://github.com/ojuschugh1
