# API-node.js

API básica em Node.js para armazenamento de projetos.

# A API faz uso de 4 métodos HTTP

 * Métodos HTTP:
 
 * GET: Buscar informações da API
 * POST: Criar uma informação na API
 * PUT/PATCH: Alterar uma informação na API
 * DELETE: Deletar uma informação na API
 
 
 # Utilizamos 3 parâmetros 

 * Tipos de parâmetros:
 * 
 * Query Params: Filtros e paginação
 * Route Params: Identificar recursos (Atualizar/Deletar)
 * Request Body: Conteúdo na hora criar ou editar um recurso (JSON)
 
 E ultilizamos um Middleware.
 
 Middleware:

 * Interceptador de requisições que interromper totalmente a requisição ou alterar dados da requisição.
