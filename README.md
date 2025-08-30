# EgalercraftXserver
EaglercraftX 1.8 Server Setup
This repository contains the necessary files to set up and run an EaglercraftX 1.8 server.

Prerequisites
Before you begin, make sure you have the following installed on your system:

Node.js and npm: You can download them from nodejs.org.

Git: Required to clone the server repository.

Java: The EaglercraftX server jar file requires a Java Runtime Environment (JRE).

How to Set Up and Run the Server
Clone this repository:

git clone [https://github.com/your-username/eaglercraftx-server-setup.git](https://github.com/your-username/eaglercraftx-server-setup.git)
cd eaglercraftx-server-setup

Run the setup script:
This script will clone the EaglercraftX server files, install dependencies, and prepare the server.

chmod +x start-eaglercraft.sh
./start-eaglercraft.sh

Start the server:
To run the server, use the npm start command in your terminal.

npm start

The server should now be running and accessible. Look for the server's URL in the terminal output.

Project Structure
package.json: Defines the project and the start script.

start-eaglercraft.sh: A shell script that automates the setup process by cloning the server source and installing dependencies.

README.md: This file, providing instructions on h
