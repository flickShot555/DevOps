# Use an official Python runtime as a parent image
FROM python:3.8-slim

# Set the working directory in the container
WORKDIR /app

# Copy the requirements file and install Python dependencies
COPY requirements.txt requirements.txt
RUN pip install --no-cache-dir -r requirements.txt

# Copy the current directory contents into the container at /app
COPY . .

# Expose port 5000 for the Flask app
EXPOSE 5000

# Define environment variable for Flask (optional)
ENV FLASK_APP=app.py

# Run the application
CMD ["python", "src/main.py"]
