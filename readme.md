docker build . -f D -t user-manager
docker run -d  --name buster -p 3000:3000 user-manager:latest

Go to http://localhost:3000/users