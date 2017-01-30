# RabbitMQ cli for debugging

If you want to run an
[amqp cli](https://github.com/cthayer/node-amqp-cli#readme) to debug something
real quick, this image is for you.

## Usage

```shell
$ docker run -ti jannis/node-amqp-client bash
root@9147e793df36:/# amq-consume --help
…
root@9147e793df36:/# amq-publish --help
```

## About

This image just pulls the latest
[node docker image](https://hub.docker.com/_/node/) and the latest
[node-amqp-cli](https://github.com/cthayer/node-amqp-cli)
npm package
