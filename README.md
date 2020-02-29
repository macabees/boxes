# Boxes
## The Boxes command draws a box around its input text. 

## Boxes (Project Info)
[Website](https://boxes.thomasjensen.com/)

## Docker Hub
[Website](https://hub.docker.com/r/macabees/boxes/)

## Build image
`$ docker build -t macabees/boxes:latest .`

## Run image
`$ docker run -it --rm macabees/boxes sh -c 'echo "Hello World" | boxes'`

## Docker Push
`$ docker push -t macabees/boxes:latest`

Note: requires `docker login`

## Help
`$ docker run -it --rm macabees/boxes boxes --help`
