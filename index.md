# Implementarea relatiilor in Markdown

![Text descriptiv Imagine](https://th.bing.com/th/id/OIP.a1CexLzdq5ogQ4qzji7CCgHaFx?rs=1&pid=ImgDetMain)

**Cuprins**

[Elemente avansate de Markdown](avansate.md)

[Formule cu Mathjax](mathjax.md)
***

## Implememntarea relatiilor/legaturilor catre alte fisiere

Fisirele accesate prin linkuri pot fi:
1. Gazduite pe alte servere (de exemplu accesarea unui alt site)
2. Gazduite pe serverul site-ului curent

De asemenea, prin aceste linkuri se pot accesa si sectiuni din pagina curenta sau sectiuni din alte pagini ale aceluiasi site

### Sintaxa unui link Markdown

Tipuri de linkuri in Markdown:
1. Linkuri clasice (normale)
2. Linkuri referentiale

#### Linkuri clasice 

**Variante:**
1. [Textul linkului](https://www.google.com/)
2. [Textul linkului](https://www.google.com/ "Accesare site Google")

#### Linkurile referentiale 

Iata un []link[] catre site-ul Google.

[link1]: https://www.google.com/

Varianta prescurtata a linkurilor preferentiale:

Iata un link [important] catre site-ulGoogle

[important] https://www.google.com/

#### Linkuri catre imagini


