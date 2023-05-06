# chat-app-frontend![React App - Google Chrome 13-04-2023 11_01_48](https://user-images.githubusercontent.com/54906865/231662972-2a04a990-fb9d-4a94-8a5c-d4f9d2777f85.png)
![React App - Google Chrome 13-04-2023 11_02_01](https://user-images.githubusercontent.com/54906865/231662994-1a81f809-5ac7-43f7-b911-4a0a7db355fb.png)
![React App - Google Chrome 13-04-2023 11_02_31](https://user-images.githubusercontent.com/54906865/231663008-92b952fb-5bfd-4886-87c9-6264865ac39c.png)
![React App - Google Chrome 13-04-2023 11_02_51](https://user-images.githubusercontent.com/54906865/231663018-cb9e38b1-d2f6-4113-8a22-16a020849cc1.png)
![React App - Google Chrome 13-04-2023 11_03_26](https://user-images.githubusercontent.com/54906865/231663021-f769d9c3-c13e-4fec-83a1-183001fc3456.png)
# How to use
You can have this application up and running with just a few steps because it has both the frontend and the backend in two repository. Follow the steps below to do so.

# Clone this repo
Once you have the repo, you need to install its dependencies. So using a terminal, move into the root directory of the project and execute npm install to install the dependencies of the Node.js server and then run npm run client-install to install the dependencies of the frontend. The second command is a custom command that I wrote to simplify the installation process.
This application uses MongoDB as its Database. So make sure you have it installed. You can find detailed guides on how to do so here. Once installed, make sure that your local MongoDB server is not protected by any kind of authentication. If there is authentication involved, make sure you edit the mongoURI in the config/keys.js file.
Finally, all you have to do is simply run npm run dev. If this command fails, try installing the package concurrently globally by running npm install -g concurrently and then running the dev command.
The frontend of the application will be automatically opened in your web browser and you can test it away.
# Things to note
The frontend is created using create-react-app
Database connections in the backend are handled using the Mongoose 

# Disclaimer
You are welcome to open issues if you find any and I will accept PR's as well.


# Author
MUSKAN



