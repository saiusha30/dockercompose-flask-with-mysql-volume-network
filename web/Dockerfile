# Use official Python image
FROM python:3.9

# Set working directory
WORKDIR /app

# Copy everything into the container
COPY . /app

# Install dependencies
RUN pip install flask mysql-connector-python python-dotenv

# Expose the port the app runs on
EXPOSE 5000

# Command to run the app
CMD ["python", "app.py"]

