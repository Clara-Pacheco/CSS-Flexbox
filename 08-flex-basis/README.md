# flex-basis

Indica o tamanho inicial do flex item antes da distribuição do espaço restante.

Quando definimos o flex-grow: 1; e possuímos auto no basis, o valor restante para ocupar o container é distribuído ao redor do conteúdo do flex-item.

Define o **tamanho padrão de um elemento** antes do espaço disponível ser distribuído. O valor pode ser em px, %, em, etc.
Se o valor for auto, ele irá olhar para o valor de width e height do item.
Se o valor for content, ele irá olhar para o tamanho do conteúdo do item.

```css
.container{
   display: flex;  
}
.item.selected{
   flex-basis: 50px;  
}
```


<br />

