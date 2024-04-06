# Frontend/Dockerfile

# Use the official Python image from Docker Hub
FROM python:3.10.8

# Set the working directory inside the container
WORKDIR /app/frontend

# Copy the Streamlit frontend files into the container
COPY Streamlit_Frontend/ .

# Upgrade pip and install dependencies
RUN pip install --upgrade pip && pip install -r requirements.txt

# Expose the port that Streamlit runs on
EXPOSE 8501

# Specify the command to run the Streamlit app
CMD ["streamlit", "run", "Hello.py"]
