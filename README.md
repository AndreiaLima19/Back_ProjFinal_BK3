# Projeto Final API RESTful - Loja Esportiva

## Rotas: Roupas e Calçados

##### Integração Frontend + Backend + Mongo Atlas + Heroku.

API com rotas e banco de dados distintos, através do VS Code.

**** Existem os seguintes Endpoints por rota:

[GET] Leitura de todos os itens

[GET] Leitura de itens individuais (por ID)

[POST] Cadastro

[PUT] Edição de item por ID

[DELETE] Exclusão de item por ID


###  Url_heroku = "https://lojasesportivas.herokuapp.com"

## **** Endpoints - Roupas ****

[GET] Leitura de todos os itens
Url_heroku/roupas/listall

[GET] Leitura de itens individuais (por ID)
Url_heroku/roupas/listid/id

[POST] Cadastro
Url_heroku/roupas/add

Todos os campos são obrigatórios:

{ 

  "tipo": "String", 

  "genero": "String",
  
  "marca": "String", 
  
  "tamanho": "String",
  
  "cor": "String"
  
}

[PUT] Edição de item por ID
Url_heroku/roupas/update/id

Todos os campos são obrigatórios:
{ 

  "tipo": "String", 
  
  "genero": "String",
  
  "marca": "String", 
  
  "tamanho": "String",
  
  "cor": "String"
  
}

[DELETE] Exclusão de item por ID
Url_heroku/roupas/delete/id

## **** Endpoints - Calçados ****

[GET] Leitura de todos os itens
Url_heroku/calcados/listall

[GET] Leitura de itens individuais (por ID)
Url_heroku/calcados/listid/id

[POST] Cadastro
Url_heroku/calcados/add

Todos os campos são obrigatórios:
{ 

  "tipo": "String", 

  "genero": "String",
  
  "marca": "String", 
  
  "tamanho": "Number",
  
  "cor": "String"
  
}

[PUT] Edição de item por ID
Url_heroku/calcados/update/id

Todos os campos são obrigatórios:
{ 

  "tipo": "String", 

  "genero": "String",
  
  "marca": "String", 
  
  "tamanho": "Number",
  
  "cor": "String"
  
}

[DELETE] Exclusão de item por ID
Url_heroku/calcados/delete/id

### Projeto configurado e conectado ao Mongo Atlas.
