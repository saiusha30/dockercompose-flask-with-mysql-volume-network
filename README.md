# Flask + MySQL with Docker compose

This project demonstrates how to run a simple Flask web application with a MySQL database using Docker Compose. 
It also uses Docker volumes to persist MySQL data and Docker networks for container communication.

## 🚀 What This Project Does

- Runs a Python Flask web app in a Docker container
- Connects the app to a MySQL database container
- Stores MySQL data using Docker volumes
- using customized docker network for conncting continers morre securly
- Manages environment variables using a `.env` file

##  Project Folder Structure
my-dockercompose-project/
├── .env
├── docker-compose.yml
├── .gitignore
├── README.md
└── web/
    ├── app.py
    └── Dockerfile
## pre installed

docker,
git,
docker compose


## How to Run

1. Clone the project:

```bash
https://github.com/saiusha30/dockercompose-flask-with-mysql-volume-network.git
cd my-dockercompose-project

2. Create all required files mentioned in the project folder structure
3. Edit .env and fill in your own values.(here not providing any .env template)
4. Build and run the containers

docker-compose up --build

5.Open the app in your browser

with public-ip address with 5000(portnumber)


you should see like this

Connected to MySQL! Tables: []

5. To stop and remove containers, networks, and volumes:

docker-compose down -v


About the Author
saiusha30





