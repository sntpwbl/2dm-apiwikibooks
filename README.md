<h1>API Naciona Livros - Descrição</h1>
API construída para entrega de sprint do curso técnico de desenvolvimento de sistemas no SENAI Suiço-Brasileira com intuito de ler, inserir, alterar e deletar informações sobre livros nacionais.

<h1>Tecnologias utilizadas</h1>
<strong>Node.js</strong> - v20.10.0<br>
<strong>Express</strong> - v4.19.2<br>
<strong>Mongoose</strong> - v8.3.2

<h1>Requisitos</h1>
<strong>npm</strong> - v10.2.3

<h1>Utilização</h1>
<ol>
  <li>Clone esse repositório:<br><code>git clone https://github.com/sntpwbl/2dm-apiwikibooks.git</code></li><br>
  <li>Navegue até o diretório gerado:<br><code>cd 2dm-wikibooks</code></li><br>
  <li>Instale as dependências da API:<br><code>npm install</code></li><br>
  <li>Inicie o servidor:<br><code>npm start</code></li>
</ol>

<h1>Rotas</h1>
<strong>GET /books</strong>: Retorna todos os livros inseridos no banco;<br>
<strong>GET /books/searchid/:id</strong>: Retorna um único a partir do seu id;<br>
<strong>GET /books/searchname/:name</strong>: Retorna todos os livros com um nome semelhante ao que foi passado;<br>
<strong>POST /books</strong>: Insere um novo livro no banco;<br>
<strong>PUT /books/:id</strong>: Atualiza um livro a partir de seu id;<br>
<strong>DELETE /books/:id</strong>: Deleta um livro a partir de seu id.

<h1>Observações</h1>
<ul>
  <li>Os campos para inserção são: name, author, description, year, page_number e cover;</li>
  <li>Com exceção de page_number, todos os outros campos são obrigatórios;</li>
  <li>Para inserir uma imagem, utilize o endereço da mesma.</li>
</ul>
