# Excercise 1.12

## Build and run backend
#$ docker build -t backend-example .

#$ docker run --rm -it  -p 8000:8000/tcp backend-example


## Build and run frontend
$ docker build -t frontend-example .

$ docker run -it -p 5000:5000 --rm frontend-example