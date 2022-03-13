# align-content

Alinha as linhas do container em relação ao eixo vertical. A propriedade só funciona se existir mais de uma linha de flex-itens. Para isso o flex-wrap precisa ser wrap.

Além disso o efeito dela apenas será visualizado caso o container seja maior que a soma das linhas dos itens. Isso significa que se você não definir height para o container, a propriedade não influencia no layout.

![](https://css-tricks.com/wp-content/uploads/2018/10/align-content.svg)

Alinha as linhas do container.
Por alinhar as linhas, esta propriedade só tem efeito quando há mais de uma linha.


- **stretch (padrão):** estica as linhas para preencherem o espaço restante.
- **flex-start: as linhas** ficam juntas no começo do container
- **flex-end:** as linhas ficam juntas no final do container
- **center:** as linhas ficam centralizadas no container
- **space-between:** as linhas são distribuídas igualmente. A primeira linha fica no começo do container e a última fica no final.
- **space-around:** as linhas são distribuídas igualmente no espaço disponível ao redor delas.

```css
.container{
   display: flex;
   flex-wrap: wrap;
   align-content: flex-start;   
}
```

> **Ver exemplo (row):** [Link](https://marcelopoars.github.io/flexbox/app/06-align-content/row)

<br />
