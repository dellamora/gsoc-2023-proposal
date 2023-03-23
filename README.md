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


# **Functional Requirements**


### **Add default values to JSON document**
- Accept a valid JSON Schema and a JSON document as input.
- Assign a default value to a property, object, or items of an array in the JSON document if it is present but has a null or undefined value.
- Add missing properties to an object in the JSON document if a corresponding default value is specified in the JSON schema.
- Add missing items to an array in the JSON document with a default specified in the JSON schema.
- Add properties with default values specified in the JSON schema to the JSON document if they are not present in the document.
- Handle conflicts when multiple defaults are specified for the same property by using the last default specified in the JSON schema (or define a specific priority rule for handling these conflicts).
- If a property or item is missing from the JSON document and no default value is specified in the JSON schema, the utility should not add the property or item to the JSON document and should not modify the existing document in any way.
- Provide clear error messages and handle errors gracefully to minimize disruption to the user.

---
### **Remove properties not described in JSON schema**

- Accept a valid JSON Schema and a JSON document as input.
- Remove properties from an object in the JSON document if they are not described in the JSON schema.
- Remove objects in the JSON document if they are not described in the JSON schema.
- Remove an item from an array that is not described in the schema.
- Provide clear error messages and handle errors gracefully to minimize disruption to the user.

---
### **Convert form post query string to JSON using JSON Schema**


- Convert a query string from a form post to JSON using the JSON schema to determine the types for the values.
- Handle conflicts when a parameter is present in both the query string and JSON schema with different types by using the type specified in the JSON schema.
- Handle cases where the query string contains multiple values for the same property and specify which one (if any) will be used.
- Output the updated JSON document.
- Accept only valid JSON Schema and query strings from a form post (application/x-www-form-urlencoded).
- Convert string values to the appropriate types based on the schema (e.g., "1" to 1 for a number property).
- Ignore properties not described in the schema.
- Manage required properties in the JSON schema:
  - If a required property is not present in the query string, return an error.
  -  If a required property is present in the query string but has an incorrect type, return an error.
- Implement error handling:
  - If an invalid JSON schema is provided, return an error.
  - If an invalid query string is provided, return an error.
Output the converted JSON object.


# **Non-Functional Requirements**

- Implement the project using TypeScript
- Ensure compatibility with the latest version of JSON Schema
- Write well-structured and well-tested code, with tests described in JSON for ease of use by other developers
- Ensure efficiency and the ability to handle large JSON documents and schemas
- Provide clear documentation for users to easily understand how to use the utilities
- Use consistent naming conventions and code style for maintainability and readability

**Implementation**
=====================

### **Add default values to JSON document**

- Design the API interface for the utility:
  - Define the function signature for accepting a JSON Schema and JSON document
  - Determine the output format
- Develop functions to parse and validate the JSON Schema:
  - Parse and validate simple types: string, number, boolean, object, array, and null
  - Parse and validate default values for properties, objects, and items of arrays
- Develop functions to add default values to the JSON document:
  - Add default values to properties, objects, and items of arrays when they are missing or have null or undefined values
  - Handle conflicts when multiple defaults are specified for the same property (using the last default specified or a defined priority rule)
- Implement error handling:
  - Handle invalid JSON schemas and JSON documents
  - Return clear error messages for various error scenarios
- Write unit tests for each function to ensure correctness and reliability
- Write documentation and create user guides for using the utility

-----
### **Remove properties not described in JSON schema**

- Design the API interface for the utility:
  - Define the function signature for accepting a JSON Schema and JSON document
  - Determine the output format
- Develop functions to parse and validate the JSON Schema:
  - Parse and validate simple types: string, number, boolean, object, array, and null
  - Parse and validate properties
- Develop functions to remove properties, objects, and items from the JSON document not described in the JSON schema:
  - Remove properties from an object in the JSON document

---
### **Convert form post query string to JSON using JSON Schema**

- Design the API interface for the utility:
    - Define the function signature for accepting a JSON Schema and query string
    - Determine the output format
- Develop functions to parse and validate the JSON Schema:
  - Parse and validate simple types: string, number, boolean, object, array, and null
  - Parse and validate properties, including required properties and property types
- Develop functions to parse and validate the query string:
  - Parse the query string into key-value pairs
  - Validate the query string based on the JSON Schema
- Develop functions to convert query string to JSON:
  - Convert string values to appropriate types based on the schema
  - Handle conflicts and multiple values for the same property
  - Ignore properties not described in the schema
- Implement error handling:
  - Handle invalid JSON schemas and query strings
  - Return clear error messages for various error scenarios
- Write unit tests for each function to ensure correctness and reliability
- Write documentation and create user guides for using the utility

**Timeline**
=====================

| Date   | Event  |
|----------------------|------------------------------------------------------------------------------|
| February 22 - March 19| ~~Find a cool project, join the community, hand in the qualification task, and create the proposal for the GSoC.~~   |
| March 20 - April 4      | ~~Apply for the project and continue participating in the community.~~  |
| April 27      | GSoC contributor proposal rankings due from Org Admins                        |
| May 4 - 28           | Write articles for the Dev community discussing the use cases of Schema Composition, discuss my ideas on how to implement the project with the mentor, study more about the project and attend the weekly meetings of the project.| GSoC contributors get to know mentors, read documentation, get up to speed to begin working on their projects |
| May 29    - July 10          | Phase 1      |
| July 10  - July 14     | Perform a overview of the project alongside the mentor to submit the midterm evalutions        |
| July 14 - August 14  | Phase 2  | GSoC contributors work on their project with guidance from Mentors           |
| August 14 - 21  | Perform a review of code style and quality, create developer documentation, and prepare for the final evaluation. | GSoC contributors work on their project with guidance from Mentors           |
| August 21 - 28  | Final week: GSoC contributors submit their final work product and their final mentor evaluation (standard coding period) |
| August 28 - September 4  | Mentors submit final GSoC contributor evaluations (standard coding period) |
| September 5          | Initial results of Google Summer of Code 2023 announced                      |
| September 4 - November 6 | GSoC contributors with extended timelines continue coding                  |
| November 6    | Final date for all GSoC contributors to submit their final work product and final evaluation |
| November 13   | Final date for mentors to submit evaluations for GSoC contributor projects with extended deadlines |


### **Phase 1: May 29 - July 10**

- Week 1 (May 29 - June 4)
  - Define the API interfaces for all three projects
  - Design the function signatures and output formats
- Week 2 (June 5 - June 11)
  - Develop functions to parse and validate JSON Schemas for all projects
  - Start writing unit tests for JSON Schema parsing and validation functions
- Week 3 (June 12 - June 18)
  - Develop functions specific to each project (conversion, addition of default values, and removal of properties)
  - Continue writing unit tests for each function
- Week 4 (June 19 - June 25)
  - Implement error handling for all projects
  - Complete the development of all functions for each project
- Week 5 (June 26 - July 2)
  - Finalize unit tests and ensure proper code coverage
  - Perform integration testing to validate the utilities' functionality
- Week 6 (July 3 - July 10)
  - Write documentation and create user guides for all projects
  - Conduct a final review and address any remaining issues


### **Phase 2: July 14 - August 14**

- Week 1 (July 14 - July 20)
  - Refine the utilities based on feedback from Phase 1
  - Implement any additional features or improvements
- Week 2 (July 21 - July 27)
  - Perform additional testing, including edge cases, to ensure the reliability and stability of the utilities
  - Address any issues discovered during testing
- Week 3 (July 28 - August 3)
  - Optimize the code for performance and readability
  - Refactor the code as needed to improve maintainability
- Week 4 (August 4 - August 10)
  - Update documentation and user guides based on changes made during Phase 2
  - Perform a final review of the utilities, documentation, and user guides
- Week 5 (August 11 - August 14)
  - Conduct a final round of testing to ensure no new issues were introduced during optimization and refactoring
  - Package and prepare the utilities for release


**Why me**
=====================

Eu realmente amo programar e me diverto quando estou me sentindo desafiada. Acredito que estou qualificada para esse projeto,  quero desevolver ele e vou dar o meu melhor.
Eu já estou famili
