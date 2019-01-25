# Simple Helm Starter

## Intro
This repo contains a basic Helm Starter Chart `my-app-starter` and an example built from that starter `my-app` - which is configured to use the app from https://github.com/chris-mac/simple-nodejs-microservices. 

## Usage
`my-app-starter` will need to be copied to your `~/.helm/starters` directory (there is currently no slicker way to do this).
You can build a chart from this starter by using
`helm create {{my-chart}} --starter my-app-starter`

## Configuration
The only configuration options provided at present are
- `imageRegistry`
- `containerPort`
