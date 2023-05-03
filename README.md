# Dockerized DRF Cinema

Here you have fully dockerized project. 

# Installation
### To install Cinema API using GitHub, follow these steps:
- Install PostgreSQL and create a database.
- Clone the repository by running the following command:
`git clone https://github.com/ZabFTFT/cinema-API.git`
- Install virtual environment: 
```
python -m venv venv
venv\Scripts\activate (on Windows)
source venv/bin/activate (on macOS)
```
- Install the required packages by running:
`pip install -r requirements.txt`
- Set the required environment variables in .env 
- Apply the database migrations by running:
`python manage.py migrate`
- Start the development server by running:
` python manage.py runserver`
### If you want to run Cinema API using Docker:
1. Clone the repository and change to the cloned repository directory.
2. Build the Docker image by running:
`docker-compose up --build `

## Getting Access
To access the API, you need to create a user account and
generate access token via login.

### Features
* JWT authentication
* Admin panel 
* API documentation (swagger)
* Management of orders and tickets
* Creation of movies with genres and actors
* Creation of cinema halls
* Addition of movie sessions
* Filtering of movies and movie sessions
