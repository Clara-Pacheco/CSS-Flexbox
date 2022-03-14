# flex-grow

Define a habilidade de um flex item crescer. Por padrão o valor é zero, assim os flex itens ocupam um tamanho máximo relacionado o conteúdo interno deles ou ao width definido.

Ao definir 1 para todos os Flex Itens, eles tentarão ter a mesma largura e vão ocupar 100% do container. Digo tentarão pois caso um elemento possua um conteúdo muito largo, ele irá respeitar o mesmo.

Se você tiver uma linha com quatro itens, onde três são flex-grow: 1 e um flex-grow: 2, o flex-grow: 2 tentará ocupar 2 vezes mais espaço extra do que os outros elementos.

OBS: justify-content não funciona em items com flex-grow definido.

![](https://css-tricks.com/wp-content/uploads/2018/10/flex-grow.svg)

Indica o quanto um item pode **crescer** caso seja necessário. Deve ser um número inteiro positivo.
Isso significa que se todos os itens tiverem o valor 1, o espaço disponível será distribuído igualmente a todos eles.
Caso um dos itens tenha o valor 2, este item poderá ter duas vezes mais espaço do que os outros.


```css
.container{
   display: flex;  
}
.item{
   flex-grow: 1;  
}
.item.selected{
   flex-grow: 2;  
}
```
<br />

![Flex-grow image](https://github.com/Clara-Pacheco/CSS-Flexbox/blob/main/07-flex-grow/flexbox.png%20(400%C3%97300)%20-%20Google%20Chrome%2014_03_2022%2006_37_43.png)
