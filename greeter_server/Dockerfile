# Use the official Selenium Standalone Chrome image as the base image
FROM python:3.10.9

# Copy the requirements.txt file into the container at the root directory
COPY requirements.txt .

# Install the Python dependencies specified in requirements.txt
RUN python3 -m pip install -r requirements.txt

# Set the working directory inside the container to /app
WORKDIR /app