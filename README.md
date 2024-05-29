# Simple Notes App
This is a simple notes app built with React and Django. And the project is about deploying the code on AWS using Jenkins declarative CI/CD Pipelines.

## Tools used
1. Github
2. Docker
3. DockerHub
4. AWS EC2

## Requirements
1. Python 3.9
2. Node.js
3. React

## Installation
1. Clone the repository
```
git clone https://github.com/biswas-12/notes-app-cicd
```

2. Build the app
```
docker build -t notes-app .
```

3. Run the app
```
docker run -d -p 8000:8000 notes-app:latest
```

## Nginx

Install Nginx reverse proxy to make this application available

`sudo apt-get update`
`sudo apt install nginx`
