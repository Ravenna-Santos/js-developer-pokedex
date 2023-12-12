# Trilha JS Developer - Pokedex
Neste repositório salvei o projeto acompanhado na aula, e posteriormente, quando tiver mais habilidades de JS irei realizar o desafio proposto.

tentar fazer algo assim: https://dribbble.com/shots/16833947-Mobile-Pokedex-App-Design-Exploration/attachments/11892526?mode=media
no arquivo assets/js/main.js
<a href="#" onclick="showPokemonDetails(${pokemon.number})">${pokemon.name}</a>
function showPokemonDetails(pokemonNumber) {
    // Redireciona para uma nova página ou faz algo com o número do Pokémon clicado
    window.location.href = `detalhes.html?pokemon=${pokemonNumber}`;
}
ou apenas /:id e tals
