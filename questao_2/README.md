# Teste Técnico ETUS - Questão 2

**Candidato:** Arthur Gontijo

## Como acessar a análise

Na mesma pasta em que este markdown está localizado há um arquivo chamado `analise.ipynb`. As análises nele já estão rodadas, então não há necessidade de fazer nenhuma configuração prévia caso o usuário apenas queira ler o código e as recomendações. As células de código são acompanhadas por interpretações detalhadas em linguagem não técnica. Caso você não tenha interesse na implementação técnica, pode seguir a leitura apenas pelos comentários e análises que sucedem cada bloco de código.

## Como reproduzir a análise. 

Para rodar os códigos presentes no notebook, é necessário seguir os seguintes passos:

### Instalar as bibliotecas necessárias.

A lista das bibliotecas usadas para a análise pode ser encontrada no arquivo `requirements.txt`. Para instalá-las basta rodar o seguinte comando no terminal:

`pip install -r requirements.txt`

### Configurar a chave de acesso ao BigQuery

É necessário que uma chave de acesso ao bigquery seja disponibilizada por meio de uma client file em JSON. Para instruções de como fazer isso, recomendo o seguinte [vídeo](https://www.youtube.com/watch?v=gb0bytUGDnQ). 

Com seu arquivo JSON criado, coloque-o na mesma pasta em que o notebook está com o nome: `bigquery_api_key.json`.

Pronto! Agora está tudo certo para rodar as células de código do notebook
