# Layout Spotify - Imersão Front-end

Modelo em CSS e HTML de uma versão do layout do Spotify, serviço de streaming de música. Possui um sistema básico de busca pelo nome de um artista em um mock de API de poucos resultados. Aplicação é acessada pelo navegador da máquina hospedeira.

## Front-end

A página front-end abre com a seguinte URL:

```
http://localhost:5500/index.html
```

## Back-end

Instale o Node.js, disponível em:

```
https://nodejs.org/
```

Instale a dependência necessária: json-server

```
npm i json-server -g
```

Para que a busca simples pelo nome do artista funcione, o mock da API de consulta deve ser executado pelo comando:

```
json-server --watch api-artists/artists.json --port 3000
```

A página inicial do _back-end_ abre com a seguinte URL:

```
http://localhost:3000/artists/
```
