# order

Modifica a ordem dos flex itens. Sempre do menor para o maior, assim order: 1, aparece na frente de order: 5.

![](https://css-tricks.com/wp-content/uploads/2018/10/order.svg)
Por padrão, os itens de um Flex Container são exibidos na ordem presente no **HTML**.
Com a propriedade **order** nós podemos alterar a ordem dos elementos. O valor deve ser um número inteiro, negativo ou positivo


```css
.container{
   display: flex;
   justify-content: space-evenly;
   align-items: center;  
}
.item.selected{
   order: 1;  
}
```
<br />

![](https://github.com/Clara-Pacheco/CSS-Flexbox/blob/main/11-order/images%20(392%C3%97129)%20-%20Google%20Chrome%2014_03_2022%2007_08_48.png)

<br>

![](https://github.com/Clara-Pacheco/CSS-Flexbox/blob/main/11-order/images%20(392%C3%97129)%20-%20Google%20Chrome%2014_03_2022%2007_09_26.png)

