### Clonar el repositorio

###  En la raiz del proyecto crear carpetas data/dvwa

```
mkdir data/dvwa
```
 

### Construir la imagen

```
docker build -t kali-custom ./
```

### Levantar contenedores

```
docker compose up -d --build
```

### Ingresar al contenedor de kali

```
docker exec -it kali /bin/bash
```