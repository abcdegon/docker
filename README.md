# Docker
This is a small project using container. I will use this repository for documentation purposes mainly. Probably this small project helps to learn more about containers and about how to use them.

## About Containers
I will add more information about containers later.

## Reverse Proxy
Containers make it easy to run services and expose them to other clients on the same network or to clients on the INTERNET. Following Dockers Matra: "One container for one single service" the number of containers grows fast probably and each of them can be compared to entrance to your system. Is it good to have a lot of entries?

However, think abut your house or a fortress. There is only one single entrance. You can close it, you can open it and you can control who's getting in.

This is where a reverse proxy comes into the game of containers. The only container exposed to the outside network is the remote proxy. It takes incoming requests and forwards them to the right containers and forwards the answers to the requesting client.

There are a lot of reverse proxies. From my point of view the most popular ones are [nginx](https://www.nginx.com) and [traefik](https://traefik.io/traefik) which I use here.

## Summary