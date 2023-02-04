# template

A Hello World with A-Frame for local development.

## Instalation

* download it or clone in any location
* install [Docker](https://docs.docker.com/get-docker/)

## Usage

* change files inside `html` directory
* open terminal and navigate to folder that contains `html` folder
* type `docker compose up`
* take your machine IP (`ifconfig` or `ipconfig` commands)
* open address on your device brownser (ex: http://192.168.0.2/)
* click in advanced, choose `go to https:192*** not secure`

### Security notes

VR devices need secure connections ([HTTPS](https://en.wikipedia.org/wiki/HTTPS)) to run.

That projects use a self [signed certificates](https://en.wikipedia.org/wiki/Self-signed_certificate), it implies to the warning when the brownser opens the address on the first time.

## Websocket

Websocket are forwarded on `https://[you ip address]/ws`.

You can change this route on `nginx.config` to better fit your needs.
