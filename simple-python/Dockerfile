FROM python:3.11
WORKDIR /app

# Copy requirements.txt to the image
COPY requirements.txt .

# Install Python packages using RUN directive
RUN pip install --no-cache-dir -r requirements.txt

COPY . /app
CMD ["python", "app.py"]