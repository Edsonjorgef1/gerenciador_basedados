# gerenciador_basedados
Pacote de Laravel que permite gestao de banco de dados.

# instalacao

1 - `composer install`<br>
2 - `php artisan dbm:install`<br>
3 - Cria um usario (usando Tinker ou Seeder) e depois corre o comando: <br>
`php artisan dbm:admin admin@admin.com` (Atribuir permissoes ao usuario) <br>
4 - `php artisan config:cache` <br>
5 - Acesse a rota: `http:128.0.0.1:800/database` <br>
6 - Faz o login com usuario criado e atribuido permissoes de acesso a Gerenciamento de Base de Dados <br>

[DOCUMENTACAO](https://codexshaper.github.io/docs/laravel-database-manager/) <br>
[Projecto original](https://github.com/Codexshaper/laravel-database-manager)
