# test-project

> A Vue.js project

## Build Setup

``` bash
#Check for Vue-CLI
Command vue --version

#If there is an error
Command: npm install -g vue-cli

#Bootstrap the Application
#Create a new app using webpack template
Com: vue init webpack test-project
(Answer all the question)

#Install Dependencies
npm install

# serve with hot reload at localhost:8080
npm run dev
 
#Modify Hello

#Added Event Handling
code: <p>What is {{ num1 }} times {{ num2 }}?<span v-if="product">{{ product }}</span></p>
<button v-on:click="calculateProduct">Calculate</button>

#creat Repository

#Configure Webpack
Change config/index.js
Changes made to paths dist to docs and set assetsPublicPath to ''

#Configure Githhub pages

For a detailed explanation on how things work, check out the [guide](http://vuejs-templates.github.io/webpack/) and [docs for vue-loader](http://vuejs.github.io/vue-loader).
