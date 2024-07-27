# docker-compose for Cloud-Torrent with Tor Proxy
[![Build Status](https://raw.githubusercontent.com/ariadata/public-files/main/assets/ariadata-logo-300x120.png)](https://ariadata.co)

![](https://img.shields.io/github/stars/ariadata/cloud-torrent-tor.svg)
![](https://img.shields.io/github/watchers/ariadata/cloud-torrent-tor.svg)
![](https://img.shields.io/github/forks/ariadata/cloud-torrent-tor.svg)

> This needs : [dockerhost](https://github.com/ariadata/dockerhost-sh)
---
#### 1- Clone this repo and pull it's docker images:
```sh
git clone https://github.com/ariadata/cloud-torrent-tor.git cloud-torrent-tor && cd cloud-torrent-tor
cp example.env .env
rm -rf .git
docker compose pull
```
#### 2- Edit `.env` file and set `CLOUD_TORRENT_GUI_HTTP_PORT`,`UID`,`GID`:

#### 3- Run docker compose file by using :
```sh
docker compose up -d
```
#### 4- Goto : 
>  `http://YOUR-IP:CLOUD_TORRENT_GUI_HTTP_PORT`

Done!
