
## API Documentation courses by Peter Gruenbaum

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
