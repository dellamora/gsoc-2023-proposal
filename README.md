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
| June 26 - July 2 |Create schema composition and validate conditions |
| July 3 - July 9 |Map and implement the functions needed to validate user input based on the schema, and test and debug the functions|
| July 10 - July 14 |Perform an overview of the project alongside the mentor to submit the midterm evaluations  |
| July 15 - July 31 |  Write documentation and create user guides, conduct user acceptance testing and make necessary revisions   | GSoC contributors work on their project with guidance from Mentors           |
| August 1 - August 20 | Finalize the project and deploy the API, provide support for any issues or bugs that may arise and prepare for the final evaluation. | GSoC contributors work on their project with guidance from Mentors           |
| August 21 - 28  | Final week: GSoC contributors submit their final work product and their final mentor evaluation (standard coding period) |
| August 28 - September 4  | Mentors submit final GSoC contributor evaluations (standard coding period) |
| September 5          | Initial results of Google Summer of Code 2023 announced                      |
| September 4 - November 6 | GSoC contributors with extended timelines continue coding                  |
| November 6    | Final date for all GSoC contributors to submit their final work product and final evaluation |
| November 13   | Final date for mentors to submit evaluations for GSoC contributor projects with extended deadlines |




**My tech background**
=====================
## **Projects**

### [Portfolio](dellamora.dev)
Nov 2022 - Jan 2023

My portfolio website is a hub that showcases my programming articles, work experiences, and public projects and provides a clear overview of my skills. It serves as a personal hub, making it easy to find and access relevant information about me and my work, as well as how to contact me for potential job opportunities or collaborations. Whether you're seeking programming insights or looking for a new project to explore, my portfolio website has everything you need.

On the technical side, I used TypeScript, Next.js to make the site work with SSR, Framer Motion to create the animations, and React-Query to fetch my articles. 

You can read more about the development process [here](https://dev.to/dellamora/o-passo-a-passo-de-como-criei-meu-portfolio-e-como-voce-pode-fazer-o-mesmo-23kf)

### [Rick and Morty Search](https://rickandmorty-ochre.vercel.app/)

The main goal of this project was to create a simple application that would serve as a practical study for the use of TypeScript's generic types and the implementation of React Query. By using the Rick and Morty API to allow users to search for characters, episodes, and locations, this project provides a hands-on approach to learning these technologies.

ps: this was such a fun project that I even wrote an article about it in Portuguese, and who knows, maybe in the future I'll translate it to English...[read here](https://dev.to/dellamora/criei-um-hook-personalizado-para-buscar-dados-da-api-do-rick-and-morty-com-react-query-1c7f)

### [Todo App with Redux Toolkit and Zustand](https://todos-cyan-phi.vercel.app/)

This is a Todo App project developed using two different libraries: Redux Toolkit and Zustand. Both libraries were used for state management in the application, allowing users to create, mark as complete, and delete tasks.

### [DellaFlix](https://dellaflix.dellamora.dev/)

I decided to develop a project inspired by Netflix when I faced the dilemma of every programmer who is building his portoflio, which project would be fun to work on?
Dellaflix came up as the answer, since I would challenge myself both on the backend by developing a movie API and if the movie searched doesn't exist in my database, look it up in another API (The Movie Database) and on the frontend by cloning Netflix's design.

**Stack**: React • TypeScript • NextJS• TailWindCSS• Express.js • Prisma/SQL/NoSQL

## **Worked Experience**

### RCX - Frontend Developer
Feb 2023 - Present · 2 mos

**Skills**: Redux.js Toolkit · Redux.js · HTML · React.js · JavaScript · Styled-components · CSS

### Venturus - Frontend Developer
February 2021 - September 2022 (1 year 8 months)

I have had the opportunity to work on a wide range of projects and tasks.
These include developing landing pages, creating a web crawler, and
Page 1 of 2
building two progressive web applications. Additionally, I have taken on
the responsibility of **managing daily meetings, sprints, and tasks while also performing analysis on project structure and features to enhance user
experience and developer experience through refactoring. I have documented
projects** and worked closely with back-end developers and web designers to
optimize usability. Finally, I have also organized various team-building events, including programming logic competitions, coding dojos, and other activities
that promote collaboration and cohesion among team members.

 **Skills**: Redux.js · HTML · TypeScript · React.js · PWA (Progressive Web App) · JavaScript · Firebase · Styled-components · React.Konva · Material-UI · Bootstrap · Figma (Software) · Redux.Sagas

