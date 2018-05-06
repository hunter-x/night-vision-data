# Night Vision Data

 Night Vision Data is a web app that will mostly work with Governments data to make informations more Open and Presentable to citizens and society so that they can clearly understand what’s happening under the hood.

 * In some countries, data released by Gov exists in an unsable format PDF, Images... that's why this platform will contain 'Jailed' data section where contributors can set the data free and in return get points for doing so.
 
 * Another issue is that if we want to check data related to a foreign country specially we will find a hard time doing so that's why this app will aggregate all the trusted data related to a country and to a certain field.

 * We're also gone try Visualize the existing data in the platform dynamically. 
 
## Welcome !

Thank you so much for stopping by! We're Looking forward to collaborate with you whether you're from a technical or non technical background . Please feel free to add comments and questions.
## Contributing

Thanks for your interest in contributing to Night Vision Data! There are many ways to contribute. To get started, take a look at [CONTRIBUTING.md](CONTRIBUTING.md).

## Participation Guidelines

This project adheres to  [Mozilla Community Participation Guidelines](https://www.mozilla.org/en-US/about/governance/policies/participation/). By participating, you are expected to uphold this code.

## How to install
1. Install mongo db on your machine or proveide a link to a hosted instance
2. Open mongo db 
3. Import the data of the election lists in the database :
    * go to  `./data` and execute `mongoimport --db night-vision-data --collection lists --type json  --file  ./AllList.json --jsonArray`
4. Start the backend server (node.js) go to `./backend` and type `npm start`
5. Start the front-end (React - webpack) go to `./ frontend ` and type `npm start`
6. open the browser ` localhost:3000`


## Licence
[MIT](LICENSE)
