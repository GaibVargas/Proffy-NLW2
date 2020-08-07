<h1>Proffy - Backend</h1>
<p>Backend do projeto</p>

<h2>Tecnologias</h2>
<ul>
  <li><a href="https://nodejs.org/en/">Node.js</a></li>
  <li><a href="https://www.sqlite.org/index.html">SQLite</a></li>
  <li><a href="http://knexjs.org/">Knex</a></li>
  <li><a href="https://github.com/axios/axios">Axios</a></li>
</ul>

<h2>Rodar o projeto</h2>
<ol>
  <li>Abra a pasta do projeto, e entre na pasta server, e então execute:
  
  ```console
    yarn
  ```
  
  </li>
  <li>Execute as migrations:
  
  ```console
    yarn knex:migrate
  ```
  
  </li>
  <li>Para executar o backend (por padrão será usada a porta 3333 do localhost):
  
  ```console
    yarn start
  ```
  
  </li>
</ol>
