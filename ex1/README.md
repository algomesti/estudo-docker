# Exercício 1
- Criar uma imagem com nginx que suba o serviço com index.html com hello world + 'nome'.
- Fazer o push para o DockerHub.
- Subir um container com a imagem criada em alguma porta local.

## Passos:
- Criar conta no DockerHub
  - algomesti

- Criar repositório no DockerHub
  - nginx-estudo

- Criar o [Dockerfile](Dockerfile)

- Fazer o build da imagem
  ```
  docker image build -t nginx-estudo:1.0 .
  ```

- Fazer o push da imagem no DockerHub.
  ```
  docker push algomesti/nginx-estudo:1.0
  ```

-  Subir o serviço.
```
  docker run -p 8081:80 algomesti/nginx-estudo:1.0
```
