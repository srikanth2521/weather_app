This a simple weather application which display weather details of a particular city 
this application designed based on python-flask framework with weather api data  fetching from openweathemap.org site
you need to have an API key inorder to run this application
this application can be deployable in cloud using docker containers
commands to be run:
docker-compose up -d (has to exectued in docker-compose.yml folder)
which will create two images automatically and containers as well such as one for web and other for postgres database
next type docker exec -it <webcontainername> bash and then in container terminal type python tables.py inorder to create tables
now type 127.0.0.1:5002 in your browser to access your site
Note:add your database envirnoment variables such as database name and passwords etc in .env


