
## Criando a imagem do container com php e laravel
```docker build -t (nome-imagem):latest .```

## Criando o container 
```docker run --rm -d --name (nome-container) -p 8000:8001 (nome-imagem) [--host=0.0.0.0 --port=8001]```
