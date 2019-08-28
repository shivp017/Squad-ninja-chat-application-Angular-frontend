# Squad-ninja-chat-application-Angular-frontend

#squad Ninja Chat Application

1.You will need node, NPM and angular-cli to execute the app. You can install them with:

sudo apt-get update sudo curl -sL https://deb.nodesource.com/setup_10.x | sudo bash - sudo apt-get install -y nodejs sudo npm install -g @angular/cli

2.openvidu-server and Kurento Media Server must be up and running in your development machine. The easiest way is running this Docker container which wraps both of them (you will need Docker CE):

docker run -p 4443:4443 --rm -e openvidu.secret=MY_SECRET openvidu/openvidu-server-kms:2.11.0

3.Install NPM dependencies of Angular app:

cd front/SquadNinja-call npm install

Launch the server:
ng serve --open
