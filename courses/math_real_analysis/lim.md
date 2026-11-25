
# L&iacute;mite y continuidad

An&aacute;lisis matem&aacute;tico

<small>Funciones reales de una sola variable</small>

---

## Agenda

- Funciones num&eacute;ricas
- Sucesiones
- L&iacute;mite de una sucesi&oacute;n
- L&iacute;mite de una funci&oacute;n
- Funciones infinitamente peque&ntilde;as y grandes
- Continuidad de una funci&oacute;n
  * Continuidad uniforme
- Comparaci&oacute;n de funciones
- As&iacute;ntotas

---

## Magnitudes

- Constantes
  * conserva un mismo valor
    + en general
    + en un proceso dado (par&aacute;metro)
- Variable
  * toma valores num&eacute;ricos diferentes

---

## Funci&oacute;n

- `y` = f(`x`)
- Una variable `y` es funci&oacute;n de otra variable `x` si
  * est&aacute;n relacionadas
    + relaci&oacute;n funcional
  * a cada valor de `x` le corresponde un valor de `y`
    + &uacute;nico
    + totalmente determinado
- `x` : argumento o variable independiente
- `y` : variable dependiente

---

## Conjuntos

- Dominio de definici&oacute;n (dominio de existencia)
  * Conjunto de todos los valores de la variable independiente para los cuales la funci&oacute;n est&aacute; definida
- 

---

## Conjuntos (cont.)

![L&iacute;mite unilateral](../../img/bounds.png)

- Entorno del punto `a` &isin; &real;
  * Intervalo (&alpha;, &beta;) tal que
    + &alpha; &le; `a` &le; &beta;
    + se excluye el punto `a`
- Entorno izquierdo del punto `a` &isin; &real;
  * Intervalo (&alpha;, `a`)
- Entorno derecho del punto `a` &isin; &real;
  * Intervalo (`a`, &beta;)

---

## L&iacute;mite de una funci&oacute;n

![L&iacute;mite unilateral](../../img/lim.png)

- lim<sub style="font-size:50%">x &rarr; a</sub> f(x) = `A`
  * &forall;&epsilon;&gt;`0` &exist;&delta;(&epsilon;)
    + `0` &lt; &#124; x - `a` &#124; &lt; &delta;(&epsilon;) implies &#124; f(x) - `A` &#124; &lt; &epsilon;

---

## L&iacute;mite unilateral

![L&iacute;mite unilateral](../../img/lim_uni.png)

- lim<sub style="font-size:50%">x &rarr; a<sup>-</sup></sub> f(x) = `A`
  * &forall;&epsilon; &gt;`0` &exist;&delta;(&epsilon;)
    + x &isin; (&delta;(&epsilon;)`, a`) implies &#124; f(x) - `A` &#124; &lt; &epsilon;
- lim<sub style="font-size:50%">x &rarr; a<sup>+</sup></sub> f(x) = `B`
  * &forall;&epsilon; &gt;`0` &exist;&delta;(&epsilon;)
    + x &isin; (`a`, &delta;(&epsilon;)) implies &#124; f(x) - `B` &#124; &lt; &epsilon;

---

## L&iacute;mite vs infinito

- lim<sub style="font-size:50%">x &rarr; +&infin;</sub> f(x) = `A`
  * &forall;&epsilon; &gt;`0` &exist;&delta;(&epsilon;) &gt; `0`
    + &forall;x &gt; &delta;(&epsilon;) : &#124; f(x) - `A` &#124; &lt; &epsilon;
- lim<sub style="font-size:50%">x &rarr; -&infin;</sub> f(x) = `B`
  * &forall;&epsilon; &gt;`0` &exist;&delta;(&epsilon;) &lt; `0`
    + &forall; x &lt; &delta;(&epsilon;) : &#124; f(x) - `B` &#124; &lt; &epsilon;
- lim<sub style="font-size:50%">x &rarr; a</sub> f(x) = -&infin;
  * Cambia a f(x) &lt; -&epsilon;
- lim<sub style="font-size:50%">x &rarr; a</sub> f(x) = +&infin;
  * Cambia a f(x) &gt; &epsilon;

---

## Sucesi&oacute;n

- Funci&oacute;n en el dominio de los n&uacute;meros naturales
- x<sub style="font-size:50%">1</sub>, x<sub style="font-size:50%">2</sub>, ..., x<sub style="font-size:50%">n</sub>, ... 

---

## L&iacute;mite de una sucesi&oacute;n

- lim<sub style="font-size:50%">n &rarr; &infin;</sub> x<sub style="font-size:50%">n</sub> = `A`
  * &forall;&epsilon; &gt;`0` &exist;N(&epsilon;)
    + &forall; n &gt; N(&epsilon;) : &#124; x<sub style="font-size:50%">n</sub> - `B` &#124; &lt; &epsilon;

---

## L&iacute;mite de una funci&oacute;n constante

- Sean
   * `c` &isin; &real;
   * f(x) = `c`
- ... entonces
   * lim<sub style="font-size:50%">x &rarr; a</sub> f(x) = `c`

---

## L&iacute;mite vs cotas de la funci&oacute;n

- Sea
  * lim<sub style="font-size:50%">x &rarr; a</sub> f(x) = `A`
  * &exist;&epsilon;, `M`, `N` &isin; &real : &forall;x &isin; (`a` - &epsilon;, `a` + &epsilon;) `M` &lt; f(x) &lt; `N`
- ... entoncces
  * `M` &le; `A` &le; `N`

---

## Conservaci&oacute;n del signo

- Sean
  * `a`, `c`, x<sub style="font-size:50%">0</sub> &isin; &real; : `c` &gt; `0`
  * f: &real; &rarr; &real; una funci&oacute;n
  * lim<sub style="font-size:50%">x &rarr; x<sub style="font-size:50%">0</sub></sub> f(x) = `a`
- ... entonces &exist;c, &epsilon; &gt; `0`
  * si `a` &gt; 0 , &forall;x &isin; &#124; x - x<sub style="font-size:50%">0</sub> &#124; f(x) &gt; `c`
  * si `a` &lt; 0 , &forall;x &isin; &#124; x - x<sub style="font-size:50%">0</sub> &#124; f(x) &lt; `c`

---

## Convergencia

- Sean
  * &phi;(x) &le; f(x) &le; &psi;(x)
  * lim<sub style="font-size:50%">x &rarr; x<sub style="font-size:50%">0</sub></sub> &phi;(x) = lim<sub style="font-size:50%">x &rarr; x<sub style="font-size:50%">0</sub></sub> &psi;(x) = `a`
    + `a` puede ser -&infin; o +&infin;
- ... entonces
  * lim<sub style="font-size:50%">x &rarr; x<sub style="font-size:50%">0</sub></sub> f(x) = `a`

---

## Linearidad

- Sean
  * f(x), g(x)
  * Existen
    + lim<sub style="font-size:50%">x &rarr; x<sub style="font-size:50%">0</sub></sub> f(x)
    + lim<sub style="font-size:50%">x &rarr; x<sub style="font-size:50%">0</sub></sub> g(x)
- ... entonces
  * lim<sub style="font-size:50%">x &rarr; x<sub style="font-size:50%">0</sub></sub> f(x) + g(x) = lim<sub style="font-size:50%">x &rarr; x<sub style="font-size:50%">0</sub></sub> f(x) + lim<sub style="font-size:50%">x &rarr; x<sub style="font-size:50%">0</sub></sub> g(x)
  * lim<sub style="font-size:50%">x &rarr; x<sub style="font-size:50%">0</sub></sub> f(x) &middot; g(x) = lim<sub style="font-size:50%">x &rarr; x<sub style="font-size:50%">0</sub></sub> f(x) &middot; lim<sub style="font-size:50%">x &rarr; x<sub style="font-size:50%">0</sub></sub> g(x)
  * si lim<sub style="font-size:50%">x &rarr; x<sub style="font-size:50%">0</sub></sub> g(x) &ne; `0`

<table>
  <tr>
    <td style="vertical-align:middle; padding-left:0px; padding-right:0px">
      lim<sub style="font-size:50%">x &rarr; x<sub style="font-size:50%">0</sub></sub>
    </td>
    <td style="vertical-align: top; padding-left:0px; padding-right:0px">
      <table>
        <tr style="border-bottom: 1px solid white"><td>
f(x)
        </td></tr>
        <tr><td>
g(x)
        </td></tr>
      </table>
    </td>
    <td style="vertical-align: middle">=</td>
    <td style="vertical-align: top; padding-left:0px; padding-right:0px">
      <table>
        <tr style="border-bottom: 1px solid white"><td>
lim<sub style="font-size:50%">x &rarr; x<sub style="font-size:50%">0</sub></sub> f(x)
        </td></tr>
        <tr><td>
lim<sub style="font-size:50%">x &rarr; x<sub style="font-size:50%">0</sub></sub> g(x)
        </td></tr>
      </table>
    </td>
  </tr>
</table>

---

## L&iacute;mite de la composici&oacute;n de funciones

- Sean
  * x<sub style="font-size:50%">0</sub>, y<sub style="font-size:50%">0</sub> &isin; &real;
  * f, g : &real; &rarr; &real; funciones tales que
    + lim<sub style="font-size:50%">x &rarr; x<sub style="font-size:50%">0</sub></sub> f(x) = y<sub style="font-size:50%">0</sub>
    + existe lim<sub style="font-size:50%">y &rarr; y<sub style="font-size:50%">0</sub></sub> g(y)
- ... entonces
  * lim<sub style="font-size:50%">x &rarr; x<sub style="font-size:50%">0</sub></sub> g( f(x) ) = lim<sub style="font-size:50%">y &rarr; y<sub style="font-size:50%">0</sub></sub> g(y)

---

## Criterio de existencia Cauchy

- Sean
  * f: &real; &rarr; &real;
- es equivalente
  * f tiene l&iacute;mite finito en x &rarr; x<sub style="font-size:50%">0</sub>
  * &forall;&epsilon; &gt; `0` &exist;&delta; tal que
    + &forall;x', x'' &isin; (x<sub style="font-size:50%">0</sub> - &delta;, x<sub style="font-size:50%">0</sub> + &delta;) &#124; f(x'') - f(x') &#124; &lt; &epsilon;

---

## Funciones infinitamente peque&ntilde;as y grandes

- &alpha; : &real; &rarr; &real; es inifinitamente peque&ntilde;a para x &rarr; x<sub style="font-size:50%">0</sub>
  * lim<sub style="font-size:50%">x &rarr; x<sub style="font-size:50%">0</sub></sub> &alpha;(x) = `0`
  * infinitesimal
- &alpha; : &real; &rarr; &real; es inifinitamente grande para x &rarr; x<sub style="font-size:50%">0</sub>
  * lim<sub style="font-size:50%">x &rarr; x<sub style="font-size:50%">0</sub></sub> &alpha;(x) = &infin;
  * infinita

---

## L&iacute;mite vs infinitesimal

- Son equivalentes
  * lim<sub style="font-size:50%">x &rarr; x<sub style="font-size:50%">0</sub></sub> f(x) existe y es igual a `a`
  * f(x) = `a` + &alpha;(x) tal que
    - &alpha;(x) es infinitesimal para x &rarr; x<sub style="font-size:50%">0</sub>

---

## Propiedades de los infinitesimales

- Sean
  * &alpha;(x) y &beta;(x) son infinitesimales en x &rarr; x<sub style="font-size:50%">0</sub>
- ... entonces tambien son infinitesimales
  * &alpha;(x) + &beta;(x)
  * &alpha;(x) &middot; &beta;(x)

---

## Infinitesimales vs infinito

- Sea
  * f(x) una funci&oacute;n infinitamente grande en x &rarr; x<sub style="font-size:50%">0</sub>
- ... entonces es infinitesimal la funci&oacute;n

<table>
  <tr style="border-bottom: 2px solid white">
    <td style="text-align:center;">
1
    </td></tr>
    <tr><td>
f(x)
    </td>
  </tr>
</table>

<table>
  <tr>
    <td style="vertical-align: top; padding-left:0px; padding-right:0px">
      <table>
        <tr style="border-bottom: 2px solid white"><td>
`a`
        </td></tr>
        <tr><td>
`+0`
        </td></tr>
      </table>
    </td>
    <td style="vertical-align:middle; padding-left:0px">
      = +&infin;;
    </td>
    <td style="vertical-align: top; padding-left:0px; padding-right:0px">
      <table>
        <tr style="border-bottom: 2px solid white"><td>
`a`
        </td></tr>
        <tr><td>
`-0`
        </td></tr>
      </table>
    </td>
    <td style="vertical-align: middle"> = -&infin;;</td>
    </td>
    <td style="vertical-align: top; padding-left:0px; padding-right:0px">
      <table>
        <tr style="border-bottom: 2px solid white"><td>
`a`
        </td></tr>
        <tr><td>
`0`
        </td></tr>
      </table>
    </td>
    <td style="vertical-align: middle"> = &infin;</td>
  </tr>
</table>

<table>
  <tr>
    <td style="vertical-align: top; padding-left:0px; padding-right:0px">
      <table>
        <tr style="border-bottom: 2px solid white"><td>
`a`
        </td></tr>
        <tr><td>
      +&infin;
        </td></tr>
      </table>
    </td>
    <td style="vertical-align:middle; padding-left:0px">
= `+0`;
    </td>
    <td style="vertical-align: top; padding-left:0px; padding-right:0px">
      <table>
        <tr style="border-bottom: 2px solid white"><td>
`a`
        </td></tr>
        <tr><td>
-&infin;
        </td></tr>
      </table>
    </td>
    <td style="vertical-align: middle">
= `-0`;
    </td>
    <td style="vertical-align: top; padding-left:0px; padding-right:0px">
      <table>
        <tr style="border-bottom: 2px solid white"><td>
`a`
        </td></tr>
        <tr><td>
&infin;
        </td></tr>
      </table>
    </td>
    <td style="vertical-align: middle"> = `0`</td>
  </tr>
</table>

---

## L&iacute;mites notables

<table>
  <tr>
    <td style="vertical-align:middle; padding-left:0px">
      lim<sub style="font-size:50%">x &rarr; 0</sub>
    </td>
    <td style="vertical-align: top; padding-left:0px">
      <table>
        <tr style="border-bottom: 2px solid white">
          <td style="text-align:center">
sin x
          </td>
        </tr>
        <tr>
          <td style="text-align:center">
x
          </td>
        </tr>
      </table>
    </td>
    <td style="vertical-align:middle; padding-left:0px">
      = `1`
    </td>
  </tr>
</table>

<table>
  <tr>
    <td style="vertical-align:middle; padding-left:0px">
      lim<sub style="font-size:50%">x &rarr; 0</sub> (1 + x)
      <sup style="font-size:50%">1 / x</sup>
    </td>
    <td style="vertical-align:middle; padding-left:0px">
      = `e`
    </td>
  </tr>
</table>

---

## Continuidad de una funci&oacute;n

- Incremento infinitamente peque&ntilde;o del argumento
- Incremento infinitamente peque&ntilde;o de la funci&oacute;n
- lim<sub style="font-size:50%">x - x<sub style="font-size:50%">0</sub> &rarr; 0</sub> (f(x) - f(x<sub style="font-size:50%">0</sub>)) = `0`
- lim<sub style="font-size:50%">&Delta;x &rarr; 0</sub> &Delta;y = `0`

---

## Continuidad uniforme

---

## Propiedades de funciones continuas

- Son acotadas (Weierstrass)
- &forall;C : f(`a`) &lt; C &lt; f(`b`)
  * &exist; &xi; &isin; (`a`, `b`) : f(&xi;) = C

---

## Punto de discontinuidad

- Sea
  * x<sub style="font-size:50%">0</sub> &isin; &real;
  * f(x) definida en un entorno de x<sub style="font-size:50%">0</sub>
    + excepto, posiblemente, en el propio punto
- f no est&aacute; definida en x<sub style="font-size:50%">0</sub>
- f no es continua en x<sub style="font-size:50%">0</sub>

---

## Discontinuidad de primer g&eacute;nero

![Discontinuidad de 1er g&eacute;nero](../../img/lim_uni.png)

- f(x<sub style="font-size:50%">0</sub><sup style="font-size:50%">-</sup>) = lim<sub style="font-size:50%">x &rarr; x<sub style="font-size:50%">0</sub><sup style="font-size:50%">-</sup></sub> f(x)
- f(x<sub style="font-size:50%">0</sub><sup style="font-size:50%">+</sup>) = lim<sub style="font-size:50%">x &rarr; x<sub style="font-size:50%">0</sub><sup style="font-size:50%">+</sup></sub> f(x)
- Salto de la funci&oacute;n f en el punto x<sub style="font-size:50%">0</sub>
  * f(x<sub style="font-size:50%">0</sub><sup style="font-size:50%">+</sup>) - f(x<sub style="font-size:50%">0</sub><sup style="font-size:50%">-</sup>)
  * ... cuando es `0` , discontinuidad evitable 

---

## Discontinuidad de segundo g&eacute;nero

![Discontinuidad de 2do g&eacute;nero](../../img/hyperb.png)

---

## Comparaci&oacute;n de funciones

- Sean
  * f, g : &real; &rarr; &real;
  * x<sub style="font-size:50%">0</sub> &isin; &real;
- ... si existe
  * `c` &isin; &real;
  * un entorno U(x<sub style="font-size:50%">0</sub>) del punto x<sub style="font-size:50%">0</sub> tal que
    + &forall;x &isin; U(x<sub style="font-size:50%">0</sub>) : &#124; f(x) &#124; &le; `c` &middot; &#124; g(x) &#124;
- ... entonces f es acotada en comparaci&oacute;n con la funci&oacute;n g en el entorno de x<sub style="font-size:50%">0</sub>
  * f(x) = O(g(x)) , x &rarr; x<sub style="font-size:50%">0</sub>

---

## Funciones del mismo grado

- f = O(g)
- g = O(f)

<table>
  <tr>
    <td style="vertical-align:middle; padding-left:0px; padding-right:0px">
      lim<sub style="font-size:50%">x &rarr; x<sub style="font-size:50%">0</sub></sub>
    </td>
    <td style="vertical-align: top; padding-left:0px; padding-right:0px">
      <table>
        <tr style="border-bottom: 2px solid white"><td>
f(x)
        </td></tr>
        <tr><td>
g(x)
        </td></tr>
      </table>
    </td>
    <td style="vertical-align: middle">= `k` &ne; `0`</td>
  </tr>
</table>

- `k` = `1` : equivalentes

---

## Notaci&oacute;n **o**

- Sean
  * f, &alpha; : &real; &rarr; &real;
  * x<sub style="font-size:50%">0</sub> &isin; &real;
- ... si existe
  * &epsilon; : &real; &rarr; &real; infinitesimal para x &rarr; x<sub style="font-size:50%">0</sub>
  * un entorno U(x<sub style="font-size:50%">0</sub>) del punto x<sub style="font-size:50%">0</sub> tal que
    + &forall;x &isin; U(x<sub style="font-size:50%">0</sub>) : &alpha;(x) = &epsilon;(x) &middot; f(x)
- ... entonces &alpha; es infinitesimal en comparaci&oacute;n con la funci&oacute;n f en el entorno de x<sub style="font-size:50%">0</sub>
  * f(x) = o(g(x)) , x &rarr; x<sub style="font-size:50%">0</sub>

---

## As&iacute;ntotas

![As&iacute;ntota](../../img/asymp.png)

- Recta y = `k` x + `l` tal que
  * f(x) - `k` x - `l` = o(`1`)
- f(x) se comporta como una recta
  * x &rarr; +&infin; o x &rarr; -&infin;

---

## Relaci&oacute;n con l&iacute;mites

![As&iacute;ntota](../../img/asymp.png)

<table>
  <tr>
    <td style="vertical-align:middle; padding-left:0px; padding-right:0px">
      `k` = lim<sub style="font-size:50%">x &rarr; &infin;
    </td>
    <td style="vertical-align: top; padding-left:0px; padding-right:0px">
      <table>
        <tr style="border-bottom: 2px solid white"><td>
f(x)
        </td></tr>
        <tr>
          <td style="text-align: center">
x
          </td>
        </tr>
      </table>
    </td>
  </tr>
</table>

`l` = lim<sub style="font-size:50%">x &rarr; &infin;</sub> (f(x) - `k` x)

