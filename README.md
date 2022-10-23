<h1>Zebra Word Judge</h1> 

<h3>Project Management tool:</h3> 
https://scrabbleapp-399.atlassian.net/jira/software/projects/TF1/boards/2/roadmap?shared=&atlOrigin=eyJpIjoiNDllYTY5NjhhYmMwNDZmNzliNzY2YzM4MWVmMDM4YmYiLCJwIjoiaiJ9

<br>

<h3>Description:</h3>

Zebra Word Judge lets users check the validity of words played against a chosen lexicon during a game of scrabble, and can be enjoyed by not just those who play competitively but also by casual players.
Final Presentation link: https://docs.google.com/presentation/d/149Zw67ydC6_GvL3lUkf4wPDysPHDI1-TEyjD6o5o6HM/edit?usp=sharing
To create Zebra Word Judge in Native Windows we used Eletron with react js. Programming languages used was Javascript, HTML, and CSS.

<br>

<h3>Code Dependencies and versions:</h3>
  "dependencies": {
    "@electron/remote": "^2.0.8",
    "@fortawesome/fontawesome-svg-core": "^6.2.0",
    "@fortawesome/free-solid-svg-icons": "^6.2.0",
    "@fortawesome/react-fontawesome": "^0.2.0",
    "@svgr/webpack": "^6.5.0",
    "@testing-library/jest-dom": "^5.16.5",
    "@testing-library/react": "^13.4.0",
    "@testing-library/user-event": "^13.5.0",
    "electron": "^21.0.1",
    "react": "^18.2.0",
    "react-dom": "^18.2.0",
    "react-scripts": "5.0.1",
    "sqlite": "^4.1.2",
    "sqlite3": "^5.1.2",
    "validator": "^13.7.0",
    "web-vitals": "^2.1.4"

  "devDependencies": {
    "@babel/core": "^7.19.3",
    "@babel/preset-env": "^7.19.3",
    "@babel/preset-react": "^7.18.6",
    "babel-loader": "^8.2.5",
    "css-loader": "^6.7.1",
    "electron-builder": "^23.6.0",
    "electron-reload": "^2.0.0-alpha.1",
    "js-sha256": "^0.9.0",
    "raw-loader": "^4.0.2",
    "react-svg-loader": "^3.0.3",
    "sass": "^1.55.0",
    "sass-loader": "^13.0.2",
    "style-loader": "^3.3.1",
    "webpack": "^5.74.0",
    "webpack-cli": "^4.10.0"


<h3>Installation:</h3>
Prerequisites: Node.js, VSCode, visual studio 2019/2022, git, jdk latest version, npm, yarn + all required software to install prerequisites.
- To run the app, please make sure ZebraWordJudge-React-Electron is somewhere in documents folder.
- Open VSCode > Click File > Click open folder > select ZebraWordJudge-React-Electron folder
- In VSCode > Click terminial > click new terminal > click split terminal
- In VSCode > Write in one terminal and press enter the following line - npm install
- In VSCode > Write in one terminal and press enter the following line - yarn add @svgr/webpack
- In VSCode > Write in one terminal and press enter the following line - npm i --save @fortawesome/fontawesome-svg-core
- In VSCode > Write in one terminal and press enter the following line - npm install --save @fortawesome/free-solid-svg-icons
- In VSCode > Write in one terminal and press enter the following line - npm install --save @fortawesome/react-fontawesome
- In VSCode > open the file webpack.common.js and check if the following line has been added, if not, add it:
      {
        test: /\.svg$/,
        use: ['@svgr/webpack'],
      },
- In VSCode > Write in one terminal and press enter the following line - npm run watch (keep this running)
- In VSCode > Write in the second terminal and press enter the following line - npm start

<br>

<h3>Hosting service:</h3>
The app has not yet been deployed.

<br>

<h3>Conclusion:</h3>
In the future, we would like to improve the UI by adding more animations and making it look more aesthetic without degrading the user experience and ease of use.
We would like to acknowledge the teaching staff and our client, Dylan for their guidance and support during this project.