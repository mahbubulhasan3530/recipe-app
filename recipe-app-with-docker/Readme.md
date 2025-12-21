<h1 style="color: #1bf89cff; font-size: 48px; font-weight: bold;">Docker based hosting</h1>

## Recipe Rating App
This is a three layer architecture base app. where used react as frontend. and python used as a backend and also used postgres as a database.

## Step-by-Step Deployment Guide
Prerequisite 
1. Make a directory for database on the current direcotry and the database directory name will be postgres-data
2. env change in frontend dircetory. means base on you ip address 
3. And check docker have or not.
## clone the repository 
git clone https://github.com/mahbubulhasan3530/recipe-app.git 
cd recipe-app-with-docker

## Update system and install dependencies

sudo apt update -y
sudo apt upgrade -y
sudo apt install docker.io docker-compose -y
sudo systemctl start docker
sudo systemctl enable docker
sudo usermod -aG docker $USER
newgrp docker

## docker compose up -d
