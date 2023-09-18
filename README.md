# laravel-my-app

Instalação do Projeto
Copia o arquivo .env.example e cola com o nome .env.

Instalar os pacotes do projeto:

$ composer install
Gera a chave do laravel:

$ php artisan key:generate
Configura o banco de dados com as variaveis ambiente:

DB_CONNECTION=
DB_HOST=
DB_PORT=
DB_DATABASE=
DB_USERNAME=
DB_PASSWORD=
Startando a aplicação:

$ php atisan serve
TABELAS
Cria uma migration de tabela de alunos

# Criando a tabela inscritos
$ php artisan make:migration create_alunos_table
Cria um model para tabela de alunos

$ php artisan make:model inscritos
Verifica os status das migrations

$ php artisan migrate:status
Criando as tabelas no banco de dados

$ php artisan migrate
Criando o controller de Inscritos

$ php artisan make:controller InscritoController --resource

