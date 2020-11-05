# Ambiente Web para Docker - NGINX

## 💻 Ambiente

Ambiente completo de desenvolvimento Web.

- [x] NGINX
- [x] PHP 7
- [x] Composer
- [x] PostgreSQL

## 🚀 Como executar o ambiente

### Pré-requisitos:

- Docker e Docker Compose.
- Não ter nenhuma aplicação executando nas portas 80, 443, 5432 e 9000.

### Instalação do Docker e Docker Compose:

- <a href="https://docs.docker.com/engine/install/" target="_blank">Instalação do Docker</a>
- <a href="https://docs.docker.com/compose/install/" target="_blank">Instalação do Docker Compose</a>

####  [Ubuntu]
- Para executar o Docker sem SUDO:
```bash
$ sudo usermod -aG docker $USER
```

### Como executar:

```bash
# Clona a aplicação do GitHub
$ git clone https://github.com/leonardopigatto/docker-ambiente-web-nginx.git

# Acessa a pasta que contém os códigos
$ cd docker-ambiente-web-nginx

# Executa o ambiente (em background)
$ docker-compose up -d

# Encerra a execução
$ docker-compose down

# Reconstroi o ambiente
$ docker-compose up -d --build
```

### Acesso:

Para acessar e ver as informações do PHP: http://localhost/.
