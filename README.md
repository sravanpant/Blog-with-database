# Blog-with-database
Source code for creating a blog website with mongodb local backend

## How to get started : 
1. Download the source code given above.
2. Run the commmand in the terminal
```
npm install 
```
This command will download all the packages that are required for the project from the package.json file.
3. Then run the command to start the mongodb server
``` 
sudo systemctl start mongod
```
4. Then begin using mongosh
```
mongosh
```
5. Open a new tab in your terminal and cd to the directory where you stored your downloaded files.
6. Run the following command to start the localhost server:
```
nodemon app.js
```
7. Open the browser and type the following in the address bar and hit enter:
```
https://localhost:3000
```
8. You will be able to see the blog home page.<br>
9. Go to 
```
https://localhost:3000/compose
```
<br>and you will be able to compose new blog posts and store in the local mongodb server
