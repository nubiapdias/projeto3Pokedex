# projeto2Pokedex

O Pokédex é um dispositivo eletrônico criado e projetado para catalogar e fornecer informações sobre as várias espécies de Pokémon apresentadas no videogame Pokémon, anime e séries de mangás. O nome Pokédex é um neologismo que inclui "Pokémon" (que é um aglutinação de "bolso" e "monstro") e "índice". O nome japonês é simplesmente "Enciclopédia Pokémon", pois pode apresentar todos os Pokémon nele, dependendo do Pokédex.

# Projeto 2 do módulo 2 BlueEdtech

ara construir esse projeto, usei usei um JSON de dados dos Pokémon. Aqui também é um exemplo de como sua aplicação pode ser com relação ao layout.
Requisitos:
Criar um projeto no GitHub com Readme.md, .gitignore e licença;
Iniciar um projeto node;
Instalar as dependências:
Express
Nodemon
EJS
Alterar os scripts do package.json;
Criar as pastas:
public
css (arquivo style.css)
js (arquivo script.js)
views
Crie um arquivo principal chamado index.js;
Crie a rota principal, renderizando a view index.ejs;
Crie a rota de cadastro, renderizando a view cadastro.ejs;
Crie a rota detalhes, renderizando a view detalhes.ejs;
Crie uma const chamada pokedex que será um array;
cada objeto deve conter essas informações dos pokemons:
Número;
Nome;
Tipo;
Imagem;
Altura;
Peso;
Categoria;
Ao renderizar a view index.ejs, envie esse array como variável;
Estilize toda a view index.ejs para receber os dados do array, porém só adicione o nome, imagem e tipo do pokemon. Reserve os outros dados para a rota detalhes.
