# ESTUDO DOS END POINTS - PROVA API

\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\

**(1°) => Consultar tabela**

/GET /pets

_response_

{
    "id": id,
    "nome": nome
}

\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\


**(2°) => Inserir pet**

/POST   /pets

_request body_

{
    "nome": nome
}

_response 200_

{
    "nome": nome,
    "id": id
}


