### 3 - flex-wrap

Define se os itens devem quebrar ou não a linha. Por padrão eles não quebram linha, isso faz com que os flex itens sejam compactados além do limite do conteúdo.

Essa é geralmente uma propriedade que é quase sempre definida como flex-wrap: wrap; Pois assim quando um dos flex itens atinge o limite do conteúdo, o último item passa para a coluna debaixo e assim por diante.


![](https://css-tricks.com/wp-content/uploads/2018/10/flex-wrap.svg)
O comportamento padrão dos itens de um elemento flex é ficar em uma única linha. Se a largura total de todos os itens for maior do que o espaço disponível, os itens continuarão na mesma linha.

Esta propriedade permite que os itens sejam jogados em outra linha caso não haja mais espaço na linha.


- **nowrap (padrão):** todos os itens ficam em uma única linha
- **wrap:** os itens que não cabem na linha são jogados para baixo
- **wrap-reverse:** os itens que não cabem na linha são jogados para cima

```css
.container{
   display: flex;
   flex-wrap: wrap;  
}

.item{
   width: 40%;  
}
```

> **Ver exemplo:** [Link](https://marcelopoars.github.io/flexbox/app/03-flex-wrap/)


<br />


