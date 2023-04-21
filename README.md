# node-k8s

# create project directory
 mkdir node-web-app
 
 cd node-web-app
 
 # initialize project directory
 
 npm init
 
 apt install npm     // if not present
 
 # install express
 
  npm install express --save
  
  # package.json created automatically after running above command
  # make sure to make changes in this file from index.js to app.js
  and add 
  
  "scripts": {
  "test": "echo \"Error: no test specified\" && exit 1",
  
  "start": "node app.js"
}

  
  vi app.js
 
 # start app
 node app.js
 
 
 
 vi Dockerfile
 
 docker build -t nodeapp .
 
 
 
 ![Screenshot (613)](https://user-images.githubusercontent.com/109224601/233654687-c2df65e4-6748-4d37-9197-b56a8492d0e6.png)




nodejs docker image
https://www.section.io/engineering-education/building-a-nodejs-application-using-docker/

Dockerfile
![Screenshot (609)](https://user-images.githubusercontent.com/109224601/233653557-0a1e6eba-0b65-4d2f-a137-b3b460078324.png)

app.js
![Screenshot (610)](https://user-images.githubusercontent.com/109224601/233653854-13140f61-8920-4e2e-8eb9-3cb70e91ae71.png)

package.json
![Screenshot (611)](https://user-images.githubusercontent.com/109224601/233654154-159f9c90-90a8-44e1-aaa5-46f5e4a5d2f5.png)


