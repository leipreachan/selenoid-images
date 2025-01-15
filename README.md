# Browser Images
[![Build Status](https://github.com/aerokube/images/workflows/build/badge.svg)](https://github.com/aerokube/images/actions?query=workflow%3Abuild)
[![Release](https://img.shields.io/github/release/aerokube/images.svg)](https://github.com/aerokube/images/releases/latest)

The original repo is not maintained, consider https://aerokube.com/moon/latest as alternative.

The owner of this fork still tries to update and support the versions they need: https://hub.docker.com/repository/docker/leipreachan/selenoid

This repository contains [Docker](http://docker.com/) build files to be used for [Selenoid](http://github.com/aerokube/selenoid) and [Moon](http://github.com/aerokube/moon) projects. You can find prebuilt images [here](https://hub.docker.com/u/selenoid/).

## Download Statistics

### Firefox: [![Firefox Docker Pulls](https://img.shields.io/docker/pulls/selenoid/firefox.svg)](https://hub.docker.com/r/selenoid/firefox)

### Chrome: [![Chrome Docker Pulls](https://img.shields.io/docker/pulls/selenoid/chrome.svg)](https://hub.docker.com/r/selenoid/chrome)

### Opera: [![Opera Docker Pulls](https://img.shields.io/docker/pulls/selenoid/opera.svg)](https://hub.docker.com/r/selenoid/opera)

### Android: [![Android Docker Pulls](https://img.shields.io/docker/pulls/selenoid/android.svg)](https://hub.docker.com/r/selenoid/android)

## Building Images

Moved to: http://aerokube.com/images/latest/#_building_images

## Image information
Moved to: http://aerokube.com/images/latest/#_browser_image_information


## Important
If you changed anything in the repo, RE-RUN `go generate github.com/aerokube/images && go build`!!!!!

If build from a local *.deb file fails, use `python3 -m http.server 8080` to expose the browser and run `docker build ..` command
