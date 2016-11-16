This is a static version of the application. All the content loaded in this application is loaded statically.
To generate an apk for the application follow the following steps:

1. Run the following commands to install dependencies for the project:
   npm install
   This will create a 'node_modules' folder and install all node related dependencies for the project in it.
   bower install
   This will create a 'bower_components' folder inside 'www' folder and install all dependencies for the project in it.
   
2. Then run the following ionic commands:
   ionic platform add android
   This command adds android platform to the project.
   
   ionic build android
   This command builds the apk for the project by wrapping the content.
   
   After the build command, the apk file can be found at the following location:
   platforms > android > build > outputs > apk > android-debug.apk
   
   Install this apk in the device to perform device testing.
