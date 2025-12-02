# syntax=docker/dockerfile:1
FROM squidfunk/mkdocs-material:latest

# Copy only requirements so docker build can cache better
COPY requirements.txt .

# Install additional Python packages (floating versions as requested)
RUN pip install --no-cache-dir -r requirements.txt

WORKDIR /docs

EXPOSE 8000
