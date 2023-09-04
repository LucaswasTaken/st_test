
# Streamlit Hello World on Cloud Run

This is a simple Streamlit "Hello World" application that can be deployed to Google Cloud Run.

## Local Development

1. Build the Docker image:  
   `docker build -t streamlit-hello-world .`

2. Run the Docker container locally:  
   `docker run -p 8080:8080 -e PORT=8080 streamlit-hello-world`

3. Open a browser and navigate to `http://localhost:8080`.

## Deployment to Cloud Run

1. Build the Docker image and push it to Google Container Registry or another container registry.

2. Deploy the container to Google Cloud Run.

## License

MIT
