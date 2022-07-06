# Technical writing for software and API documentation : learning journal

   ## Table of contents

- [What this journal is about](#What-this-journal-is-about) </br>
- [How I chose the courses presented in this document](How-I-chose-the-courses-presented-in-this-document)</br>
- [Documentation as code VS DITA & other methods](Documentation-as-code-VS-DITA-&-other-methods)</br>
- [**Course 1 : How to build a DITA XML technical writing portfolio**](#Course-1-How-to-build-a-DITA-XML-technical-writing-portfolio)</br>
                  - [Getting setup with Github and Oxygen XML Author](#Getting-setup-with-Github-and-Oxygen-XML-Author)</br>
                  - [The workflow steps](#The-workflow-steps)</br>
                  - [Creating a DITA map with Oxygen XML Author](#Creating-a-DITA-map-with-Oxygen-XML-Author)</br>
                  - [Designing your content](#Designing-your-content)</br>
                  - [Generate a PDF file and HTML 5 content](#Generate-a-PDF-file-and-HTML-5-content)</br>
                  - [Additionnal DITA tutorials](#Additionnal-DITA-tutorials)</br>
- [**Course 2 : the art of API Documentation**](#Course-2-the-art-of-API-Documentation)</br>

 ## What this journal is about

Hello ! My name is [Anne-Laure Freant](https://www.linkedin.com/in/annelaurefreant/) and I am a content specialist with 10 years of experience in the field of tech 
(in Canada and in France) where I worked for either startups or state-level public institutions on digital products. I used to conduct editorial projects (blogs, SEO, UX writing) as well as translations of technical content (english to french, french to english) and data or code curation (reading and checking JSON files, completing metadata, etc.). So I already have a good set of skills in the field of tech, content and technical writing, and I got into the process of obtaining a technical writing certification in 2022 so to shift my career towards technical writing full time. 
**My goal is to specialize in software, web apps and API documentation.** I share on this document my notes from the various courses I took to improve my technical writing skills as well as getting a technical writing certification. 

## How I chose the courses presented in this document

As I was looking for online courses and certifications to improve my technical writing skills, I read several articles ranking the "best technical writing certifications" ( [1](https://www.squibler.io/blog/technical-writing-certification/), [2](https://productmanagerhq.com/technical-writing-certification/) ,[3](https://www.thecareerproject.org/blog/best-technical-writing-courses/)). </br>

Udemy might not the best place to start if you are looking for a full certificate or a complete training, but it is perfect to acquire some specific skills, assess your level and see more precisely what other trainings you might need according to your background and goals. It is a good way to test your interest for a very reasonable price before considering investing in a more expensive, longer certification.

As I already have a background in digital writing and technical content curation, I decided to start with a few Udemy courses that are relatively fast to complete (within a few days) but very specific to technical writing as well as based on real exercices. I then decided to go for the [Technical writing certification from HQ](https://technicalwriterhq.com/technical-writing-certification/) for a complete training and official certification.

## Documentation as code VS DITA & other methods

There is, in the last years, a cultural shift happening from the DITA standard (structured content with XML) tools and methods to "documentation as code" workflows. The two cultures coexist but seem to be evolving in different professionnal worlds that don't overlap or meet very often.
Most big corporation, especially in the trade & industry business, are used to work with DITA and XML structured content tools (Oxygen XML for instance) to manage heavy documentations to be exported in PDF for prints or as HTML files to publish online, for instance.</br>
Most tech companies, especially API based companies, have adopted "documentation as code" workflows, mainly because developers are often themselves the documentation editors and are used to work with Github, markdown or HTML files as well as static sites and a more open source, collaborative approach. It is also implied that the documentation needs to be online eventually to be usefull to other developers, so it is from the beginning designed as such. </br>
Both methods and tools are interesting to learn, it all depends on what you are interested in. </br>
My project is definitely more on the "documentation as code" culture but I took a course on DITA and XML to gain basic knowledge.
</br>

## [Course 1 : How to Build a DITA XML Technical Writing Portfolio](https://www.udemy.com/course/how-to-build-a-dita-xml-technical-writing-portfolio)

This course can be found [here](https://www.udemy.com/course/how-to-build-a-dita-xml-technical-writing-portfolio).
Below are my notes following the lesson step by step.

   ### Getting setup with Github and Oxygen XML Author

- Download and install Oxygen XML Author from [the Oxygen XML website](https://www.oxygenxml.com/xml_author/download_oxygenxml_author.html) using the trial licence key that is available for 30 days
- To showcase your technical skills and ability to work with developers, it is a good thing to build a DITA XML documentation portfolio and to have it available on a public Github repository. To do so,  you would have to create an account (if you don't have one already) on Github. If you already have a Github account, you can  [create a new public repository](https://docs.github.com/en/repositories/creating-and-managing-repositories/creating-a-new-repository) right away.

  ### The workflow steps

- CONCEPTION : What are the main features of the app or the software I am writing the documentation of ? We start by making a simple list of main functions.
- WRITING : Write the content with DITA XML
- PRODUCTION : Generate a PDF file and HTML5 content from the DITA source
- PUBLICATION : Share the content with the end user

  ### Creating a DITA map with Oxygen XML Author

DITA means Darwin Information Typing Architecture. 
DITA is a Component Content Management System (CCMS).

> "A content model is an architectural framework for a collection of content, representing the structure of the data to be stored. In a structured authoring sense, a content model is a high level plan of the types of information and an appropriate structure for its storage. For example, the content model for a Frequently Asked Question (FAQ) of a manual might describe a hierarchy of topics, broken down into title, question, background, and answer.
When we design an information architecture for storing information (or a structure to suit our documentation), we are creating a content (or information) model.
Top-level elements in DITA content models are topic types (or information types). A typical procedure manual may include procedure, explanation, glossary and error message information types. DITA's base content model (that is, the standard, default DITA model) defines three information types: **concept, task and reference**. These three types all inherit characteristics of a proto information type, simply named topic. The following diagram shows the basic information types."

Visit the [DITA Style Guide by Oxygen XML](https://www.oxygenxml.com/dita/styleguide/webhelp-feedback/#Artefact/Topics_and_Information_Types/c_Content_Models_and_Info_Types.html) for a complete set of definitions and best practices.

Once Oxygen XML is open :
- Create a DITA map by clicking on "file", then "new", then by selecting "DITA map" and by naming your new file with a relevant name
- Create a dedicated folder for your work on the desktop of your computer and make sure all files created in this exercice are included in it
- Create  topic heads elements within this map by right clicking on our new map title, then "append child", then "Topic head"
- Save your work (Crtl S)

  ### Designing your content 

Content in DITA can be divided into 4 categories : 
- **topics (general descriptions)** </br>
    - **concepts** (specific thing to know about a topic), </br>
    - **tasks** (step by step, how to),</br>
    - **references** (norms, tables, index...).</br>

Each page of the documentation should help the users address one specific question. People tend to search on search engines with by questions, such as "how to group items in Illustrators". The basic template to follow is :
- **Question** :  "How to create a clipping mask in Adobe Illustrator ?"
- **Answer** : Follow the steps indicated to create a clipping mask in Adobe Illustrator
- **Definition** : A clipping mask is an object whose shape masks other artwork so that only areas that lie within the shape are visible—in effect, clipping the artwork to the shape of the mask. It is a useful way of creating the look of "cropping" an image without having to move into Illustrator to create a true crop.
- **Prerequisite** : To sucessfully create a skimming mask, you must know how to create shapes and import images to Adobe Illustrator.
- **Steps** :
      - 1 : import one image to Illustrator
      - 2 : on the same layer, draw a shape (either a circle, rectangle or hand-draw shape with the pencil tool) that will be the contour of the skimming mask
      - 3 : select both the image and the shape by either clicking on both while maintaining "shift" or by dragging the mouse over 
      - 4 : do a right click, select "create a skimming mask" in the menu
- **Result** : the skimming mask is created

   
   ### Generate a PDF file and HTML 5 content
   
To export our DITA content, we must :
- select the DITA map in Oxygen
- click on the "Configure transformation scenario" icon
- choose HTML5 and PDF in the list of output formats
- click on "apply"

To improve the apparence of the content output, CSS would be required. At this stage, we focus only on the content.
Publishing the content must be done **only when the customer has approved the publication** to be shared with the end users.

The PDF file can be added to our Github Repository along with DITA XML files and the HTML file by adding https://htmlpreview.github.io/? before the file link so the end user can actually read the content.


   ### Additionnal DITA tutorials

- Webinar : [What is DITA (53 minutes)](https://www.youtube.com/watch?v=UGiV7evB8Ig&ab_channel=Heretto)
- The website for [DobBook XML standard](https://docbook.org/)
- Learning DITA free courses on [LearningDITA.com](https://learningdita.com/available-courses/)



## Course 2 : the art of API Documentation

This course can be found on Udemy [here](https://www.udemy.com/course/the-art-of-api-documentation/learn/lecture/4207186#overview). It is given by Peter Gruenbaum, President, SDK Bridge. It is the 3 out of 3 courses about API documentation.
See also, intro video : ["What is a REST API ?"](https://www.youtube.com/watch?v=lsMQRaeKNDk&ab_channel=IBMTechnology)

### Introduction

API stands for Application Programming Interface. API defines how 2 pieces of software communicate with each other.
There are several types of API : the 2 most common are Web API (REST) and platform API.
API documentation are for developers. Good quality documentation will improve developers autonomy. 
Writers bring an important 

API documentation can be divided in 2 parts :
- conceptual : high level info such as 
      - an overview
          - explain why to use the API
          - requirements
          - key concepts
          - workflow (order of steps to do common tasks)
          - visual information (models diagrams)
          - a "getting started section"
              - For Web API : lead people through a simple task
                  - registration
                  - get an app key
                  - authorization
                  - making one or two http request that return a response
              - For Platform API :
                  - downloading the SDK (software development kit)
                  - setting up your Integrated Development environment (IDE)
                  - doing something simple
      - tutorials
           - step by step instructions, should start with simple tasks and gradually become more complex
           - sample code covers common tasks (lots of comments in them to explain how the code works)
           - sample code is different from production code
      - sample code
- reference : http request and references (methods, classes...)

#### Material of API documentation

The overview needs to explain the "why" and not just the "how".
Its important because developers need to know :
- what does the API do
- what does it require
- is it well designed ?
They need to know if this API can solve their problem or not.

- Explaining the why : describe key features, provide a few use cases
- Provide the list of requirements (might not be needed for web API)
- for Platforms API : what operating system, what language, what versions ?

For each concept, write a paragraph or two.
Workflow diagrams and architecture diagrams might help for visual persons within the overview section (explaining how the different pieces fit together).

### Tools for API documentation

- Postman : [https://www.postman.com/](https://www.postman.com/) is an app that allows you to make requests and see responses through a visual client.


