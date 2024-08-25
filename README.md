# Introduction
Hello! My name is Tomas Estanislao, and this is my final Capstone project for my BSCS. 

I transferred to Southern New Hampshire University around one year ago, in order to affordably finish my degree online. Through my coursework in this program, I have gained numerous technical and soft skills— and have been exposed to various CS domains.   

I will briefly cover a few topics that will highlight skills that I have gained throughout my coursework. 

### Collaboration
There are two things that immediately come to mind when thinking about collaboration: version control and methodology. When it comes to physically writing code, developing and testing, using git effectively is crucial. I was able to work with git in CS465 and practice using branches and frequent committing to stay organized. 

![Branching](/assets/collaboration1.png)
_[repository](https://github.com/Testanislao/cs465-fullstack/tree/main)_

In CS250, I learned about different software development methodologies and practiced the roles within an agile team. I also researched different collaborative tools, such as _Gherkin_, which was illuminating.

![Methodology](/assets/collaboration2.png)
_[repository](https://github.com/Testanis396/CS250/tree/main)_

### Communication

In terms of communication, I have practiced system design, diagramming, and presentations. CS255 was an interesting class where I learned not only how to analyze systems, but also how to graphically illustrate them in meaningful ways. These two skills combine to provide powerful tools for communicating with stakeholders. 

![Stakeholder Presentation](/assets/communication1.png)
![System Design Document](/assets/communication2.png)
_[repository](https://github.com/Testanis396/CS255/tree/main)_

### Data Structures/Algorithms

In CS320, I created custom classes and services for: Contacts, Tasks, and Appointments. I designed these data structures in addition to JUnit tests. I focused on the functional requirements, using: automated, regression, boundary, and negative testing. Code coverage was a tool that I had heard about, but never understood. I used coverage to ensure that all branches were being appropriately accessed and tested as well. 

![Data Structures](/assets/data1.png)
_[repository](https://github.com/Testanis396/CS320/tree/main)_

### Software Engineering/Databases

I am proud of my work in CS330 to create a 3d scene. I was able to demonstrate my skills with a lower level language, while also leveraging my math background to implement low-poly shapes. I used formulaes to manually create circles with over twenty vertices, properly connecting and shading, resulting in objects such as: Spheres, Toruses, Cylinders, and Hexagonol/Rectagonal Prisms. My Linear Algebra and Multivariable Calculus background was especially helpful in dealing with vectors. 

![Software Engineering](/assets/software1.png)
_[repository](https://github.com/Testanis396/CS330-3DScene/tree/main)_

In CS340 I interacted with MongoDB for the first time, building an interative dashboard to visualize data. I was impressed by how easy it was to set up these tools and frameworks, while also excited to create custom queries and practice some UI/UX skills. This was one of the first projects where I considered pursuing a career and further education dealing with data. 

![Software Engineering](/assets/software2.png)
_[repository](https://github.com/Testanis396/CS340/tree/main)_

### Security

CS305 was a fun class where I learned about vulnerabilties and certificates. I learned about tools like OWASP dependency check and Synk, while researching on the practice of protecting HTTP communications. 

![Security](/assets/security1.png)
_[repository](https://github.com/Testanis396/CS305/tree/main)_

CS465 focused more on authentication middleware, and how tokens could be used to prevent unauthorized API calls. I incorporated these skills within my project enhancements. 

```js
const express = require('express');
const router = express.Router();
const { expressjwt: jwt } = require('express-jwt');
const auth = jwt({
    secret: process.env.JWT_SECRET,
    userProperty: 'payload',
    algorithms: ['HS256']
});
```
_[repository](https://github.com/Testanislao/cs465-fullstack/tree/main)_

### Artifact Summary

When brainstorming ideas for artifact selection and enhancement, I was uncertain of the idea of choosing three seperate artifacts. Although I understood the reasoning behind the three main categories, I had a hard time imagining how to focus in on each one. My thought process was that each of these three areas are so interconnected— if not all within a single app or service, then definitely within an entire project. This led me to re-visisting my CS465 fullstack [web-app](https://github.com/Testanislao/cs465-fullstack/tree/main). It already incorperates all three categories, so it was easy visualize potential enhancements: expanding the API, re-designing the Models, and manipulating the Data. This original artifact is a type of project that I want to gain much more familiarity with and build upon. 

However, I did not think that focusing so heavily on an existing project- from a previous class- was overly meaningful to a capstone project. Thus, I decided to combine this artifact with a small personal project of mine: a web [scraper](https://github.com/Testanis396/WebScraper/tree/main). This would cover different aspects of _Data_ collection and manipulation, while re-designing the api to interface with a new database would require new _Data Structures_ and _System Design_. Combining these artifacts provides an opportunity to demonstrate skills in a common responsibility of backend developers, while also exploring how to work with data. 

The fullstack web-app is for managing and displaying vacation packages on a website. The web-scraper processes publically available web novel information from [Royal Road](https://www.royalroad.com/fictions/search?) into a JSON file. Through each enhancement, the goal was to focus on re-designing the api to meaningfully interact with a new dataset- emulating the use case of a personal reading list. 

### Portfolio Items 

*  Github Portfolio [Repository](https://github.com/Testanis396/Testanis396.github.io/tree/main)
  
*   Milestone One Code Review [Link](https://youtu.be/LcpNidBBbhM)
*   Milestone Two Original [Files](/Enhancement1/Estanislao3-2Original.zip)
*   Milestone Two Enhanced [Files](/Enhancement1/Estanislao3-2Enhance1.zip)
*   Milestone Two Narrative [Doc](/Enhancement1/Estanislao3-2MilestoneTwoNarrative.docx)
*   Milestone Three Original [Files](/Enhancement2/Estanislao4-2Original.zip)
*   Milestone Three Enhanced [Files](/Enhancement2/Estanislao4-2Enhance2.zip)
*   Milestone Three Narrative [Doc](/Enhancement2/Estanislao4-2MilestoneThreeNarrative.docx)
*   Milestone Four Original [Files]()
*   Milestone Four Enhanced [Files]()
*   Milestone Four Narrative [Doc]()


