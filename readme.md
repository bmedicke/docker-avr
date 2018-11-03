# building and pushing a new image

```sh
docker build . -t bmedicke/avr:v0.0

docker login
docker push bmedicke/avr:v0.0
```
