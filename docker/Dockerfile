# Base image
FROM python:3.11-slim

# Set working directory
WORKDIR /app

# Copy only the app files (from parent directory)
COPY my_app/ /app/

# Install Flask
RUN pip install --no-cache-dir flask

# Expose the port Flask runs on
EXPOSE 5000

# Run the app
CMD ["python", "app.py"]
