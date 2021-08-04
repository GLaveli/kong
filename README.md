<img src="https://github.com/GLaveli/Ahgora/blob/main/gitAssets/logo.png" width="150px" height="120px" align="left"/>

# Kong & Konga
API Gateway + database + interface.

------------------------------------------

# Requisitos:

* Docker V: 20.10.7+
* Docker-compose v: 1.29.2+

------------------------------------------

# Instalação:

Abra o CMD e cri uma rede internet no docker chamada kong-net
```
 docker network create kong-net
```

Navegue ate a pasta do projeto em seguida para a pasta 'compose' execute em seu terminal favorito o comando:
```
 docker-compose up -d
```
aguarde a instalação, ao termino suba os containers kong-postgres, compose_kong e compose_konga caso eles não subam altomaticamente.

Agora basta coectar a API do Kong com o Konga acessando:
```
 localhost:1337
```

------------------------------------------

# outros acessos

para acessar a API Gateway use:
```
 localhost:8000
```
para acessar a API do kong use:
```
 localhost:8001
```
