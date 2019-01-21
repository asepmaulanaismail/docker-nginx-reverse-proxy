# docker-nginx-reverse-proxy
Nginx reverse proxy with docker

# How to
## Clone the repository.
```bash
$ git clone https://github.com/asepmaulanaismail/docker-nginx-reverse-proxy.git
$ cd docker-nginx-reverse-proxy
```
## Change proxy_pass url
Replace proxy_pass url with your app url in `nginx.conf`:
```bash
// replace 192.168.4.64:82 with your app url
proxy_pass http://192.168.4.64:82;
```
## Run
```bash
$ docker-compose up -d
```
