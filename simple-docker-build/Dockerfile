# Build docker image using python and run a simple python script
FROM python:3.12-slim

# Set the working directory in the container
WORKDIR /app

# Copy the current directory contents into the container at /app
COPY simple_script.py /app

# Command to run the script
CMD ["python", "simple_script.py"]