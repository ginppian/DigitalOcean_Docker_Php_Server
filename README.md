Digital Ocean
==============

## VPS

<p align="justify">
	Un servidor virtual privado (VPS, del inglés virtual private server) es un método de particionar un servidor físico en varios servidores de tal forma que todo funcione como si se estuviese ejecutando en una única máquina. Cada servidor virtual es capaz de funcionar bajo su propio sistema operativo y además cada servidor puede ser reiniciado de forma independiente.
</p>

<p align="justify">
	Descargamos todas las librerias necesarias y construir todo el ambiente de desarrollo.
</p>

```
	docker-compose build
```

<p align="justify">
	Corremos el servidor con la opción -d para que lo ejecute en background y puedamos seguir usando la termianl.
</p>

```
	docker-compose up -d
```

<p align="justify">
	Detenemos el servidor.
</p>

```
	docker-compose stop
```

## Fuente

<a href="https://www.digitalocean.com/community/tutorials/initial-server-setup-with-ubuntu-16-04#step-four-%E2%80%94-add-public-key-authentication-(recommended)">Dar de alta un nuevo usuario en el Drop</a>
<br>
<a href="https://www.digitalocean.com/community/tutorials/how-to-install-docker-compose-on-ubuntu-16-04">Instalar Docker en el Drop</a>
<br>
<a href="https://hub.docker.com">Buscar una imagen de Docker</a>
<br>
<a href="https://www.youtube.com/watch?v=zcCEA0aG3aU">Instalar un LAMP server with Docker</a>