# OpenCV, Flask & Docker

#### A stripped down version of: https://github.com/realpython/flask-image-search
#### As seen in the tutorial: http://www.pyimagesearch.com/2014/12/08/adding-web-interface-image-search-engine-flask/

A minimal starting point for building a `Flask` app with `OpenCV2` on an `Ubuntu 14.04.3` `docker` image

#### Getting started:

1. Install `docker` https://www.docker.com/
2. Clone this repo
3. Run `docker build --rm -t opencv-docker .` to build/re-build the image
4. Run `docker run -p 80:5000 opencv-docker` to run the container
5. In your browser, go to the IP address of the `docker` container which will be given when you run the _Docker Quickstart Terminal_ which is installed with `docker`. See this article if you are still having trouble: http://networkstatic.net/10-examples-of-how-to-get-docker-container-ip-address/
6. You will see "Welcome!" in your browser.

**Have fun!**
