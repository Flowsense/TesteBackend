# Definição da Tarefa:

Olá! Agradecemos o seu interesse na vaga da Flowsense.

Este é um teste para avaliarmos os diferentes skills para desenvolvimento backend e a capacidade de usar Python e Django.

Há uma parte em que é necessário mostrar uma página web, mas o front pode ser bem simples, usando HTML simples ou qualquer framework/ferramenta do seu interesse. Assim, não é necessário se preocupar com um design bonito, SPAs e afins. Vamos avaliar a organização do código/componentes e aplicação da lógica de programação.

Como entregar:
- Colocar o projeto em um repositório git público e compartilhar o link

Requisitos técnicos:
- Utilizar Django
- Utilizar a biblioteca requests para acessar a API indicada
- Testes unitários
- Readme expicando como instalar e rodar o projeto

Extras que seria legal ver:
- Tasks assíncronas (Usar celery, por exemplo)
- Dockerização


Sinta-se à vontade para instalar e usar quaisquer bibliotecas de suporte que desejar.

## DISCLAIMER: Estamos avaliando skills. Um ponto importante de trabalhar em time é poder buscar ajuda mútua. Se não souber fazer algo e/ou achar muito comprido, deixar indicado o que está faltando, "simulando" como outras pessoas no time poderiam eventualmente te ajudar.


## 1) Listar filmes OMDb
Quando o usuário abrir a URL raíz (Ex: localhost:8000/), mostrar uma lista de filmes com a imagem do cartaz, título do filme e gênero. A lista de filmes deve ser obtida de uma API REST pública da OMDb.

A lista de resultados deve ser enxuta, queremos avaliar requisições HTTP, portanto não estamos preocupados com um site que mostre muitos resultados de busca.

## 2) Permitir aplicar um filtro de gênero à busca
Permitir ao usuário do site aplicar um filtro de gênero (ex.: ação, comédia, drama) e retornar os resultados correspondentes a este filtro.

## 2) Favoritar filme
Quando o usuário clicar em um botão de "like" próximo ao filme, gravar em algum banco de dados da sua preferência esse filme.

### Pontos extras: Usar a autenticação do próprio Django para separar por usuário os filmes favoritos

## 3) Listar filmes favoritados
Quando o usuário abrir a url /favoritos/ (Ex: localhost:8000/favoritos/), mostrar uma lista de filmes favoritados com a imagem do cartaz, título do filme, gênero e data que o filme foi favoritado.

### Pontos extras: Dar nota para o filme favoritado e remover o filme dos favoritos.


# API Rest OMDb:

Entre em http://www.omdbapi.com/apikey.aspx e registre uma chave de API gratuita

Saiba como usar a API em http://www.omdbapi.com

ATENÇÃO: essa API gratuita tem um limite de 1000 requisições por dia. Cuidado para não usar mais do que o permitido.

# Biblioteca Requests:

https://requests.kennethreitz.org/en/master/
