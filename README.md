# docker-prediction.io

## Prediction.IO Automated Docker Build

This project is used to build Prediction.IO containers. I'm actively adding support for different versions.

### List of currently supported versions:

* Prediction.IO v0.9.6 (branch 0.9.6)
* Prediction.IO v0.11.0 (branch 0.11.0)

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

