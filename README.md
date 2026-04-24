Primero imagenes, abajo esquema general

<img width="1865" height="1079" alt="Captura de pantalla 2026-04-24 163042" src="https://github.com/user-attachments/assets/87c8dbb8-dcc5-4f4a-a208-6cafb44dbbfa" />
<img width="1919" height="545" alt="Captura de pantalla 2026-04-24 163002" src="https://github.com/user-attachments/assets/9ba16a9b-52eb-4c96-866c-1b65ad42e8fe" />
<img width="982" height="466" alt="Captura de pantalla 2026-04-24 161027" src="https://github.com/user-attachments/assets/12fbca0c-5fe5-4f89-ae73-30aca7408219" />
<img width="779" height="989" alt="Captura de pantalla 2026-04-24 160559" src="https://github.com/user-attachments/assets/29e5da90-c060-40fa-adae-9c069b5dcabf" />
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
