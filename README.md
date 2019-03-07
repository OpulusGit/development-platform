# The development environment #

##### Students : #####
- MILLET Eliot
- SAUTEREAU Tom

## Purpose of this repository ##
This project is made for an educative purpose only.<br/>
The main compenents of the development platform are :
- Mattermost : for communications between developpers
- GitHub : to develop every applications
- Trello : to work with the agile style
- Zapier : to make connections between the three previous components

## In this repository... ##
In this repository stands the mattermost private server deployment.<br/>
Developped with the docker technology, this platform allows the
developpers to communicate in a private location.<br/>

## How to start Mattermost ##
The easiest way to start the mattermost server is to use the following command :
```bash
  # Go the the repository root directory
  cd the/path/to/the/root/repository/folder
  # To build the server image
  docker-compose build
  # To run the server
  docker-compose up
```
However, to go achieve to do that, you have to install these followings technologies :
- Docker CE
- Docker compose
To install docker CE, just go on :
- For Windows : https://docs.docker.com/docker-for-windows/install/
- For Mac OS : https://docs.docker.com/docker-for-mac/install/
- For Linux (Ubuntu) : https://docs.docker.com/install/linux/docker-ce/ubuntu/

To install docker-compose, just go on : https://docs.docker.com/compose/install/<br/>

## Open the mattermost interface ##
To go on the mattermost web application, you have to connect to <strong>localhost:8065</strong><br/>
During the first connection, the server will ask you to enter to create the first mattermost account.
