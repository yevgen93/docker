# init a base image (Alpine is a small Linux distro)
FROM python:3.6.1-alpine

# define the present working directory
WORKDIR /python_app

# copy the contents into the working dir
ADD . /python_app

# run pip to install the dependencies of the flask app
RUN pip install - requirements.txt

# define the command to start the container
CMD ["python","app.py"]
