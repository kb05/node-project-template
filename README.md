## node-project-template
The purpose of this project is to create a skeleton of a basic node project. 

The project creates a container from a node image (specified version in the .env file) with the debugger configured (in the dev environment).

To run the project is necessary to create a .env file with the HTTP_SERVER_PORT and the NODE_VERSION (you can use the env.example file as an example).

After that, you can use ```docker-compose up``` in the folder of one of the environments to start the container and check the functionality.

<img src="https://raw.githubusercontent.com/kb05/node-project-template/master/images/node-project-template.gif">
