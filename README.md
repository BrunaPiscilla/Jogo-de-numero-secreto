# Jogo do Número Secreto

Este é um jogo simples desenvolvido em **JavaScript**, **HTML** e **CSS**, onde o jogador tenta adivinhar um número secreto gerado aleatoriamente. O objetivo do jogo é acertar o número secreto com o menor número de tentativas.

## Funcionalidades

- O número secreto é gerado aleatoriamente entre 1 e 10.
- O jogador pode inserir sua tentativa através de um campo de entrada.
- O jogo informa se o número secreto é maior ou menor que o chute do jogador.
- Um botão "Novo Jogo" permite reiniciar o jogo após acertar o número.

## Tecnologias Utilizadas

- **HTML**: Estrutura da aplicação.
- **CSS**: Estilização do layout.
- **JavaScript**: Lógica do jogo.

## Como Jogar

1. Abra o arquivo `index.html` em seu navegador.
2. Insira um número entre 1 e 10 no campo de entrada.
3. Clique no botão "Chutar".
4. O jogo informará se o número secreto é maior ou menor que sua tentativa.
5. Continue tentando até acertar o número secreto.
6. Ao acertar, o botão "Novo Jogo" será ativado para reiniciar o jogo.

## Estrutura do Projeto

```plaintext
/
├── index.html     # Estrutura HTML do jogo
├── style.css      # Estilos CSS para o layout
├── app.js         # Lógica do jogo em JavaScript
├── img/
│   └── ia.png     # Imagem utilizada no layout
```

## Melhorias Futuras

- Adicionar níveis de dificuldade, alterando o intervalo de números.
- Implementar um contador de tempo para desafiar o jogador.
- Salvar as melhores pontuações no navegador usando LocalStorage.

## Contribuição

Sinta-se à vontade para contribuir com melhorias! Faça um fork deste repositório, implemente suas alterações e envie um pull request.

## Licença

Este projeto é de uso livre e aberto para fins educacionais e recreativos.
