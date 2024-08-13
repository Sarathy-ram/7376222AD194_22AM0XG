# Use the official Python base image
FROM python:3.9-slim

# Set the working directory
WORKDIR /app

# Install dependencies directly
RUN pip install --no-cache-dir scikit-learn joblib

# Copy the Python script into the container
COPY app.py /app/app.py

# Run the Python script
CMD ["python", "app.py"]
