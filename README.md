# Proyecto Docker Batman

## Descripción
Se ha desplegado una infraestructura web con Docker Compose formada por:

- Un proxy inverso Nginx
- Dos servidores Apache
- Balanceo de carga
- Red interna aislada
- Volumen compartido

## Arquitectura

[ NAVEGADOR ]
       |
       v
   [ NGINX ]
     /   \
    v     v
[WEB1] [WEB2]

## Elección de Batman
He elegido Batman porque es mi superhéroe favorito desde pequeño.

## Despliegue

```bash
docker compose up -d
