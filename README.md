# Example of MySQL in Docker


## Setup
1. `pip install -r requirements.txt`
1. `docker-compose --file docker-compose-mysql.yml up` 
1. `python manage.py migrate`
1. `docker-compose --file docker-compose-mysql.yml stop` to take it down