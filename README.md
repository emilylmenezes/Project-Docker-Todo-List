# Boas vindas ao repositório do projeto <b>Docker Todo-List</b>!

Esse projeto foi desenvolvido durante o módulo de Backend na Trybe! #vqv 

---

# Habilidades desenvolvidas

- Conteinerizar aplicações;
- Criar uma conexão entre elas;
- Orquestrar seu funcionamento.

---

# Funcionamento da aplicação

Para iniciar o projeto, é necessário possuir o [Docker](https://docs.docker.com/engine/install/ubuntu/) instalado.

Para rodar o projeto, é necessário executar o comando
```
docker-compose up -d
```
na raíz do projeto. Isso fará com que os containers docker sejam orquestrados e a aplicação esteja disponível. Esse comando deve ser executado via terminal dentro do diretório onde está o arquivo **docker-compose.yml**.

O projeto trata-se de um desafio para consolidar o aprendizado com os comandos básicos de Docker e criação de container, bem como a criação de Dockerfiles para montar imagens e a utilização de Docker-compose para orquestrar esses Dockerfiles de forma a subir uma aplicação inteira com Docker totalmente containerizada!

---

# Histórico de Commits

É possível verificar todo o histórico de commits do projeto, de modo a visualizar passo-a-passo como foi desenvolvido o meu raciocínio até a finalização do projeto.

---

# Requisitos técnicos do desafio:

- ✅ 1. Crie um container em modo interativo, sem rodá-lo, nomeando-o como 01container e utilizando a imagem alpine na versão 3.12.

- ✅ 2. Inicie o container 01container.

- ✅ 3. Liste os containers filtrando pelo nome 01container.

- ✅ 4. Execute o comando cat /etc/os-release no container 01container sem se acoplar a ele.

- ✅ 5. Remova o container 01container.

- ✅ 6. Faça o download da imagem nginx com a versão 1.21.3-alpine sem criar ou rodar um container.

- ✅ 7. Rode um novo container com a imagem nginx com a versão 1.21.3-alpine em segundo plano nomeando-o como 02images e mapeando sua porta padrão de acesso para porta 3000 do sistema hospedeiro.

- ✅ 8. Pare o container 02images que está em andamento.

- ✅ 9. Gere uma build a partir do Dockerfile do back-end do todo-app nomeando a imagem para todobackend.

- ✅ 10. Gere uma build a partir do Dockerfile do front-end do todo-app nomeando a imagem para todofrontend.

- ✅ 11. Gere uma build a partir do Dockerfile dos testes do todo-app nomeando a imagem para todotests.

# REQUISITOS BÔNUS

- ✅ 12. Suba uma orquestração em segundo plano com o docker-compose de forma que backend, frontend e tests consigam se comunicar
