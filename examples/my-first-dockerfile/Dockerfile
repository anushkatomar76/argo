#Base Image
FROM ubuntu:latest

# SET the working directory in the image
WORKDIR /app

#Copy the code from src to des
COPY . /app

#Install the necessary packages
RUN apt-get update && apt-get install -y python3 python3-pip

#Set environment variable
ENV NAME World

#Run a command to start the application
CMD ["python3","app.py"]
