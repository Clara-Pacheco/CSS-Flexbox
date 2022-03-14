# flex-shrink

Define a capacidade de redução de tamanho do item.

Indica o **quanto um item pode encolher** caso seja necessário. Deve ser um número inteiro positivo.
Isso significa que se todos os itens tiverem o valor 1, o espaço disponível será distribuído igualmente a todos eles.
Caso um dos itens tenha o valor 2, este item poderá ter metade do espaço do que os outros.

![Flex-shrink](https://github.com/Clara-Pacheco/CSS-Flexbox/blob/main/09-flex-shrink/flexbox.png%20(400%C3%97300)%20-%20Google%20Chrome%2014_03_2022%2006_46_31.png)

```css
.container{
   display: flex;  
}
.item{
  flex-basis: 40%;  
}
.item.selected{
  flex-shrink: 2;  
}
```


<br />
