<script id="MathJax-script" async src="https://cdn.jsdelivr.net/npm/mathjax@3.0.1/es5/tex-mml-chtml.js"></script>

![Text descriptiv Imagine](https://th.bing.com/th/id/OIP.a1CexLzdq5ogQ4qzji7CCgHaFx?rs=1&pid=ImgDetMain)

[Homepage](index.md)

# Inserarea ecuatiilor si formulelor "Mathjax"

**Sintaxa:**

Formulele 'Mathjax' sunty inserate in aceeasi linie daca sunt plasate intr-o pereche de simboluri '$'

Exemplu: Aceasta este o ecuatie: $a=bc$

Formulele 'Latex' (prin 'Mathjax') se introduc pe rand nou intre doua perechi de simboluri '$$'

*Exemplu:*

$$a=b^c$$

# Ridicarea la putere (superscript)

Se foloseste meta-caracter 'LaTex': '^'

Exemplu:

$$a=10^7$$

# Subscript

Se foloseste meta-caracterul 'LaTex': '_'

Exemplu:

$$a_i=b^c$$




# Gruparea elementelor din formule

Elementele din formule se grupeaza prin meta-caracterele '{' si '}'

$$ 10^{10} $$

# Literele grecesti

*Exemple:*

'\alpha' - alpha litera mica ($\alpha$)

'\Alpha' - alpha litera mare ($\Alpha$)

# Parantezele

- Parantezele rotunde se scriu direct (nu au un inteles special 'LaTex')
- Parantezele drepte se scriu direct (nu au inteles special in 'LaTex')
- Acoladele, deoarece ele sunt metacaractere de grupare, vor fi renderizate corect daca sunt 'escapate' de intelesul special, punand in fata lor 'metacaracterul' '\'

  Exemple:

  $$a = (b+c)^{3x} - [3+6x]$$

  # Fractiile

  *Exemplu:*

  '\frac{numarator}{numitor}

$$ a = \frac{(a+bc)}{(d-c)} $$

# Semnele de multiplicare si respectiv de diviziune

*Exemple:*

$$ a = c + 10 \times x $$

$$ a = c + 10 \cdot x $$

$$ a = b \div c $$

# Suma de la i=0 la n

**Exemplu:**

$$ \sum_{i=0}^n i^2 = \frac{(a+b) \times (b+c)}{6} $$

# Integrale

**Exemple:**

$$ \int_0^1 x^4 dx $$
