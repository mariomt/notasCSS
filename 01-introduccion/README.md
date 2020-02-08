
# Introducción a CSS

CSS por sus siglas en inglés _**C**ascading  **S**tyle  **S**heets_ (Hojas de Estilo en Cascada), es el lenguaje utilizado por los desarrolladores para dar estilos a los documentos HTML o XML y así poder dar una mejor presentación de dichos documentos. CSS le dice al navegador como debe presentar la información en pantalla, dando a los elementos, colores de fondo, fuentes, tamaños, etc.

>Tenemos que tener en claro que HTML como CSS no son lenguajes de programación, estos son lenguajes de marcado de hipertexto y un lenguaje de estilos respectivamente.

Esto fue una pequeña definición sobre lo que es css y lo que no es css, para leer un poco más sobre la anatomía de una regla CSS y algunos otros temas puede visitar la siguiente página dando click [aqui](https://developer.mozilla.org/es/docs/Learn/Getting_started_with_the_web/CSS_basics).

## Temas
A continuación te menciono algunos de los temas que deberías aprender para poder entender mejor lo básico de CSS.
### ¿Cómo usar CSS?
- **Embebido**: Esta forma de usar css no es recomendable usarla ya que da muchos dolores de cabeza al momento de querer dar mantenimiento a las distintas páginas del sitio. La forma de utilizarlo es utilizando la propiedad style que tienen las etiquetas html.
- **Interno**:  Esta manera de utilizar estilos es poco recomendable usar ya que los estilos solo harán efecto al documento que los contengan, por lo cual si queremos reutilizar dicho código habría que copiar y pegar el código nuevamente en las otras páginas que hagan uso de estos estilos. La manera de utilizarlo es por medio de las etiquetas `<style></style>` las cuales se deben colocar en el head de la página.
- **Externo**: Esta es la manera mas recomendable de utilizar estilos en tu sitio web ya que es muy practico y muy fácil de mantener ya que dicho código lo puedes utilizar en varias páginas referenciando a un mismo archivo.
### Selectores
- **Elementos**
- **Clases**
- **Identificadores**
- **Atributos**
- **pseudo-clases**

- **Agrupados:** 
Por ejemplo `p, h1{ propiedad: valor}`

- **Descendientes:** (hijos)
Por ejemplo `header  h1 { propiedad:valor }` (no es recomendable utilizarlo).

- **hijo directo**
Por ejemeplo `header > h1 { propiedad:valor } `

- **Hermano siguiente:**
Por ejemplo `.title + .subtitle { propiedad:valor }`

- **Hermanos siguientes:**
Por ejemplo `.hermano-mayor ~ .hermano { propiedad:valor }`




También contamos con los selectores compuestos los cuales como su nombre lo indica son selectores que se componen de varios selectores...

### Modelo de Caja
- **width**
- **height**
- **padding**
- **margin**
- **border**

### Colapsado de margenes
Debemos comprender muy bien este tema ya que puede ser un dolor de cabeza al estar diseñando un sitio y no obtener lo que esperamos, como resumen podemos decir que los margenes superiores e inferiores de los elementos se colapsan siempre y cuando los los elementos no sean interrumpidos por algún otro elemento como texto entre otras cosas. 
Hay que tomar en cuenta que el primer hijo de un elemento puede colapsar su margen con el margen del padre siempre y cuando el padre no tenga un borde o un padding que lo interrumpa.
Para leer y comprender mejor este tema podemos visitar el siguiente [enlace](https://developer.mozilla.org/es/docs/Web/CSS/CSS_Modelo_Caja/Mastering_margin_collapsing).

### Unidades de medida
#### Absolutas
- **in** (pulgadas)
- **cm** (centímetros)
- **pc** (Picas)
- **mm** (milímetros)
- **pt** (puntos)
- **px** (pixeles)

>**pt** suele usarse para documentación que se imprimirá.

#### Relativas

- **rem** (tamaño de la raíz)
- **em** (tamaño de la fuente del navegador)
- **ex** (~0.5em o al alto de la x minúscula)
- **ch** (respectiva a la altura del carácter cero)
- **%**
- **vw**
- **vh**
- **vmin** 
- **vmax**

>**rem** El tamaño es respecto al tamaño de la raíz o body.
>**em** El tamaño es respecto a la fuente de su contenedor padre.
>**vmin y vmax** Es respecto al porcentaje de la dimensión mas grande o más pequeña según lo indicado.


### Variables
Las variables css nos permiten almacenar valores para despues utilizarlo en las propiedades, con la finalidad de agrupar un conjunto de parametros en una sola variable y asi cuando tengamos que hacer un cambio en lugar de hacerlo en varias propiedades solo se hará el cambio en la variable.

### Especificidad


### Herencia


### Cascada

