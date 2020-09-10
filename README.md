# python-okta-poc

Making a python backend to connect to React front end use Okta integration

https://developer.okta.com/blog/2018/12/20/crud-app-with-python-flask-react

# To Install

\*This app requires docker
 - git clone
 - cd into directory
 - $pip install


# To Run

 - $pipenv shell 
 >starts the virtual environment
 - $docker-compose up
 >for Mongo instance
 - $FLASK_APP=$PWD/app/http/api/endpoints.py FLASK_ENV=development pipenv run python -m flask run --port 4433