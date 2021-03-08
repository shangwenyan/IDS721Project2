# IDS721Project2
This project demonstrates a simple Docker container application written in Python that returns Hello + string you pass in
  
# Build image
run: docker build --tag=hello .

# Push to Docker Hub
docker push shangwen/IDS721:latest

# Pull from Docker Hub
docker pull shangwen/IDS721:latest

# Run your image
docker run -it shangwen/IDS721 python app.py --name "Big John"
