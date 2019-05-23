
# Heroku-Deploy
This is a template and tutorial for a Heroku Deploy of Angular, React or Any other SPA or static applications
## What to use for
This template can be used to serve as a tutorial or blueprint to fast deploy of applications on Heroku
## Requirements
  - Node and NPM installed on machine. To see if you have it installed, use the code under and you should see something like this:
  ```sh
$ node -v
v8.11.3
$ npm -v
6.2.0
  ```
## Using the template
  - **Paste your code on the root folder** -  This templates will only serve the application for the Heroku required configurations, so you can get the files contained in this repo and paste on your project, or vice-versa
  
  ``The **/public** folder should have and **index.html** file``
  
  - **Serving application** - To serve the application, to see if this would run corretcly on the cloud, simply go to the root folder and run the code:
  ```sh
  $ npm run start
  or
  $ node server.js
  ```
  - **And That`s it!** - The webserver will host the application on port 8080, the default port for websites!
  - ***Enjoy!!!***
## Important notes
 - Package.json : 
    - You should include the libraries used in the ``server/server.js `` right along with your applications dependencies, otherwise, the server won't run correctly.
    - Paste the scripts contained on the ``package.json`` file on yout package.json, they will be used by heroku to run the application
 - Angular.json: 
    - The only configuration it's required to be modified is the `outputPath`, to output the build on the ``server/public``path.

## Author
#### Othecos
A Web developer with experience in Angular, Sass and Back-end development
- Contact - othecos@gmail.com
- Web Portofolio - https://www.othecos.com.br
- Linkedin - https://www.linkedin.com/in/otavio-henrique-pires-costa


