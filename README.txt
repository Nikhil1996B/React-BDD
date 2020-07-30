var arr1 = ["Joh: Commented this!!", "Leela: Commented this!!", "Hell!!!"];
var arr2 = ["10:10:10", "11:11:11", "12:12:12"];

var result = [];

arr1.map((val, index) => result.push(`<div>${val.concat(`<p>${arr2[index]}</p><div>`)}`));

result.map(val => console.log(val));



Steps to execute to run applcation:

npm install 

npm install cucumber --save-deve -g

npm i selenium-webdriver --save -g

npm install chromedriver
Resources:


http://chromedriver.storage.googleapis.com/index.html?path=84.0.4147.30/

https://docs.proxymesh.com/article/142-using-selenium-in-the-proxy#js

https://www.npmjs.com/package/selenium-webdriver


npm install -g chromedriver --save

https://stackoverflow.com/questions/37192508/trying-to-execute-a-script-from-package-json-on-windows-throws-a-jscript-error


