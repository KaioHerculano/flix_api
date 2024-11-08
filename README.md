<h1>Flix API</h1>
Este projeto é uma API desenvolvida em Django que fornece acesso a informações de filmes e séries. O objetivo da flix_api é oferecer endpoints RESTful para buscar, adicionar, atualizar e remover dados relacionados a conteúdo de mídia.

<h1>Funcionalidades</h1>
<h3>CRUD Completo: A API oferece operações completas para criar, ler, atualizar e deletar dados relacionados a:</h3>
  <ol>
    <li>Atores</li>
    <li>Filmes</li>
    <li>Gêneros de filmes</li>
    <li>Avaliações (reviews).</li>
  </ol>
<h1>Tecnologias</h1>
  <ol>
    <li>Django Rest Framework: Framework principal para construção da API.</li>
    <li>JWT (JSON Web Token): Para autenticação de usuários.</li>
    <li>PythonAnywhere: Deploy da API para um ambiente de produção seguro e acessível.</li>
    <li>Autenticação JWT: Implementação de autenticação segura com JSON Web Token (JWT), garantindo que apenas usuários autorizados tenham acesso ao gerenciamento de dados.</li>
  </ol>
<h1>Endpoints Principais</h1>
  <ol>
    <li>GET /api/v1/movies/ - Lista todos os filmes.</li>
    <li>POST /api/v1/movies/ - Adiciona novo filme.</li>
    <li>PUT /api/v1/movies/{id}/ - Atualiza um filme.</li>
    <li>DELETE /api/v1/movies/{id}/ - Remove um filme.</li>
  </ol>
