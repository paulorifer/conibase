# Controle de Retiradas — Sistema de Gestão de Estoque

Sistema em Python desenvolvido para resolver um problema real da empresa 
onde trabalho: controle de estoque, busca de produtos por cliente e 
acompanhamento de retirada de mercadorias.

## Funcionalidades

- Cadastro de produto com código RP, loja, cliente, CPF, localização física, 
  número do pedido, nota fiscal e data de chegada
- Busca de produto por CPF do cliente
- Marcação de produto como retirado
- Persistência completa dos dados em arquivo JSON (não perde nada ao fechar)

## Tecnologias

- Python 3
- Módulo `json` para persistência de dados
- Módulo `datetime` para registro de data/hora do cadastro

## Próximos passos

- Migração da persistência para SQLite
- Criação de API com FastAPI

## Autor

Paulo Ricardo Ferreira — Estudante de ADS | Mackenzie
[LinkedIn](https://www.linkedin.com/in/paulorifer/) | [GitHub](https://github.com/paulorifer)
