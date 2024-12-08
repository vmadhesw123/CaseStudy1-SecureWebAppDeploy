# Base Python image
FROM python:3.9-slim

# Set working directory
WORKDIR /app

# Copy application code
COPY main.py /app/

# Install dependencies (if any)
RUN pip install flask

# Expose port
EXPOSE 8080

# Start the application
CMD ["python", "main.py"]
