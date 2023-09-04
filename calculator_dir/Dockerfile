# Use the official Python image as the base image
FROM python:3.8-slim

# Set the working directory inside the container
WORKDIR /calculator

# Copy the Python script and XML file to the container
COPY calculator.py /calculator

# Run the Python script when the container starts
ENTRYPOINT ["python", "calculator.py"]
