# gc-actions-lab-03-docker

Lab 03 · Exercício 02 — build de imagem Docker no GitHub Actions.

- Sem secrets: o workflow **builda** a imagem (`lucased22/webacademy:latest`) sem push.
- Com secrets `DOCKERHUB_USERNAME` e `DOCKERHUB_TOKEN`: faz login e push no Docker Hub.