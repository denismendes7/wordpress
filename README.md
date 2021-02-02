# wordpress
One page com Wordpress

Passo a passo para executar o projeto localmente:

Com o xampp instalado, apache e mysql em execução, insira a pasta do projeto "wordpress" dentro da pasta xampp/htdocs.

No phpmyadmin crie um novo banco de dados e importe o arquivo .sql que está da pasta banco dentro no projeto.

Depois de ter importado verifique se o nome do banco de dados criado está igual no arquivo wp_config.php na pasta wordpress.
 
define( 'DB_NAME', 'bdteste' );

Caso não esteja com o mesmo nome altere;

No navegador digite localhost/wordpress  para abrir a home do projeto, e para entrar no painel de administração do wordpress digite localhost/wordpress/wp-admin .

Para logar utilize o usuário: (admin) e senha: (admin);
