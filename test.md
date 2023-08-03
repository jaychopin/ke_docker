version: "3.7"
services:
  websrv-a: 
    image: "nginx:alpine"
    networks:      
      
net-proxy
net-backend
  websrv-b:
    image: "nginx:alpine"
    networks:
net-proxy
net-backend
  db:
    image: "nginx:alpine"
    networks:
net-backend
  mq:
    image: "nginx:alpine"
    networks:
net-backend
networks:
    net-backend:
    net-proxy:
