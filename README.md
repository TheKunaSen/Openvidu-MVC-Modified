
# Telemedicine




## Installation

Docker Installation

```bash
 sudo apt install docker
```
Node Installation

```bash
 sudo apt install node
```
NPM installation

```bash
 sudo apt install npm
```

MongoDB installation

```bash
 sudo apt install mongodb
```
## Node packages installation
Go to the root folder of the directory where the package.json file is located then type the following command to install node packages

```bash
 npm install
```
## Starting the server

Start the docker demon by following command
```bash
sudo dockerd
```

To start the server you have to run the docker image first by following command in the root directory

```bash
sudo docker run -p 4443:4443 --rm -e OPENVIDU_SECRET=MY_SECRET openvidu/openvidu-server-kms:2.19.0
```
Starting the node server
```bash
nodemon server.js https://localhost:4443 MY_SECRET
```





  

  

  
  
## Run Locally

http://localhost:8080/



  
## Author

- [@TheKunalSen](https://github.com/TheKunaSen)

  