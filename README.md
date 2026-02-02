# MyBlog

A simple blog application designed for demonstration purposes, showcasing backend web development skills using Python and Flask. This project can be run locally using Docker Compose.


## Table of Contents

- [About the Project](#about-the-project)  
- [Built With](#built-with)  
- [Getting Started](#getting-started)  
- [Usage](#usage)  
- [Contributing](#contributing)  


## About the Project

**MyBlog** is a blog platform where users can create posts and follow others. This project demonstrates:

- Backend development with Python (Flask)  
- Database integration  
- Containerization using Docker and Docker Compose  
- Ability to quickly set up a development environment  


## Built With

- [Python](https://www.python.org/)  
- [Flask](https://flask.palletsprojects.com/)
- [SQLite](https://sqlite.org)
- [Docker](https://www.docker.com/)  
- [Docker Compose](https://docs.docker.com/compose/)  


## Getting Started

These instructions will get a copy of the project up and running on your local machine using Docker Compose.

### Prerequisites

- [Docker](https://docs.docker.com/get-docker/)  
- [Docker Compose](https://docs.docker.com/compose/install/)  

### Installation

1. Clone the repository:

```bash
git clone https://github.com/Yakovyshena/myblog.git
cd myblog
```

2. Build and start the containers:
```bash
docker-compose up --build
```

3. Access the application:
- Open your browser and go to http://localhost:8000

4. Stop and remove the containers:
```bash
docker-compose down 
```

## Usage
Once the containers are running, you can:
- Register and authenticate users
- View the blog homepage
- Create new posts
- Update user profile information
- Follow and unfollow other users
- View posts from followed users

## Contributing
Contributions are welcome! For major changes, please open an issue first to discuss what you would like to change.