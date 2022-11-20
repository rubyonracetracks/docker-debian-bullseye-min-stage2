[![CI](https://github.com/rubyonracetracks/docker-debian-bullseye-min-stage2/actions/workflows/build.yml/badge.svg)](https://github.com/rubyonracetracks/docker-debian-bullseye-min-stage2/actions/workflows/build.yml)

# Docker Debian Bullseye - Minimal - Stage 2

This repository is used for building the Stage 2 Minimal Debian Bullseye Docker image for [Ruby on Racetracks](https://www.rubyonracetracks.com/).

## Name of This Docker Image
[ghcr.io/rubyonracetracks/docker-debian-bullseye-min-stage2](https://github.com/rubyonracetracks/docker-debian-bullseye-min-stage2/pkgs/container/docker-debian-bullseye-min-stage2)

## Upstream Docker Image
[ghcr.io/rubyonracetracks/docker-debian-bullseye-min-stage1](https://github.com/rubyonracetracks/docker-debian-bullseye-min-stage2/pkgs/container/docker-debian-bullseye-min-stage1)

## What's Added
* Git
* Ansible
* Python
* SQLite, PostgreSQL, Redis, and other common external dependencies of Ruby on Rails apps
* Heroku
* NVM and Node.js

## Things NOT Included
Ruby version managers, such as RVM

## What's the Point?
* This Docker image is a building block for other Docker images for [Ruby on Racetracks](https://www.rubyonracetracks.com/).
* Software for managing Ruby versions (such as RVM) is NOT included in this Docker image.  (This is covered in downstream Docker images.)

## More Information
General information common to all Docker Debian build repositories is in the [FAQ](https://gitlab.com/rubyonracetracks/docker-common/blob/master/FAQ.md).
