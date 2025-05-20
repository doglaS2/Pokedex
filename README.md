# Pokédex

Este é um projeto simples de Pokédex que utiliza a [PokeAPI](https://pokeapi.co/) para exibir informações de Pokémon. A interface web é construída com HTML, estilizada com CSS e a lógica com JavaScript.

## Estrutura do Projeto

- **[index.html](index.html)**  
  Define a estrutura principal da página, inclui os links para os arquivos CSS e JavaScript e monta a interface com botões para navegação entre os Pokémon.

- **[css/style.css](css/style.css)**  
  Responsável pela formatação e estilo visual da aplicação, incluindo a disposição, cores e efeitos dos elementos da página.

- **[js/script.js](js/script.js)**  
  Gerencia a lógica da aplicação:  
  - Faz chamadas à PokeAPI para buscar dados dos Pokémon.  
  - Atualiza a interface com os dados retornados (nome, número e imagem animada).  
  - Lida com a navegação entre os Pokémon com os botões "Prev" e "Next" e o formulário de pesquisa.

- **Imagens e Favicons**  
  Arquivos gráficos que compõem a identidade visual (ex.: Pokédex, ícones).

## Funcionalidades

- **Busca de Pokémon**  
  - Pesquisa via nome ou número.  
  - Exibe "Loading..." enquanto aguarda a resposta da API.  
  - Mostra os dados do Pokémon ou uma mensagem de erro caso não seja encontrado.

- **Navegação**  
  - Botões para acessar o Pokémon anterior ou o próximo.

## Pokémons e Gerações

- Este projeto permite a busca de pokémons de **todas as gerações** através da PokeAPI.
- **Observação:** A imagem exibida para cada pokémon utiliza o sprite animado da **Geração V (Black & White)**, presente na API. Sendo assim, mesmo que você busque um pokémon de outra geração, a visualização será baseada nessa arte específica.

## Como Usar

1. **Clone o repositório:**

   ```sh
   git clone <URL-do-Repositório>![](https://github.com/doglaS2/Pokedex/blob/master/mostruario.png)