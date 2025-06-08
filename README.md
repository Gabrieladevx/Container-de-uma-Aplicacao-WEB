# Projeto Web com Docker + Apache

Este projeto é um exemplo simples de site estático rodando em um container Docker com Apache.

## Como rodar

1. Certifique-se de que o Docker Desktop está aberto e rodando.
2. No terminal, navegue até a pasta do projeto (onde está o arquivo `docker-compose.yml`).
3. Execute:

```powershell
docker-compose up -d
```

4. Acesse no navegador: [http://localhost](http://localhost)

## Como parar

Para encerrar o container, execute:

```powershell
docker-compose down
```

## Estrutura do projeto

- `website/` — Arquivos HTML, CSS e recursos do site
  - `index.html` — Página inicial
  - `sobre.html` — Página sobre
  - `estilos.css` — Estilos modernos e responsivos
- `docker-compose.yml` — Configuração do container Apache
- `.dockerignore` — Arquivos e pastas ignorados pelo Docker
