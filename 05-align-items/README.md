# align-items

O align-items alinha os flex itens de acordo com o eixo do container. O alinhamento é diferente para quando os itens estão em colunas ou linhas.

Essa propriedade permite o tão sonhado alinhamento central no eixo vertical, algo que antes só era possível com diferentes hacks.


![](https://css-tricks.com/wp-content/uploads/2018/10/align-items.svg)
Define o alinhamento dos itens perpendicularmente em relação ao **eixo principal**. Pense nele como um **justify-content**, mas que alinhará os itens no outro eixo.


- **stretch (padrão):** estica os elementos para preencherem o container.
- **flex-start:** os itens ficam junto no começo do eixo perpendicular
- **flex-end:** os itens ficam juntos no final do eixo perpendicular
- **center:** os itens ficam centralizados no eixo perpendicular
- **baseline:** parecido com o center, mas usando a base da linha como referência. No exemplo abaixo, note como os textos dos itens ficam alinhados.

```css
.container{
   display: flex;
   align-items: flex-start;  
}
```

> **Ver exemplo (row):** [Link](https://marcelopoars.github.io/flexbox/app/05-align-items/row)

<br />
