
## eBookStore-ReactWebsite

eBookStore is a full-fledged React E-Commerce Web Application (Global Level State Application) where you can place an order for codebooks. Frontend (deployed on Netlify) and Backend (deployed on Render) are separately developed here. Filter Properties, Search Option,  JSON-Server,  JSON-Server-Auth (User Login, Logout), JSON Web Tokens (JWT), Protected Routes, React-Toastify, Session Storage, Dark Mode Option, JSON API - Auth Service and Data Service, Log in as Guest, React Core, Hooks, TailwindCSS, Responsive Screen, Context, and Reducers have been used in this project.

**Frontend webpage can be seen by using this URL:** https://ebookstore-arnob.netlify.app

**Backend webpage can be seen by using this URL:** https://codebook-mock-server-j8n3.onrender.com

(To view the Backend Source Folder, Visit: https://github.com/arnobt78/eBookStore-Mock-Server )

## To Install Dependences

Before launching this web application, be sure to install all required dependencies, which are listed in the package.json file.

To install all dependences, run this command from your project folder: `npm install`

## To Install NodeJS

Make sure you have NodeJS installed in your machine first, The installation instructions are here: https://nodejs.org/en/

## To Install React-Router 

Open up your terminal and bootstrap a new React app by: `npx create-react-app`

Then go to that project folder, and write this command via terminal from your project folder: `npm i react-router-dom`

(For more details, visit: https://reactrouter.com/en/main and https://www.npmjs.com/package/react-router-dom )

## To Install json-server-npm and json-server-auth-npm

Open up your terminal from your project folder and run: `npm install -D json-server json-server-auth`

To run json-server: `npx json-server data/db.json`

With Restricted Route and run from different Port from another terminal: `npm json-server data/db.json -m ./node_modules/json-server-auth -r data/routes.json --port 8000`

(You must open a second terminal to run the json-server and json-server-auth via different Port number because the React app is already running on Port: 3000 on your localhost)

(For more details, visit:  https://www.npmjs.com/package/json-server and https://www.npmjs.com/package/json-server-auth )

## To Integrate JSON Web Tokens (JWT) for the Login in your Project

Visit: https://jwt.io/#debugger-io

## About Netlify (Frontend-Deployment)

Visit: https://app.netlify.com/

- Login using GitHub

- Click on ‘Import from Git’

- **Connect to Git provider > Github**

- If the desired repository is not shown, click on ‘Configure the Netlify app on GitHub’

- Repository Access > All Repository

- Select the repository

- Click on ‘Deploy site’

**Note:** Deploying Process will take 2-5 minutes to be active on Netlify.

**Error:** Check the log if you get an error > apply changes to the codebase > push them on ‘main’ branch.

To set Environment Variable:

- **Site settings > Build & deploy > Environment > Environment variables**

https://docs.netlify.com/configure-builds/environment-variables/

(Make sure to push new changes after setting env to make them effective)

To change domain name:

- Change domain name on Netlify through ‘Site Settings’

404 Page Not Found Error:

- https://stackoverflow.com/questions/58065603/netlify-renders-404-on-page-refresh-using-react-and-react-router

- https://www.netlify.com/blog/2019/01/16/redirect-rules-for-all-how-to-configure-redirects-for-your-static-site/

## About Render (Backend-Deployment)

Visit: https://render.com/

Locally

- Create a folder ‘codebook-mock-server’

- npm init

- Install express, json-server, json-server-auth

- Create index.js, add ‘data’ folder and .gitignore

- Push to Github

On Render, 

- Click on ‘New’ > ‘Web Service’

- Select the Git Repository and deploy 

Note: Deploying Process will take 10-15 minutes to be active on Render.

Error: Check the log if you get an error > apply changes to the codebase > push them on ‘main’ branch.


## Available Scripts

In the project directory, you can run:

### `npm start`

Runs the app in the development mode.\
Open [http://localhost:3000](http://localhost:3000) to view it in your browser.

The page will reload when you make changes.\
You may also see any lint errors in the console.

### `npm test`

Launches the test runner in the interactive watch mode.\
See the section about [running tests](https://facebook.github.io/create-react-app/docs/running-tests) for more information.

### `npm run build`

Builds the app for production to the `build` folder.\
It correctly bundles React in production mode and optimizes the build for the best performance.

The build is minified and the filenames include the hashes.\
Your app is ready to be deployed!

See the section about [deployment](https://facebook.github.io/create-react-app/docs/deployment) for more information.

### `npm run eject`

**Note: this is a one-way operation. Once you `eject`, you can't go back!**

If you aren't satisfied with the build tool and configuration choices, you can `eject` at any time. This command will remove the single build dependency from your project.

Instead, it will copy all the configuration files and the transitive dependencies (webpack, Babel, ESLint, etc) right into your project so you have full control over them. All of the commands except `eject` will still work, but they will point to the copied scripts so you can tweak them. At this point you're on your own.

You don't have to ever use `eject`. The curated feature set is suitable for small and middle deployments, and you shouldn't feel obligated to use this feature. However we understand that this tool wouldn't be useful if you couldn't customize it when you are ready for it.

## Learn More

You can learn more in the [Create React App documentation](https://facebook.github.io/create-react-app/docs/getting-started).

To learn React, check out the [React documentation](https://reactjs.org/).

### Code Splitting

This section has moved here: [https://facebook.github.io/create-react-app/docs/code-splitting](https://facebook.github.io/create-react-app/docs/code-splitting)

### Analyzing the Bundle Size

This section has moved here: [https://facebook.github.io/create-react-app/docs/analyzing-the-bundle-size](https://facebook.github.io/create-react-app/docs/analyzing-the-bundle-size)

### Making a Progressive Web App

This section has moved here: [https://facebook.github.io/create-react-app/docs/making-a-progressive-web-app](https://facebook.github.io/create-react-app/docs/making-a-progressive-web-app)

### Advanced Configuration

This section has moved here: [https://facebook.github.io/create-react-app/docs/advanced-configuration](https://facebook.github.io/create-react-app/docs/advanced-configuration)

### Deployment

This section has moved here: [https://facebook.github.io/create-react-app/docs/deployment](https://facebook.github.io/create-react-app/docs/deployment)

### `npm run build` fails to minify

This section has moved here: [https://facebook.github.io/create-react-app/docs/troubleshooting#npm-run-build-fails-to-minify](https://facebook.github.io/create-react-app/docs/troubleshooting#npm-run-build-fails-to-minify)
