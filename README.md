# Text Editor Web App
  ![MIT-yellow License](https://img.shields.io/badge/License-MIT-yellow.svg)
  
  ## Table of Contents
  - [Description](#description)
  - [License](#license)
  - [Installation](#installation)
  - [Testing](#testing)
  - [Usage](#usage)
  - [Contributors](#contributors)
  - [Questions](#questions)

  ## Description
  Users will be able to create notes or code snippets with or without internet connection so they can use them later.

  ## License
  ![MIT-yellow License](https://img.shields.io/badge/License-MIT-yellow.svg)  
  This project is licensed under: [MIT License](https://opensource.org/licenses/MIT)  

  ## Installation
  List specific steps to help remove ambiguity and get people to use your project as quickly as possible. Let people know if it only runs in a specific context like a particular programming language version or operating system or has dependencies that have to be installed manually.  
  To install necessary dependencies, run the following command:  
  

  ## Testing
  Mention and explain all the tests that can be performed with the code examples you’ve provided.  
  To run tests, run the following command:  
  

  ## Usage
  Use this space to show useful examples of how a project can be used. Additional screenshots, code examples and demos work well in this space. You may also link to more resources.  
  

  ## Contributors
  Show your appreciation to those who have contributed to the project.  
  Also state if you are open to contributions and what your requirements are for accepting them. For people who want to make changes to your project, it's helpful to have some documentation on how to get started.  
    

  1. Fork the Project
  2. Create your Feature Branch: "git checkout - b feature / featureName"
  3. Commit your Changes: "git commit - m 'Add something featureName'"  
  4. Push to the Branch: "git push origin feature / featureName"  
  5. Open a Pull Request

  ## Questions
  To view more of my work, visit my GitHub page: [GitHub: maggiemcc](https://github.com/maggiemcc)  
  If you have any questions, please feel free to contact me by email: maggiemccausland@hotmail.com


User Story  
- AS A developer I WANT to create notes or code snippets with or without an internet connection SO THAT I can reliably retrieve them for later use  
Acceptance Criteria  
- GIVEN a text editor web application
1. WHEN I open my application in my editor
- THEN I should see a client server folder structure
2. WHEN I run `npm run start` from the root directory
- THEN I find that my application should start up the backend and serve the client
3. WHEN I run the text editor application from my terminal
- THEN I find that my JavaScript files have been bundled using webpack
4. WHEN I run my webpack plugins
- THEN I find that I have a generated HTML file, service worker, and a manifest file
5. WHEN I use next-gen JavaScript in my application
- THEN I find that the text editor still functions in the browser without errors
6. WHEN I open the text editor
- THEN I find that IndexedDB has immediately created a database storage
7. WHEN I enter content and subsequently click off of the DOM window
- THEN I find that the content in the text editor has been saved with IndexedDB
8. WHEN I reopen the text editor after closing it
- THEN I find that the content in the text editor has been retrieved from our IndexedDB
9. WHEN I click on the Install button
- THEN I download my web application as an icon on my desktop
10. WHEN I load my web application
- THEN I should have a registered service worker using workbox
11. WHEN I register a service worker
- THEN I should have my static assets pre cached upon loading along with subsequent pages and static assets
12. WHEN I deploy to Render
- THEN I should have proper build scripts for a webpack application