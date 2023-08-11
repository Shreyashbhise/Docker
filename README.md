Open a terminal and navigate to the directory containing app.py, Dockerfile, and requirements.txt.

Build the Docker image using the following command:

bash

docker build -t simple-flask-app .

Once the image is built, run a container based on the image using the following command:

bash

docker run -p 8080:8080 simple-flask-app

Open a web browser and navigate to http://localhost:8080 to see the rendered template with the dynamic content.

![image](https://github.com/Shreyashbhise/Docker/assets/108046802/86338846-f95a-4cee-b8a7-513747e9969b)
