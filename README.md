# Projeto com Laravel 11/Ui

## Preparar Ambiente de Desenvovliemnto

### Instalar e Configurar os programas

-   PHP
-   Composer
-   Mysql Server
-   Visual Studio Code(Vs Code)
-   BDeaver
-   Git
-   Criar conta no github

### Configurar no `php.ini`

#### Habilitar as extensões

```
   extension=zip
   extension=fileinfo
   extension=gd
   extension=mysql
   extension=pdo_mysqlextension=pdo_pgsql
   extension=pdo_sqliteextension=pgsql
   extension=sqlite3
```

#### Habilitar a exibição de erros em tela,o tipo a ser reportado e o registro de logs de erros:

```
display_errors= On
error_reporting = E_ALL
log_errors = On
errors_log = /tmp/php_errors.log
```

#### Aumentar o limite de memoria em (Mb) , bem como tempo de execução minimo de cada

```
script em (Segundos)
memory_limite =512M
max_execution_time = 120
```

#### Permitir uploads e envio de formulários:

```
session.gc_maxlifetime = 14000
```

## Criar Projeto Laravel 11 , execute o comando:

```bash
composer create-project laravel/laravel: ^11 example_App
```

#### Para Executar o servidor embutido digite o comando abaixo:

```
php artisan serve

```

##### Criação de repositório local:

```
git init
```

#### Definir o branch princicpal :

```
com o comando
git branch -m main
```

#### Adicionando os arquivos do projeto

ao repositorio :

```
git add .
ou git add 'nomeArquivo'
```

#### Efetivar as alterações utilize o comando:

```
git commit -am "Primeiro Commit"
```

## Instalar e configurar o pacote laravel/ui:

```bash
composer require laravel/ui
php artisan ui vue --auth
npm install
npm run build (ou vite build -watch
```
