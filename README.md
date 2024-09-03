
## Application Description

The application will be deployed in 3-tier layers:

- Presentation layer: Kubernetes NGINX Ingress;
- Application layer: Flask application based on Docker image in Kubernetes pods;
- Data layer: MongoDB based on Docker image in Kubernetes pods.

The Flask application provides users with possibility to change colour of website background.
