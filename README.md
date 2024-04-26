# Criando-um-Jogo-da-mem-ria-com-Emojis-Utilizando-Javascript

[1]: https://www.youtube.com/watch?v=NV88N1r2Qkg ""
[2]: https://www.youtube.com/watch?v=nDrYuilcukM ""
[3]: https://www.youtube.com/watch?v=tcbMmm77WOU ""
[4]: https://marina-ferreira.github.io/tutorials/js/memory-game.pt-br/ ""
[5]: https://github.com/BrunoDorea/jogoDaMemoria-Emojis ""
[6]: https://github.com/HugoAPortela/Criando-Jogo-Memoria-Emojis-JavaScript ""
[7]: https://ichi.pro/pt/crie-um-jogo-de-memoria-com-react-e-javascript-133303565646838 ""
[8]: https://pt.stackoverflow.com/questions/246290/jogo-da-mem%C3%B3ria-com-javascript ""

Para criar um jogo da memória com emojis utilizando JavaScript, podemos seguir estes passos detalhados e dividir o projeto em módulos diferentes:

### Módulo HTML:
1. **Estrutura Básica**: Crie um arquivo `index.html` com a estrutura básica do HTML5.
2. **Contêiner do Jogo**: Adicione uma `<section>` que servirá como o tabuleiro do jogo.
3. **Cartas de Memória**: Dentro da `<section>`, crie `<div>` para cada carta de memória, que terá duas faces: uma com o emoji (front-face) e outra com um verso padrão (back-face).

### Módulo CSS:
1. **Estilos Básicos**: No arquivo `styles.css`, defina os estilos básicos para o corpo do documento, como fonte e cor de fundo.
2. **Estilização do Tabuleiro**: Use Flexbox ou Grid para posicionar as cartas no tabuleiro.
3. **Estilização das Cartas**: Adicione estilos para as cartas, como tamanho, margem e animações para o efeito de virar a carta.

### Módulo JavaScript:
1. **Lógica do Jogo**: No arquivo `scripts.js`, crie a lógica para inicializar o jogo, embaralhar as cartas e adicionar a funcionalidade de virar as cartas.
2. **Eventos**: Adicione event listeners para lidar com cliques nas cartas.
3. **Verificação de Correspondência**: Implemente a lógica para verificar se duas cartas viradas correspondem e, em caso afirmativo, mantenha-as viradas.

Aqui está um modelo prático em código para começar:

```html
<!-- index.html -->
<!DOCTYPE html>
<html lang="pt-br">
<head>
    <meta charset="UTF-8">
    <title>Jogo da Memória com Emojis</title>
    <link rel="stylesheet" href="styles.css">
</head>
<body>
    <section class="memory-game">
        <!-- Adicione suas cartas aqui -->
    </section>
    <script src="scripts.js"></script>
</body>
</html>
```

```css
/* styles.css */
.memory-game {
    display: flex;
    flex-wrap: wrap;
    width: 640px;
    margin: auto;
}
.memory-card {
    width: 100px;
    height: 100px;
    margin: 10px;
    /* Adicione estilos de virar cartas aqui */
}
```

```javascript
// scripts.js
document.addEventListener('DOMContentLoaded', () => {
    // Lógica para inicializar o jogo e adicionar eventos
});
```

Lembre-se de adicionar os emojis e estilizar as cartas para que elas possam virar quando clicadas. Você também precisará de um conjunto de emojis para usar como faces das cartas, que podem ser obtidos do teclado de emojis do Windows ou de qualquer biblioteca de emojis disponível.

Para mais detalhes e um guia passo a passo, você pode consultar tutoriais online ou repositórios que oferecem exemplos e explicações sobre como criar jogos da memória¹[1]²[2]³[3]⁴[4]. Esses recursos podem fornecer insights adicionais e técnicas específicas para aprimorar seu jogo.
