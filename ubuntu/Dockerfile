FROM ubuntu:20.04

RUN apt-get update && apt-get install -y tzdata

ENV TZ=Asia/Tokyo

RUN apt-get update && apt-get upgrade -y && \
    apt-get install -y --no-install-recommends build-essential libx11-dev libxtst-dev x11-xserver-utils xvfb x11-apps xterm x11vnc firefox \
    nodejs npm imagemagick libcairo2-dev
