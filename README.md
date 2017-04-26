# Simpla2.0-Template

---
If you are just using the template project use "npm install" to download all dependencies!
---

Simpla2.0 How to start:

1.	Install npm (https://docs.npmjs.com/getting-started/installing-node)
2.	Create a directory for your project e.g „SimplaTest“
3.	Press Windows-Key + R
4.	Enter “cmd”
5.	Enter in the cmd: cd <pathtoSimplaTest>
for me it’s “C:\Users\Username\Documents\SimplaTest”
-----------------------------
THIS SECTION IS ONLY IF YOU WANT TO RUN YOUR SERVER LOCALLY!
6.	Initialize the project with “npm init” and fill out the questions
After that it looks similarly to this (if not open it in the Editor and change it. After that run “npm install”)
![Simpla1](https://cloud.eisenschmidt.family/s/M8y9MhxGoerRzWE/download)

7.	Enter “yes” to finish the setup and it should generate a package.json
-----------------------------------
8.	With “npm install bower -g” you are downloading the tool necessary to gather all elements!
9.	Now can now install packages needed for your website.
I want simpla-text and simpla-img and of course the edit function so I am typing “bower install simpla-text simpla-img simpla-admin --save”
10.	After that, you you can start coding your website with the following template: 

![Simpla2](https://cloud.eisenschmidt.family/s/mcj9Cu5dAeAq5mv/download)

<If you followed Step 6,7 then you can now run “npm start” and the website should be served to 127.0.0.1:8080>

Troubleshooting:
If your editmode (#edit) or image does not load properly delete the 'async' behind the imports of the elements! 

Source:
https://www.simpla.io/docs/guides/migrating-from-v1#install-elements  
https://www.npmjs.com/package/simpla

