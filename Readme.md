# Estudo Site Profissional 

Este projeto ira abortar tecnicas de **HTML**, **CSS** e **JS**.

- Criando paginas para demonstrar o uso de ferramentas
- Varias dicas para desenvolver sites profissionais

## Display Flex CSS
- Aprendendo a usar display flex
- É uma ferramente do CSS que ajuda a posicionar os itens na tela no lugar desejado
- É uma propriedade tambem em que os componentes ficam responsivo 

### Flex Container
| id| Nome            |Descrição                      |
|---|-----------------|-------------------------------|
| 1 | flex-direction  |Direcionar linhas e colunas    |
| 2 | flex-wrap       |Limita e altera o tamanho      |
| 3 | flex-flow       |Uma junção de wrap e direction |
| 4 | justify-content |Alinha items na horizontal     |
| 5 | align-items     |Alinha items na vertical       |
| 6 | align-content   |Alinha todos os items juntos   |
| 7 | gap             |Cria espaçamento entre os items|  

- flex-direction
  -
  - row (linha 1, 2, 3, 4, 5)
  - row-reverse (Linha 5, 4, 3, 2, 1)
  - column (Coluna)
  - column-reverse (Coluna Reversa)

- flex-wrap
  -
  - nowrap (limita o tamanho dos items)
  - wrap (quebra o limite de tamanho)
  - wrap-reverse (inverte o item)

- flex-flow
  -
  - flex direction + flex wrap
    - row wrap 
    - column nowrap

- justify-content (Eixo principal)
  -
  - flex-start (Posiciona tudo a esquerda)
  - flex-end (Posiciona tudo a direita)
  - center (posiciona tudo ao centro)
  - space-between (Da espaçamento entre o items)
  - space-around (Da espaçamento entre o items porem desalinhados)
  - space-evenly (Da espaçamento entre o items porem alinhados)

- align-items (Eixo secundario)
  -
  - stretch
  - flex-start
  - flex-end 
  - center (Alinha no centro da tela)

![Imagem de Exemplo ](./IMG/Exemplo%20de%20eixos.png)

>!important
>
>Diminuir o tamanho da imagem

- align-content (Alinha todos os items juntos)
  -
  - stretch
  - flex-start
  - flex-end
  - center
  - space-between
  - space-around

- gap (Cria espaçamento entre todos os items)
  -

### Flex Items
| id| Nome        |Descrição                                   |
|---|-------------|--------------------------------------------|
| 1 | flex-basis  |Permite colcoar tamanho exato em cada item  |
| 2 | flex-grow   |Controla o quanto que cada item vai crescer |
| 3 | flex-shrink |Controla o quanto que cada item vai diminuir|
| 4 | flex        |É uma atalho para o basis, grow e shrink    |
| 5 | order       |Altera a ordem dos items                    |
| 6 | align-self  |Muda o posicionamento do item dentro da div |

-align-self
  -
  - flex-start
  - flex-end
  - center
  - baseline
  - stretch

>!Importante
>
> Site com documentação: mdn web docs (https://developer.mozilla.org/en-US/)

#Projeto para colocar em pratica o display box
