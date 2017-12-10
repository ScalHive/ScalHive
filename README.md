# scalhive
scalhive web application

## Literature
- [Customizing GitHub Pages](https://help.github.com/categories/customizing-github-pages/)
 
## Interesting examples
- [Paul Chiusano pesonal blog](https://github.com/pchiusano/pchiusano.github.io) 


## Docker manual
[Docker image for running GitHub Pages / Jekyll projects](https://hub.docker.com/r/starefossen/github-pages/)

### Run docker container in ./docs folder
```
docker run -t --rm -v "$PWD":/usr/src/app -p "4000:4000" starefossen/github-pages
```
