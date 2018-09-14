# Docker with React

[![Build Status](https://travis-ci.org/davidhenley/docker-react.svg?branch=master)](https://travis-ci.org/davidhenley/docker-react)

## Running in Development with Docker

`docker-compose up --build`

## Running in Production with Docker

1. `docker build -t henleydr/docker-react .`
2. `docker run -p 8080:80 henleydr/docker-react`
3. Open `http://localhost:8080` in your browser.
