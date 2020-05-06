Steps:

1. npm install gh-pages --save-dev
2. package.json add "homepage": "https://hossain434.github.io/ghpage"
"scripts": {.. "predeploy":"npm run deploy", "deploy": "gh-pages -d build"}
3. For React-router: browserRouter change to HashRouter,
4. git init
5. git remote add origin https://github.com/hossain434/ghpage.git
6. npm run deploy
