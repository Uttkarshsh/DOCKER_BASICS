# DOCKER BASICS

With my first project in Docker, I have started by printing "Hello, World!".

## Creating the Application File

First, we create a file named `app.py`.

## Documentation
- Docker
- Docker Desktop
- Deployment

## Steps to Deploy a Basic Application with Docker

### 1. Install Docker and Python
First, we download and install Docker Desktop and ensure that it is set up correctly.
After that, we install Python and necessary extensions.

### 2. Verify Installations
To check whether Docker and Python are installed, we run the following commands:

For Docker:
```sh
docker --version
```

For Python:
```sh
pip install streamlit
```

Once these are installed, we can proceed with building our application.

### 3. Build the Application
Run the following command to build the application:
```sh
streamlit build app.py
```

### 4. Check If the Image is Built
To verify if the image has been created successfully, run:
```sh
docker images
```

### 5. Run the Application
Finally, we run the application using Streamlit:
```sh
streamlit run app.py
```

This will launch the Streamlit web application.

Now, our basic Docker setup is complete!

