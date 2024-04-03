
# Desafio Full Cycle Módulo Docker
## Desafio Go

Esse desafio é muito empolgante principalmente se você nunca trabalhou com a linguagem Go!
Você terá que publicar uma imagem no docker hub. Quando executarmos:

docker run <seu-user>/golang:latest

Temos que ter o seguinte resultado: Full Cycle Rocks!!

Lembrando que a Go Lang possui imagens oficiais prontas, vale a pena consultar o Docker Hub.

A imagem de nosso projeto Go precisa ter menos de 2MB =)

# Build 
```
docker build -t <seu-user>/golang:latest .
```

# Pull 
```
docker pull genarofigueiredo/golang:latest
```

# Executar o container
```
docker run --rm genarofigueiredo/golang:latest
```