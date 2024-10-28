![Text descriptiv Imagine](https://metricop.com/cdn/shop/articles/trimble-total-station.jpg?v=1677673954)



[Homepage](index.md)

# Inserarea ecuatiilor si formulelor 'Mathjax'

**Sintaza:**

Formu;e; 'MathJxax' sunt inserate in aceeasi linie daca sunt plasate intr-o pereche de simboluri '$'

Exemplu:Aceasta este o ecuatie $a=bc$

Formule 'Latex'(prin 'Mathjax')se introduc pe rand doua perechi de simboluri "$$'

*Exemplu:*
$$a=b^c$$

#Ridicarea la putere

Se foloseste meta-caracter 'latex':^

Exemplu:

$$a=10^7**
#'subscript'

se folosete meta-caracterul 'latex':'_'

*Exemplu:*

$$a_i=b^c$$


# Gruparea elementelor din formule 

Elementele din formule se grupeaza prin meta-caracterele '{' si '}'

$$10^{10}$$

#Literele grecesti

*Exemple;*

'\alpha' alpha litera mica ($\alpha$)
'\Alpha' alpha litera mare ($\Alpha$)


# Parantezele


-Parantezele rotunde se scriu direct(nu au un inteles special 'Latex')

-Parantezele rotunde se scriu drepte(nu au un inteles special 'Latex']

-Acoladaele,deoarece ele sunt metacaractere de grupare,vor fi renderizate corect daca sunt 'escapade' de la intelesul lor special,punand in fara


*Exemple;*
$$a=(a+c)^(3x)-[3+6x]$$


#Fractie

'\frac(numarator){numitor}


$$ a=/frac{(a+B)}(d-e)


# Semnele de multiplicare si respectiv de diviziune 

*Exempl:*

$$ a=c + 10\times x $$

$$a=c + 10\cdot x $$

$$a= b\div c $$

#Suma de la i=0 la n

**Exemplu:**

$$\sum_{i-0}^n i^2=\frac{(a+b)\times (b+c)}{6}$$

