Passos para iniciar o projeto:

git clone: https://github.com/Paulaarquelino/provaDocker.git

entrar na pasta: cd provaDocker

Subir container docker compose up -d

Criando o arquivo .env docker compose exec laravel_api cp .env.example .env

Intalando as dependencias da api docker compose exec laravel_api composer install

Como executar a migração para o banco de dados docker compose exec laravel_api /var/www/html/artisan migrate:fresh

Criando o usuário padrão no banco de dados docker compose exec laravel_api /var/www/html/artisan db:seed

Stop os cantainers docker compose down

Para atualizar git pull cd provaDocker

Subir containers e atualizar as imagens docker compose up -d --build

Acessar api http://localhost:9090

Referências:

Laravel Nuxt

https://www.youtube.com/watch?v=NY9yoqoN72w&t=1004s

https://www.youtube.com/watch?v=HLPoKz9j9KY&t=325s

Docker

https://www.youtube.com/watch?v=ScmgXebitlQ&list=PLN_FLtIvNW0mo63rPdFBgL_UP5wF5eWLT
