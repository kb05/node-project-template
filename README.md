## node-project-template
The purpose of this project y create the skeleton of basic node project. 

The project creates a container from a image of Node (specified version in the .env file) with the debugger configured (in the dev environment).


To run the project it's necessary save a .env file with the HTTP_SERVER_PORT and the NODE_VERSION (you can copy the env.example file).

After that you can use ```docker-compose up``` in the folder of one of the environments to start the container and check the functionality.

<img src="https://raw.githubusercontent.com/kb05/node-project-template/master/images/node-project-template.gif">