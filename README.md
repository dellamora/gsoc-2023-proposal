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
Hello, I'm a full-stack developer with a passion for creating web projects that positively impact people's lives. I've been working in the software development industry for over two years, where I've sought out efficiency and smart solutions to overcome challenges.

My love for computers began when I was young, and I taught myself HTML and CSS to create themes on the Tumblr platform. This experience solidified my decision to pursue a career in web development, where I could combine my passion for technology with my desire to create positive change.

Beyond my work, I'm actively involved in the Brazilian tech community and am eager to expand my reach by creating content in English. I'm particularly passionate about creating programming content and sharing my knowledge with others. Ultimately, my goal is to be a role model for women in the industry and inspire others to pursue their passions in tech.

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

- Criar a API (interface da api) pra eu conseguir ter uma noção mais clara do que vai perciso 
  -  como que entra o JSON Schema
  -  como que os dadaos vao ser tratados e validados 
  -  como que vai ser o ouput 
- Mapear todas as funções que vamos precisar criar para validar se o JSON segue o padrão JSON Schema 
  - mapear as validações simples: string, number, boolean.... ir na doc confirmar 
  - mapear propriedades como min, max etc....
  - mapear as validações mais complexas como object and arrays
  - create schema composition
  - validar condições
- Mapear todas as funções para validar se o input do usuário é valido baseado schema    
  - validação simples baseada no tipo
  - validação do valor conforme as propriedades (min: 10 max:20 valor:15 true)
  - validação de valores condicionais 
  



**Timeline**
=====================

| Date   | Event  |
|----------------------|------------------------------------------------------------------------------|
| February 22 - March 19| ~~Find a cool project, join the community, hand in the qualification task, and create the proposal for the GSoC.~~   |
| March 20 - April 4      | ~~Apply for the project and continue participating in the community.~~  |
| April 27      | GSoC contributor proposal rankings due from Org Admins                        |
| May 4 - 28           | Write articles for the Dev community discussing the use cases of Schema Composition, discuss my ideas on how to implement the project with the mentor, study more about the project and attend the weekly meetings of the project.| GSoC contributors get to know mentors, read documentation, get up to speed to begin working on their projects |
| May 29    - July 10          | NAO ESQUECER DE PERSONALIZAR!                                       |
| July 10  - July 14     | Perform a overview of the project alongside the mentor to submit the midterm evalutions        |
| July 14 - August 14  | Work Period  | GSoC contributors work on their project with guidance from Mentors           |
| August 14 - 21  | Perform a review of code style and quality, create developer documentation, and prepare for the final evaluation. | GSoC contributors work on their project with guidance from Mentors           |
| August 21 - 28  | Final week: GSoC contributors submit their final work product and their final mentor evaluation (standard coding period) |
| August 28 - September 4  | Mentors submit final GSoC contributor evaluations (standard coding period) |
| September 5          | Initial results of Google Summer of Code 2023 announced                      |
| September 4 - November 6 | GSoC contributors with extended timelines continue coding                  |
| November 6    | Final date for all GSoC contributors to submit their final work product and final evaluation |
| November 13   | Final date for mentors to submit evaluations for GSoC contributor projects with extended deadlines |

**Why me**
=====================
