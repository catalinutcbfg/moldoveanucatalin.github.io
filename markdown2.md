![Text descriptiv Imagine](https://th.bing.com/th/id/OIP.a1CexLzdq5ogQ4qzji7CCgHaFx?rs=1&pid=ImgDetMain)

**Cuprins**

[Elemente avansate de Markdown](avansate.md)

[Formule cu Mathjax](mathjax.md)

[Matrice si ecuatii cu MathJax](mathjax2.md)

[Diagrame Mermaid](/diagrame/mermaid.md)
***


# Elemente de MarkDown partea a doua


## Inserarea codului de programare in MarkDown si HTML

### Cod `In linie`

**Markdown**

Iata un fragment de cod scris pe aceeasi linie: `a = b**c`

**HTML**

<code> a=b**c </code>

### Cod scris pe mai multe linii

**In MarkDown**

```python
import pandas as pd
import numpy as np

a = 2
b = 3

**HTML:**

<pre>
import pandas as pd
import numpy as pd

a = 2
b = 3
</pre>

## Inserarea elementelor evidentiate (blockquote)

**MarkDown**
> Acesta este un text evidentiat

**HTML**
<blockquote>
Acesta este un text evidentiat
</blockquote>

## Avantajele HTML fata de MarkDown

**MarkDown**

![Total Station](images/)

**HTML**

<img src=images/mp.jpg
width="200px" align=center>

**MarkDown**

***

**HTML**

<hr size =10>

<p> Acesta este un paragraf </p>

### Echivalentul unui link in HTML

[Textul Linkului](https://www.google.com)

<a src="https://www.google.com" alt="Textul linkului">


<!DOCTYPE html>
<html>

<head>
<meta charset =UTF-8>

</head>

<body>
<header>....</header>
<main>...</main>
<footer>...</footer>
</body>

</html>