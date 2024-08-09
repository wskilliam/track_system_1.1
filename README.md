<h1>Sistema de trechos</h1>

<h2>Descrição do Sistema:</h2>

<h4>Sistema será utilizado para o cadastro e gerenciamento de trechos de uma determinada rodovia. </h4>

<p>Requisitos</p>
<p>- PHP 7.1 ou superior</p> 
<p>- Composer</p>
<p>- MySQL</p>
<p>- Node.js com npm ou yarn</p>

**OBS:** __Instalação foi feito no sistema operacional Windows 10.__
## Instalação ##

1. **Clone o Repositório:**

````
git clone https://github.com/wskilliam/track_system_1.1.git
````
2. **Instale as Dependências do Backend:**

_Copiar código:_

````
composer install
````

3. **Instale as Dependências do Frontend:**

_Copiar código:_
````
npm install
````

4. **Configurar o Banco de Dados:**

_Copie o arquivo .env.example para .env:_

_Copiar código:_
````
cp .env.example .env
`````

_Configure suas credenciais de banco de dados no arquivo **.env**:__

_Copiar código:_
````
DB_CONNECTION=mysql
DB_HOST=127.0.0.1
DB_PORT=3306
DB_DATABASE=track_system
DB_USERNAME=root
DB_PASSWORD=admin
`````
**Gere a chave da aplicação:**

_Copiar código_`

````
php artisan key:generate
`````

**Execute as migrações para criar as tabelas:**

_Copiar código:_
````
php artisan migrate
````
**Compilar os Arquivos do Frontend:**

_Copiar código:_
```
npm run dev
````

5. **Para iniciar o servidor de desenvolvimento:**

_Copiar código_
````
php artisan serve
````

6. **O sistema estará disponível em http://localhost:8000/trechos**
