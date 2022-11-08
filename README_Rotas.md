A API do checklist ira armazenar todos os dados de avaliação que o usuario informou no aplicativo.

Todas as rotas são privadas

<strong>Protocolos HTTP existentes na API </strong>

<ul>
<li>401 - Cliente não está autenticado ou os dados de autenticação são inválidos.</li>
<li>403 - A autenticação foi bem-sucedida, mas o usuário autenticado não tem acesso ao recurso.</li>
<li>405 - Método HTTP que não é permitido para o usuário autenticado.</li>
<li>500 - Erro genérico indicando um problema de execução no servidor (cliente pode fazer chamar novamente se faz sentido)</li>
<li>200 - Resposta a um bem-sucedido GET, PUT, PATCH ou DELETE. Também pode ser usado para um POST que não resulte em uma criação.</li>
<li>201 - Em requisições POST quando um recurso é criado.</li>
<li>204 - Resposta a uma requisição bem-sucedida que não retorna um corpo (requisição DELETE).</li>
</ul>

<strong>Rotas POST</strong>


<strong>Rotas GET</strong>


<strong>Rotas PUT</strong>


