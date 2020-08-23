# Responsividade


## CSS Units

Unidades de medidas do CSS

Layout Fixo<br>
`px` - Pixels


Layout Fluido <br>
`%` - Porcentagem <br>
`auto` - Automática <br>
`vh` - Viewport Height <br>
`vw` - Viewport Width <br>


Textos fixos <br>
`1px` = 0.75pt <br>
`16px` = 12pt <br>


Textos fluidos <br>
`em` - Multiplicado pelo pai <br>
`rem`- Multiplicado pelo root <br>




## Media Queries CSS

```css
@media(max-width: 320px){
  #form h3{
   font-size: 2rem; 
  }

}
```

## HTML Media Atrib.










## Imagens
`<picture>`

JPG, PNG vs SVG


## Anotações

Estratégias de responsidade com % e max-with


```css
 Exemplo:

 with: 100%;
 max-width: 980px;
 ```

 Estratégia com rem

 ```css
  Exemplo: 

 html{
  font-size: 62.5%; -> A  cada 1rem será considerado 10px
 }

 a{
   font-size: 2rem; -> 20px
 }

 ```
 
 Estratégia pra grid sem usar @media

 ```css

 grid-template-columns: repeat(auto-fit, minmax(250px, 1fr)); -> crie colunas de acordo com o tamanho da tela com no minimo 250px e no máximo flexivel!
                                                      

 ```
