
# 💻 Finanças  

Projeto integrador de um site de controle de finanças.

## 🚀 Pré-Requisitos 

Software necessários para a instalação:

<ul>
 <li>PHP 7.1 ou superior</li>
 <li>Composer</li>
 <li>MySql</li>
 <li>WampServer</li>
</ul>

## 🔧 Instalação

### Clonar o projeto
```
git clone https://github.com/Anacss24/Financas-Projeto_integrador.git 
```
### Entrar no diretório criado 
```
cd Financas-Projeto_integrador
```
### Instalar as dependências do projeto
```
composer install
composer update
```

### Crie o Arquivo .env
```
cp .env.example .env
```
### Atualize as variáveis de ambiente do arquivo .env
```
DB_CONNECTION=mysql
DB_HOST=127.0.0.1
DB_PORT=3306
DB_DATABASE= ""
DB_USERNAME=root
DB_PASSWORD= ""
```

### Gerar a key do projeto Laravel
```
php artisan key:generate
```

### Migrar as tabelas 
```
php artisan migrate
```
### Instalar npm
```
npm install
npm run build
npm run dev
```

### Iniciar o servidor
```
php artisan serve
```
### Desenvolvedores
  [<img src="https://avatars.githubusercontent.com/u/101267392?s=100" /><br /><sub>@Anacss24</sub>](https://github.com/Anacss24) 
  
  [<img src="https://avatars.githubusercontent.com/u/150391010?s=100" /><br /><sub>@felipenassil</sub>](https://github.com/felipenassil) 
 









