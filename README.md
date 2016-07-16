# sts
Spring Tool Suite in docker container

How to Run
----------
docker run -it --rm -e DISPLAY=$DISPLAY -v /tmp/.X11-unix:/tmp/.X11-unix -v `pwd`:/workspace emirates/sts
