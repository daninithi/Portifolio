docker build -t portfolio:latest .

docker run -d -p 4173:4173 --name portfolio portfolio:latest
http://localhost:4173