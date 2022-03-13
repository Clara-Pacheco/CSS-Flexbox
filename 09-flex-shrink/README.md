# flex-shrink

Define a capacidade de redução de tamanho do item.

Indica o **quanto um item pode encolher** caso seja necessário. Deve ser um número inteiro positivo.
Isso significa que se todos os itens tiverem o valor 1, o espaço disponível será distribuído igualmente a todos eles.
Caso um dos itens tenha o valor 2, este item poderá ter metade do espaço do que os outros.

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