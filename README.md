**Personal Information**
=====================
- Name: Francielle Dellamora Menegotto
- Email: francielle@dellamora.dev
- Github: [@dellamora](https://github.com/dellamora)
- Personal Website: [Dellamora.dev](https://www.dellamora.dev/)
- Articles: [Dev.to](https://dev.to/dellamora)
- Linkedin: [Francielle Dellamora](https://www.linkedin.com/in/francielle-dellamora-3579301a1/)
- Location: Porto Alegre, Brazil
- Time Zone: UTC-3
- University: University of Vale do Rio dos Sinos
- Bachelor degree: Computer Science 

**About me**
=====================
I'm a full-stack developer with a passion for making a positive impact through web development. 

My love for computers began at a young age, where I taught myself HTML and CSS to create themes on the Tumblr platform. This experience solidified my decision to pursue a career in web development, where I can combine my passion for technology with my desire to make a positive impact in the community. 

To achieve this goal, I'm particularly passionate about sharing my personal experiences, writing technical content, and working in Open Source. Because of this, I'm actively involved in the Brazilian tech community and am excited to reach more people by creating content in English. 
I’ve been working in the software development industry for over two years, where I've gained valuable experience in finding efficient and innovative solutions to overcome challenges.

At this moment in my career I’m focusing on building projects using TypeScript, Next.js, React, Tailwind CSS, Prisma/SQL/NoSQL, Express.js, and whenever I discover a new and interesting technology to add to my stack, I enjoy writing articles about it.


**Project Description**
=====================
- Name: [Data Transformation Utilities Using JSON Schemas](https://github.com/postman-open-technologies/gsoc-2023/issues/16)
- Mentor: [@jdesrosiers](https://github.com/jdesrosiers)
- Description: This project aims to provide a set of transformation utilities that utilize the information in a JSON Schema beyond validation. The utilities to be implemented include adding missing values with a default specified in the JSON Schema, removing properties in a JSON document that are not described in the JSON Schema, and converting a query string from a form post to JSON using the JSON Schema to determine the types of the values. The goal is to implement these utilities in any language and ensure compatibility with at least the latest version of JSON Schema. Additionally, the project intends to provide test cases in JSON format to enable others to use them when writing similar tools in different languages. By doing so, the project hopes to contribute to the JSON Schema community and provide valuable resources for developers working with JSON Schema.

**Requirements**
=====================

| Functional | Non-Functional|
| ------------- | ------------- |
|Should be able to accept a valid JSON Schema and a JSON document as input.|Should be implemented using TypeScript.|
|Should add missing values to the JSON document with a default specified in the JSON Schema.|Should work with the latest version of JSON Schema.|
|Should remove properties from the JSON document that are not described in the JSON Schema.|Should be well-tested, with tests written in JSON.|
|Should be able to accept a query string from a form post and convert it to JSON using the JSON Schema to know the types for the values.|Should be efficient and able to handle large JSON documents and schemas.|
||Should be easy to use.|
||Should Have clear documentation.|


**Implementation**
=====================
  
- Create the API interface so that I can have a clearer understanding of what is needed:
  - How the JSON Schema is integrated
  - How the data will be treated and validated
  - What the output will be
- Map all the functions needed to validate whether the JSON follows the JSON Schema standard:
  - Map the simple validations: string, number, boolean, object, array, and null
  - Map properties
  - Map more complex validations, such as objects and arrays
  - Create schema composition
  - Validate conditions
- Map all the functions needed to validate if the user input is valid based on the schema:
  - Validate simple types
  - Validate values based on properties (min: 10 max:20 value: 15 true)
  - Validate conditional values.
- Write documentation and create user guides

**Timeline**
=====================

| Date   | Event  |
|----------------------|------------------------------------------------------------------------------|
| February 22 - March 19| ~~Find a cool project, join the community, hand in the qualification task, and create the proposal for the GSoC.~~   |
| March 20 - April 4      | ~~Apply for the project and continue participating in the community.~~  |
| April 27      | GSoC contributor proposal rankings due from Org Admins                        |
| May 4 - 14           | Research and study the project, read documentation, and attend weekly meetings |
| May 15 - 21       | Write articles for the Dev community discussing Schema Composition |
| May 22 - 28          | Discuss project implementation ideas with mentor, and attend weekly meetings|
| May 29    - June 4 | Create a basic API interface and integrate the JSON Schema |
| June 5 - 11  | Map and implement the functions needed to validate simple data types |
| June 12 - June 18| Map and implement the functions needed to validate properties |
| June 19 - June 25 |Map and implement the functions needed to validate more complex data types (objects and arrays) |
| July 3 - July 9 |Create schema composition and validate conditions |
| July 10 - July 14 |Perform an overview of the project alongside the mentor to submit the midterm evaluations|
| July 15 - July 31 | Map and implement the functions needed to validate user input based on the schema, and test and debug the functions |
| July 10  - July 14     | Perform a overview of the project alongside the mentor to submit the midterm evalutions        |
| July 15 - August 14  |  Write documentation and create user guides, conduct user acceptance testing and make necessary revisions   | GSoC contributors work on their project with guidance from Mentors           |
| August 14 - 21  | Finalize the project and deploy the API, provide support for any issues or bugs that may arise and prepare for the final evaluation. | GSoC contributors work on their project with guidance from Mentors           |
| August 21 - 28  | Final week: GSoC contributors submit their final work product and their final mentor evaluation (standard coding period) |
| August 28 - September 4  | Mentors submit final GSoC contributor evaluations (standard coding period) |
| September 5          | Initial results of Google Summer of Code 2023 announced                      |
| September 4 - November 6 | GSoC contributors with extended timelines continue coding                  |
| November 6    | Final date for all GSoC contributors to submit their final work product and final evaluation |
| November 13   | Final date for mentors to submit evaluations for GSoC contributor projects with extended deadlines |




**Why me**
=====================



