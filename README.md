image: docker build -t lab5 .
container: docker run -it -p 8080:8080 --rm --name vuejs-lab5 lab5