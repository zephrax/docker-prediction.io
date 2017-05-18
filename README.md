# docker-prediction.io

## Prediction.IO Automated Docker Build

As I needed to run the Universal Recommender, the only way I got it working was using an old version. So currently there is only one branch (master) and its working with Prediction.IO v0.9.6

### List of currently supported versions:

* Prediction.IO v0.9.6 (master/0.9.6)

### How to Start

```bash
~# docker pull zephrax/docker-prediction.io
~# docker run -ti zephrax/docker-prediction.io
```
Once the container is launched, you got a shell into it. To start all of the services run:
```bash
~# pio-start-all
```

### Other versions

I will add new tags for other versions soon.

### Stuff used to make this:

 * [docker-predictionio](https://github.com/steveny2k/docker-predictionio) based on this Dockerfile

