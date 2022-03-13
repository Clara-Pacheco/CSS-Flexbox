### 5 - justify-content

![](https://css-tricks.com/wp-content/uploads/2018/10/justify-content.svg)
Define o alinhamento dos itens ao longo do **eixo principal**.


- **flex-start (padrão):** os itens ficam junto no começo da linha
- **flex-end:** os itens ficam juntos no final da linha
- **center:** os itens ficam centralizados na linha
- **space-between:** os itens são distribuídos igualmente no espaço disponível. O primeiro item fica no começo da linha e o último fica no final.
- **space-around:** os itens são distribuídos igualmente no espaço disponível ao redor deles.
- **space-evenly:** os itens são distribuídos igualmente no espaço disponível.

```css
.container{
   display: flex;
   justify-content: space-around;  
}
```

> **Ver exemplo (row):** [Link](https://marcelopoars.github.io/flexbox/app/04-justify-content/row)

<br />
