# Autocomplete Exercise

This is a basic webpage for rendering autocomplete. This product utilizes frontend of VueJS and backend of Node.js.

## Getting Started

Please make sure you have at least one of package manager npm or yarn installed

### Follow the steps

1. Clone the repository
2. type the following command in your project root directory

```
npm install/ yarn install
```

Then run:

```
npm start/ yarn start
```

5. webpack development server will start at: http://localhost:3000

### Post MVP changes

This project is completed within very limited time, so aside from the fact that basic functions within user stories are done, a lot of styling and unit tests are not in place yet.

Future nice to haves would include:

- Refactor to use `bootstrap` or other library for better styled components
- Use typescript instead of javascript to avoid potential errors and ensure stronger type definitions
- Put a data processor in the node side for parsing the data
- Write unit tests for major functions, integration test for the project
- More functionality/two way activities created(such as for submit button). An arcgis map to show the pickup location as pins on map would also be nice.
- Deal with the latency of large traffic or potential errors from the GET's response
- Create reusable library for autocomplete so that others can easily import and use directly. The baseURL can be surfaced as an input parameter as well as number of row limitation and input string.
- Use heroku or firbase to deploy the code
