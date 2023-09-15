# Use the official Python image from Docker Hub
FROM python:3.9-slim

# Set a working directory in the container
WORKDIR /app

# Copy the current directory contents into the container at /app
COPY . /app

# Install any needed packages specified in requirements.txt
RUN pip install -r requirements.txt

# Define the command to run your application
CMD ["python", "app.py"]
