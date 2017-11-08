## Background
This project was created for a project in WPI CS573.  I have always been fasinated by anything to do with space, so I created a representation of sateliites orbiting the earth.  The dataset is from a real satellite database that includes all active UCS satellites in orbit.  This information was originally gathered from Celestrack.  The main task this visualization accomplishes is to visually show a user how many satellites there are in orbit, their purpose and amount owned by each country.  The visualization has the earth and satellites colored by purpose.  When a user hovers over a particular satellite, it will show the satellites name, orbit, mass, and purpose.  The user also has the ability to zoom in and rotate.  Currently their is a selector to choose a certain orbit.  This selector is not functional yet.

![image](https://user-images.githubusercontent.com/31713225/32524640-c0a4d330-c3ee-11e7-905a-0f2ade1b10a7.png)

A bar chart of countries and the number of major satellites can be found here:
https://bl.ocks.org/apratt2003/cea8be28fc370fe56343743a38e66b3b

My first prototype can be found here: https://bl.ocks.org/apratt2003/3cfd1d127d278000dcf6b78e97c65aaa

The project began with a fork of https://github.com/curran/dataviz-project-template

A template project that uses Webpack and D3. Designed as a starting point for interactive data visualization projects that require JavaScript code to be organized across many files (as ES6 modules).

The starter code here is from [Stylized Scatter Plot with Color Legend](https://bl.ocks.org/curran/ecb09f2605c7fbbadf0eeb75da5f0a6b).

## Development
This project uses NPM and Webpack. To get started, clone the repository and install dependencies like this:
```
cd dataviz-project-template
npm install
```
You'll need to build the JavaScript bundle using WebPack, using this command:
```
npm run build
```
To see the page run, you'll need to serve the site using a local HTTP server.
```
npm install -g http-server
http-server
```
Now the site should be available at localhost:8080.

For automatic refreshing during development, you can start the Webpack Dev Server like this:

```
npm run serve
```

##Deployment

To deploy your project using GitHub pages, first enable GitHub pages in the settings tab.

Each time you want to deploy a new version of the site, run the following commands:

npm run build
git add -f dist/bundle.js
git commit -m 'updated bundle'
git push

Be sure to also first install dependencies with

npm install



```
