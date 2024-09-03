
![Screenshot 2024-09-03 at 19 04 34](https://github.com/user-attachments/assets/a1701da8-19dc-4493-b02d-f2cb4e37feea) ![Screenshot 2024-09-03 at 19 04 50](https://github.com/user-attachments/assets/580eb690-e02b-4123-be4f-7c6b82bb4985) ![Screenshot 2024-09-03 at 19 05 04](https://github.com/user-attachments/assets/695f1bd5-3d8f-4049-9a11-f3f3a7805fda) ![Screenshot 2024-09-03 at 19 05 24](https://github.com/user-attachments/assets/25cf13dc-84c3-46f7-a9f9-9449da72123a) ![Screenshot 2024-09-03 at 19 06 17](https://github.com/user-attachments/assets/f35ea3d3-43ba-4114-8508-fb6509af8232) ![Screenshot 2024-09-03 at 19 07 19](https://github.com/user-attachments/assets/b8d5f055-7719-47d7-901c-f86b7b7f78f5) ![Screenshot 2024-09-03 at 19 07 42](https://github.com/user-attachments/assets/64583a22-c1b6-42e3-b459-d9c95002b2af) ![Screenshot 2024-09-03 at 19 07 52](https://github.com/user-attachments/assets/8772d23c-f95f-454d-957f-16d98936cf32) ![Screenshot 2024-09-03 at 19 08 45](https://github.com/user-attachments/assets/5e1a348b-f873-463d-9e8c-27e4f1e12aff) ![Screenshot 2024-09-03 at 19 09 19](https://github.com/user-attachments/assets/2dafa0c2-451a-4333-99a8-0167d9493df4) ![Screenshot 2024-09-03 at 19 09 29](https://github.com/user-attachments/assets/7a565cef-3caf-4295-b1b0-b3cc35086276) ![Screenshot 2024-09-03 at 19 09 43](https://github.com/user-attachments/assets/26854077-9177-40c6-9337-3bb3ec0ebd19) ![Screenshot 2024-09-03 at 19 10 10](https://github.com/user-attachments/assets/006d3b5b-a967-4dd6-9dee-2bf662c4d6c2) ![Screenshot 2024-09-03 at 19 04 12](https://github.com/user-attachments/assets/fbfa7567-799e-4415-b37d-0a82fa96fbc7)

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

## To Setup .env File

you must create an .env file in your project folder and save your API key or other sensetive info.

Example: REACT_APP_HOST=http://localhost:8000

REACT_APP_GUEST_LOGIN=arnob@example.com

REACT_APP_GUEST_PASSWORD=learnreact

## To Deploy on Netlify (Frontend-Deployment)

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

## To Deploy on Render (Backend-Deployment)

Visit: https://render.com/

Locally

- Create a folder ‘ebookstore-mock-server’

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
