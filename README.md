# Project Title

This project is an exmaple for an deployment app

## Getting Started

To execute this project you need to execute "npm start" and it will be running on the port 3000, another way the run this project is building a docker image, the Dockerfile includes the parameters to build the image, once builded the image, execute using the command "docker run -dti -p:80:80 (image), then open in any browser and open localhost:80. Other way to run it is just open this link: https://videoclub-wwrg1mj7.b4a.run/ 

## Prerequisites

Requirements for the software:

    NodeJS
    Docker

## Installing

- Node JS.- Just write "apt install nodejs" in the terminal en it will be installed automatically
- Docker.- 

Add Docker's official GPG key:

sudo apt-get update

sudo apt-get install ca-certificates curl gnupg

sudo install -m 0755 -d /etc/apt/keyrings
curl -fsSL https://download.docker.com/linux/ubuntu/gpg | sudo gpg --dearmor -o /etc/apt/keyrings/docker.gpg

sudo chmod a+r /etc/apt/keyrings/docker.gpg

Add the repository to Apt sources:

echo \
  "deb [arch="$(dpkg --print-architecture)" signed-by=/etc/apt/keyrings/docker.gpg] https://download.docker.com/linux/ubuntu \
  "$(. /etc/os-release && echo "$VERSION_CODENAME")" stable" | \
  sudo tee /etc/apt/sources.list.d/docker.list > /dev/null

sudo apt-get update

Install the Docker packages.

sudo apt-get install docker-ce docker-ce-cli containerd.io docker-buildx-plugin docker-compose-plugin

# Author 
    Ramón Reyna García, Student from Universidad Autónoma de Chihuahua

# License 

This project is not licensed