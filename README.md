# plant-store

npx create-react-app myfirstapp
cd myfirstapp
npm install web-vitals
npm start

cd /home/project
npx create-react-app myfirstapp
cd myfirstapp
npm install web-vitals
rm src/App.css src/App.test.js  src/index.css src/logo.svg src/reportWebVitals.js  src/setupTests.js
npm start

Deploy
npm install gh-pages --save-dev

Add these scripts to package.json:
"homepage": "https://yourname.github.io/myfirstapp",
"scripts": {
  "predeploy": "npm run build",
  "deploy": "gh-pages -d build"
}

Deploy:
npm run deploy

