# Codesplain

RTL practice project related to [React Testing Library and Jest: The Complete Guide](https://www.udemy.com/course/react-testing-library-and-jest) Udemy course by [Stephen Grider](https://www.udemy.com/user/sgslo).

Project uses NPM as a package manager. Run `npm install` to install project dependencies and `npm run start` to run the project.

There are two separates servers running: React Development server ([localhost:3000](http://localhost:3000)) and API (port 8000, should be free).

## Business Logic

Codesplain allows to do the search (e.g. search for React) over all the public repositories that are hosted on [GitHub](https://github.com). When user clicks on the repository from the list, he's taken to the code editor showing all the files and folders inside the repository. User can open any code file, highlight any code (e.g. function function expression) and click **_Explain Code_** button. User will get a popup with explanation of that code coming from code analyzing AI. The project also has some authentication stuff tied to it.
