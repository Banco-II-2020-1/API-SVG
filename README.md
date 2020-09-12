# API-SVG
API com Node e Express que permite consultar o path e o viewbox das geometrias dos municípios do banco do IBGE.

#Inicialização
Para inicializar basta clonar o repositório, usar o comando npm i, e por último, rodar o script npm start.

#Alterar parâmetros
Você pode alerar os dados da conexão do banco e da porta da API no arquivo .env

#Uso
Exemplo, para consultar o path e a viewBox da cidade de Apodi, considerando que a API está ouvindo na porta 3000:
http://localhost:3000/getSvg/apodi
http://localhost:3000/getViewBox/apodi
