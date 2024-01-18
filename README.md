# Servidor de Live Streaming

## Requisitos 
- Docker 
- [OBS](https://obsproject.com/pt-br/download)

## Tecnologias
- Docker compose
- NGINX

## Protocolos 
- RTMP (Real Time Message Protocol)
- HLS (HTTP Live Streaming)

## Como executar

Suba os containers utilizando docker compose
```
docker-compose up --build
```

Abra o [OBS](https://obsproject.com/pt-br/download) > Configurações > Transmissão > Servidor
```
rtmp://localhost:1935/live
```
Clique em ok e depois clique em **Iniciar transmissão**

## Como assistir a transmissão
```
http://localhost:8081/live/.m3u8
```
