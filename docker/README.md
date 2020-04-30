#### Construir a imagem

```
docker build -t grails3:0.1 .
```

#### Executar

```
docker run -d --name grails3 -p 8080:8080 grails3:0.1
```

#### Remover 

```
docker stop grails3
docker rm grails3
```

