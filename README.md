#!/bin/bash

# This script automates the setup process for an EaglercraftX 1.8 server.
# It clones the necessary repositories and prepares the server for launch.

# Clone the EaglercraftX server repository.
# You can replace this URL with the specific server repository you want to use.
echo "Cloning EaglercraftX-Server repository..."
git clone [https://github.com/EaglercraftX/EaglercraftX-Server.git](https://github.com/EaglercraftX/EaglercraftX-Server.git)
cd EaglercraftX-Server

# Install any required npm dependencies.
echo "Installing dependencies..."
npm install

echo "Setup is complete. You can now start the server with the 'npm start' command."
