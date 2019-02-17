##Service Trial

The aim of this project was to understand services. I have created a simple python server which runs on port 8080 and prints the hostname. Since I have created a service, whenever we hit the service url using curl it will automatically assign the request to one of the 3 replicas.
curl python-server-svc:8080