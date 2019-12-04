## Como correr NEST en jupyter

```
docker run --rm -e LOCAL_USER_ID=`id -u $USER` -v $(pwd):/opt/data -p 8080:8080 nestsim/nest:latest notebook
```
Va a levantar una imagen con todos los requerimientos necesarios
