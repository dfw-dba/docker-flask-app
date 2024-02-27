# Base python docker image
FROM python:3.9.5-buster

# Import Code
ADD . /code

# Change directory
WORKDIR /code

# Install lib
RUN pip install flask

#Expose port
EXPOSE 8080

#Running python file
CMD python main.python
