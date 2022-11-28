## Upplabs

An application for listing TV series, using the API provided by the TVMaze website.

## Overview
The app was built using React Native and Typescript and the APIs were provided by TVMaze.

## Setup

### Cloning The App Repo

The app was built using expo. And it is expo managed. To clone and run the app, one doesn't necessarily need to have Expo environment setup. run 'npx expo start' in your terminal after all the dependencies have been installed.


Before cloning the app, specify the directory/folder to clone the app to with the command line prompt.

For example, to clone into the Desktop folder, enter the command below into your command line.

>$ cd Desktop

##

To clone the application, copy and paste any of the commands below to your machine command line, according to your git setup, then press enter

#### If your Git is setup for:

##### HTTPS

>$ git clone https://github.com/codefreak13/upplabs.git

##### SSH

>$ git clone git@github.com:codefreak13/upplabs.git
##

### Running The App
After cloning the app, open the app folder with your favourite IDE or code editor and install node modules with the command below


>$ yarn install
##

All is set!
You can now build the app by running the following command on your IDE terminal

>$ npx expo start

This will provide a list of options on what platform to run the app. › Press a │ open Android
› Press i │ open iOS simulator. This command will also spin up the simulator or emulator and run the app. Ensure that your android directory is properly setup on your PC.


## Improvements
- Currently, with the way the app was built, if data has to change in the app, a new version has to be built which is not ideal. The ideal solution would be to move data to the backend and make API calls for data, in order to make flow of data dynamic.