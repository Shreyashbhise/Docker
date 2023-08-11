# Use the official Python image as the base
FROM python:3.9-slim

# Set the working directory within the container
WORKDIR /app

# Copy the application files to the container
COPY app.py /app/
COPY templates /app/templates/

# Install any necessary dependencies
RUN pip install Flask

# Specify the command to run when the container starts
CMD ["python", "app.py"]
