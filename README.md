## Instalación Rocket Chat Docker


hacerce Root:
```
sudo su
```

Copiar el Repositorio
```
git clone https://github.com/mclitos/rocket.chat
```

Si no tiene instalado git, puede ejecutar:
```
apt install git
```

Cambiar al nuevo directorio:
```
cd rocket.chat
```

Crear el compose:
```
docker compose pull
```

Levantar y ejecutar Rockerchat:
```
docker compose up -d && docker compose logs
```

Abrir el Navegadoir:
```
http://tuipservidor:3000
```
