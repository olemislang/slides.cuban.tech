
# C&aacute;lculo integral

An&aacute;lisis matem&aacute;tico

<small>Funciones reales de una sola variable</small>

---

## Agenda

- Particiones
- Sumas de Riemann
- Antiderivada e integral definida
- Teorema fundamental del c&aacute;lculo
- Teoremas del valor medio
- Consecuencias de los teoremas fundamentales
- Integrales indefinidas elementales

---

## Particiones (definici&oacute;n 1)

- Sea I un intervalo finito, una partici&oacute;n de I es un conjunto P finito tal que 
  * sus elementos son intervalos finitos contenidos en I
  * todo x &isin; I pertenece exactamente a uno de los intervalos en P.

---

## Particiones (definici&oacute;n 2)

- Sea I un intervalo finito `[a, b]`, una partici&oacute;n de I es un conjunto P finito tal que 
  * P = {<code>x<sub>0</sub></code>, <code>x<sub>1</sub></code>, ... , <code>x<sub>n</sub></code>}
  * `a` = <code>x<sub>0</sub></code> < <code>x<sub>1</sub></code> < ... < <code>x<sub>n-1</sub></code> < <code>x<sub>n</sub></code> = `b`

---

## Longitud de un intervalo

- Sea I un intervalo finito, se denota como &#124; I &#124;
- Si `a`, `b` &isin; &real; `a < b`
  * &#124; `(a, b)` &#124; = `b - a`
  * &#124; `(a, b]` &#124; = `b - a`
  * &#124; `[a, b)` &#124; = `b - a`
  * &#124; `[a, b]` &#124; = `b - a`
- Si I es un punto &#124; I &#124; = `0`
- Si I = &empty; , &#124; I &#124; = `0`

---

## Aditividad de la longitud

- Si
  * I es un intervalo finito
  * `n` es un n&uacute;mero natural
  * P es una partici&oacute;n de I de cardinalidad `n`
- entonces
  * &#124; I &#124; = &Sigma;<sub style="font-size:50%">J &isin; P</sub> &#124; J &#124;

---

## Sumas de Riemann

- Sea
  * f: I &rarr; &real; una funci&oacute;n acotada en un intervalo finito
  * P una partici&oacute;n de I
- Se define como
  * Suma superior de Riemann <br/> U(f, P) := &Sigma;<sub style="font-size:50%">J &isin; P:J &ne; &empty;</sub> (sup<sub style="font-size:50%">x &isin; J</sub> f(x))&middot;&#124; J &#124;
  * Suma inferior de Riemann <br/> L(f, P) := &Sigma;<sub style="font-size:50%">J &isin; P:J &ne; &empty;</sub> (inf<sub style="font-size:50%">x &isin; J</sub> f(x))&middot;&#124; J &#124;

---

## Criterio de integrabilidad de Riemann

- Sea
  * I un intervalo finito
  * f : I &rarr; &real; una funci&oacute;n acotada en I
  * Sea &weierp;(I) el conjunto de todas las particiones posibles en I
- Se considera que f es integrable seg&uacute;n el criterio de Riemann si
  * inf<sub style="font-size:50%">P &isin; &weierp;(I)</sub> U(f, P) = sup<sub style="font-size:50%">P &isin; &weierp;(I)</sub> L(f, P)
- Este valor se define como la integral de Riemann de la funci&oacute;n f y se denota por
  * &int;<sub style="font-size:50%">I</sub> f(x) dx
  * si I es el intervalo cerrado [`a`, `b`], &int;<sup style="font-size:50%">b</sup><sub style="font-size:50%">a</sub> f(x) dx

---

## Primer teorema valor medio (integrales)

- Sean
  * I = [`a`, `b`] un intervalo finito
  * f : [`a`, `b`] &rarr; &real; una funci&oacute;n integrable en [`a`, `b`] seg&uacute;n el criterio de Riemann
  * `M` = sup { f(x) : x &isin; [`a`, `b`] }
  * `m` = inf { f(x) : x &isin; [`a`, `b`] }
- ... entonces &exist;`c` &isin; &real; tal que:
  * `m` &le; `c` &le; `M`
  * &int;<sub style="font-size:50%">[a, b]</sub> f(x) dx = `c` (`b` - `a`)
- En particular, si f es continua en [`a`, `b`] entonces
  * &exist; x<sub style="font-size:50%">0</sub> &isin; [`a`, `b`] : `c` = f(x<sub style="font-size:50%">0</sub>)

---

## Segundo teorema valor medio (integrales)

- Sean
  * I = [`a`, `b`] un intervalo finito
  * f : [`a`, `b`] &rarr; &real; una funci&oacute;n
    + integrable en [`a`, `b`] seg&uacute;n el criterio de Riemann
    + monot&oacute;nica creciente
- ... entonces &exist; x<sub style="font-size:50%">0</sub> &isin; [`a`, `b`] tal que:
  * &int;<sub style="font-size:50%">[a, b]</sub> f(x) d&alpha;(x) = f(`a`) (x<sub style="font-size:50%">0</sub> - a) + f(`b`) (b - x<sub style="font-size:50%">0</sub>)

---

## Segundo teorema valor medio (Riemann)

- Sean
  * I = [`a`, `b`] un intervalo finito
  * f : [`a`, `b`] &rarr; &real; una funci&oacute;n monot&oacute;nica creciente
  * g : [`a`, `b`] &rarr; &real; una funci&oacute;n continua
  * `A`, `B` &isin; &real; tales que
    + `A` &le; f(`a`+)
    + `B` &ge; f(`b`-)
- ... entonces &exist;x<sub style="font-size:50%">0</sub> &isin; [`a`, `b`] tal que:
  * &int;<sub style="font-size:50%">[a, b]</sub> f(x) g(x) dx = `A` &int;<sub style="font-size:50%">[a, x<sub style="font-size:50%">0</sub>]</sub> g(x) dx + `B` &int;<sub style="font-size:50%">[x<sub style="font-size:50%">0</sub>, b]</sub> g(x) dx
- en particular, si &forall;x &isin; [`a`, `b`] f(x) &ge; `0` entonces
  * &int;<sub style="font-size:50%">[a, b]</sub> f(x) g(x) dx = `B` &int;<sub style="font-size:50%">[x<sub style="font-size:50%">0</sub>, b]</sub> g(x) dx

---

## Primer teorema fundamental del c&aacute;lculo

- Sean
  * `a`, `b` &isin; &real; : `a` < `b`
  * f : [`a`, `b`] &rarr; &real; una funci&oacute;n integrable seg&uacute;n el criterio de Riemann
  * F : [`a`, `b`] &rarr; &real; tal que F(x) := &int;<sub style="font-size:50%">[a, x]</sub> f
- entonces
  * F es continua en [`a`, `b`]
  * si x<sub style="font-size:50%">0</sub> &isin; [`a`, `b`] y f es continua en x<sub style="font-size:50%">0</sub>, entonces F es diferenciable en x<sub style="font-size:50%">0</sub> y F'(x<sub style="font-size:50%">0</sub>) = f(x<sub style="font-size:50%">0</sub>)

---

## Antiderivada

- Sea
  * I un intervalo finito
  * f : I &rarr; &real; una funci&oacute;n
- Se dice que la funci&oacute;n F : I &rarr; &real; es una antiderivada de f si
  * F es diferenciable en I
  * F'(x) = f(x) para todos los puntos l&iacute;mites x de I

---

## Ambig&uuml;edad de la antiderivada

- Sean
  * I un intervalo finito
  * f : I &rarr; &real; una funci&oacute;n
  * F : I &rarr; &real; y G : I &rarr; &real; dos antiderivadas de f
- ... entonces
  * &exist;C &isin; &real; : &forall;x &isin; I F(x) = G(x) + C

---

## Integrales indefinidas elementales

![Tabla de integrales indefinidas](../../img/integrals.jpg)

---

## Segundo teorema fundamental del c&aacute;lculo

- Sean
  * `a`, `b` &isin; &real; `a` &le; `b`
  * f : [`a`, `b`] &rarr; &real; una funci&oacute;n integrable seg&uacute;n el criterio de Riemann
  * F : [`a`, `b`] &rarr; &real; una antiderivada de f
- ... entonces
  * &int;<sub style="font-size:50%">[a, b]</sub>f = F(b) - F(a)

---

## Aditividad en intervalos contiguos

- Sean
  * [`a`, `c`] un intervalo finito
  * `b` &isin; &real; : `a` < `b` < `c`
  * f : [`a`, `c`] &rarr; &real; una funci&oacute;n integrable en [`a`, `c`] seg&uacute;n el criterio de Riemann
- ... entonces
  * &int;<sub style="font-size:50%">[a, b]</sub> f + &int;<sub style="font-size:50%">[b, c]</sub> f  = &int;<sub style="font-size:50%">[a, c]</sub> f

---

## Linearidad
Integraci&oacute;n por descomposici&oacute;n

- Sean
  * [`a`, `b`] un intervalo finito
  * `c` &isin; &real;
  * f : [`a`, `b`] &rarr; &real; y g : [`a`, `b`] &rarr; &real; dos funciones integrables en [`a`, `b`] seg&uacute;n el criterio de Riemann
- ... entonces
  * &int;<sub style="font-size:50%">[a, b]</sub> (f + g) = &int;<sub style="font-size:50%">[a, b]</sub> f + &int;<sub style="font-size:50%">[a, b]</sub> g
  * &int;<sub style="font-size:50%">[a, b]</sub> c f = c &int;<sub style="font-size:50%">[a, b]</sub> f

---

## Integraci&oacute;n por partes

- Sean
  * I = [`a`, `b`] un intervalo finito
  * F : I &rarr; &real; y G : I &rarr; &real; funciones
    +  derivables en I
    + integrables en I seg&uacute;n criterio de Riemann
- ... entonces
  * &int;<sub style="font-size:50%">[a, b]</sub> F G' = F(b) G(b) - F(a) G(a) - &int;<sub style="font-size:50%">[a, b]</sub> F' G
- ... o lo que es lo mismo
  * &int;<sub style="font-size:50%">[a, b]</sub> F G' = (F(x) G(x))&#124;<sup style="font-size:30%">b</sup><sub style="font-size:30%">a</sub> - &int;<sub style="font-size:50%">[a, b]</sub> F' G

---

## Cambio de variable
Integraci&oacute;n por sustitu&oacute;n

- Sean
  * I = [`a`, `b`] un intervalo finito
  * &Phi; : [`a`, `b`] &rarr; [&Phi;(`a`), &Phi;(`b`)] una funci&oacute;n continua y mon&oacute;tona creciente
  * f : [&Phi;(`a`), &Phi;(`b`)] &rarr; &real; una funci&oacute;n integrable en [&Phi;(`a`), &Phi;(`b`)] seg&uacute;n el criterio de Riemann
- ... entonces
  * f &ordm; &Phi; : [`a`, `b`] &rarr; &real; es integrable seg&uacute;n criterio de Riemann en [`a`, `b`]
  * &int;<sub style="font-size:50%">[a, b]</sub> f &ordm; &Phi; d&Phi; = &int;<sub style="font-size:50%">[&Phi;(a), &Phi;(b)]</sub> f

---

## Cambio de variable (alt.)

- Sean
  * I = [`a`, `b`] un intervalo finito
  * &Phi; : [`a`, `b`] &rarr; [&Phi;(`a`), &Phi;(`b`)] una funci&oacute;n diferenciable y mon&oacute;tona creciente, tal que
    + &Phi;' es integrable seg&uacute;n criterio de Riemann
  * f : [&Phi;(`a`), &Phi;(`b`)] &rarr; &real; una funci&oacute;n integrable en [&Phi;(`a`), &Phi;(`b`)] seg&uacute;n el criterio de Riemann
- ... entonces
  * (f &ordm; &Phi;) &Phi;' : [`a`, `b`] &rarr; &real; es integrable en [`a`, `b`] seg&uacute;n criterio de Riemann 
  * &int;<sub style="font-size:50%">[a, b]</sub> (f &ordm; &Phi;) &Phi;' = &int;<sub style="font-size:50%">[&Phi;(a), &Phi;(b)]</sub> f

---

## Producto de funciones

- Sean
  * I = [`a`, `b`] un intervalo finito
  * f : [`a`, `b`] &rarr; &real; y g : [`a`, `b`] &rarr; &real; dos funciones integrables en [`a`, `b`] seg&uacute;n el criterio de Riemann
  * F : [`a`, `b`] &rarr; &real; : F(x) = &int;<sub style="font-size:50%">[a, x]</sub> f(t) dt
  * G : [`a`, `b`] &rarr; &real; : G(x) = &int;<sub style="font-size:50%">[a, x]</sub> g(t) dt
- ... entonces
  * &int;<sub style="font-size:50%">[a, b]</sub> f(x) g(x) dx = &int;<sub style="font-size:50%">[a, b]</sub> f(x) dG(x) = &int;<sub style="font-size:50%">[a, b]</sub> g(x) dF(x)

---

## Integraci&oacute;n de fracciones algebraicas

- Sean N(x) y D(x) dos polinomios se trata de calcular

<table>
  <tr>
    <td style="font-size: 250%; padding-left:0px; padding-right:0px">&int;</td>
    <td style="vertical-align: top; padding-left:0px; padding-right:0px">
      <table>
        <tr style="border-bottom: 1px solid white"><td>
N(x)
        </td></tr>
        <tr><td>
D(x)
        </td></tr>
      </table>
    </td>
    <td style="vertical-align: middle; padding-left:0px; padding-right:0px">dx</td>
  </tr>
</table>

- Para denominador de grado 2 se reduce a

<table>
  <tr>
    <td style="font-size: 250%; padding-left:0px; padding-right:0px">&int;</td>
    <td style="vertical-align: middle; padding-left:0px; padding-right:0px">Q(x) + </td>
    <td style="font-size: 250%; padding-left:0px; padding-right:0px">&int;</td>
    <td style="vertical-align: top; padding-left:0px; padding-right:0px">
      <table>
        <tr style="border-bottom: 1px solid white"><td>
`m` x + `n`
        </td></tr>
        <tr><td>
`a` x<sup style="font-size: 50%">2</sup> + `b` x + `c`
        </td></tr>
      </table>
    </td>
    <td style="vertical-align: middle; padding-left:0px; padding-right:0px">dx</td>
  </tr>
</table>
- ... donde
  * Q(x) es el polinomio cociente de la divisi&oacute;n
  * `a`, `b`, `c`, `m`, `n` &isin; &real;

---

## Integraci&oacute;n de fracciones algebraicas (cont.)

- Se puede reescribir como

<table>
  <tr>
    <td style="vertical-align: top; padding-left:0px; padding-right:0px">
      <table>
        <tr style="border-bottom: 1px solid white"><td>
1
        </td></tr>
        <tr><td>
`a`
        </td></tr>
      </table>
    </td>
    <td style="font-size: 250%; padding-left:0px; padding-right:0px">(</td>
    <td style="vertical-align: middle; padding-left:0px; padding-right:0px">`m` F(x) + `n` G(x)</td>
    <td style="font-size: 250%; padding-left:0px; padding-right:0px">)</td>
  </tr>
</table>

---

## Integraci&oacute;n de fracciones algebraicas (cont.)

- ... con F(x)

<table>
  <tr>
    <td style="vertical-align: top; padding-left:0px; padding-right:0px">
    <td style="font-size: 450%; padding-left:0px; padding-right:0px">&int;</td>
    <td style="vertical-align: top; padding-left:0px; padding-right:0px">
      <table>
        <tr style="border-bottom: 1px solid white">
          <td></td>
          <td></td>
          <td></td>
          <td style="align: center">
x
          </td>
          <td>dx</td>
        </tr>
        <tr>
          <td style="font-size: 250%; padding-left:0px; padding-right:0px">(</td>
          <td style="vertical-align: middle; padding-left:0px; padding-right:0px">
x +
          </td>
          <td style="vertical-align: top; padding-left:0px; padding-right:0px">
            <table>
              <tr style="border-bottom: 1px solid white"><td>
`b`
              </td></tr>
              <tr><td>
`2 a`
              </td></tr>
            </table>
          </td>
          <td style="font-size: 250%; padding-left:0px; padding-right:0px">
            )<sup style="vertical-align:top;font-size: 20%">2</sup></td>
          <td style="vertical-align: middle">
+
          </td>
          <td style="vertical-align: top; padding-left:0px; padding-right:0px">
            <table>
              <tr style="border-bottom: 1px solid white"><td>
`c`
              </td></tr>
              <tr><td>
`a`
              </td></tr>
            </table>
          </td>
          <td style="vertical-align: middle">
-
          </td>
          <td style="vertical-align: top; padding-left:0px; padding-right:0px">
            <table>
              <tr style="border-bottom: 1px solid white"><td>
`b`<sup style="font-size: 30%">2</sup></td>
              </td></tr>
              <tr><td>
`4 a`<sup style="font-size: 30%">2</sup></td>
              </td></tr>
            </table>
          </td>
        </tr>
      </table>
    </td>
  </tr>
</table>

- ... y G(x)

<table>
  <tr>
    <td style="vertical-align: top; padding-left:0px; padding-right:0px">
    <td style="font-size: 450%; padding-left:0px; padding-right:0px">&int;</td>
    <td style="vertical-align: top; padding-left:0px; padding-right:0px">
      <table>
        <tr style="border-bottom: 1px solid white">
          <td></td>
          <td></td>
          <td></td>
          <td>dx</td>
        </tr>
        <tr>
          <td style="font-size: 250%; padding-left:0px; padding-right:0px">(</td>
          <td style="vertical-align: middle; padding-left:0px; padding-right:0px">
x +
          </td>
          <td style="vertical-align: top; padding-left:0px; padding-right:0px">
            <table>
              <tr style="border-bottom: 1px solid white"><td>
`b`
              </td></tr>
              <tr><td>
`2 a`
              </td></tr>
            </table>
          </td>
          <td style="font-size: 250%; padding-left:0px; padding-right:0px">
            )<sup style="vertical-align:top;font-size: 20%">2</sup></td>
          <td style="vertical-align: middle">
+
          </td>
          <td style="vertical-align: top; padding-left:0px; padding-right:0px">
            <table>
              <tr style="border-bottom: 1px solid white"><td>
`c`
              </td></tr>
              <tr><td>
`a`
              </td></tr>
            </table>
          </td>
          <td style="vertical-align: middle">
-
          </td>
          <td style="vertical-align: top; padding-left:0px; padding-right:0px">
            <table>
              <tr style="border-bottom: 1px solid white"><td>
`b`<sup style="font-size: 30%">2</sup></td>
              </td></tr>
              <tr><td>
`4 a`<sup style="font-size: 30%">2</sup></td>
              </td></tr>
            </table>
          </td>
        </tr>
      </table>
    </td>
  </tr>
</table>

---

## Integrales &uacute;tiles

<table>
  <tr>
    <td style="font-size: 250%; padding-left:0px; padding-right:0px">&int;</td>
    <td style="vertical-align: top; padding-left:0px; padding-right:0px">
      <table>
        <tr style="border-bottom: 2px solid white">
          <td style="text-align: center">
dx
          </td>
        </tr>
        <tr><td>
x<sup style="font-size: 50%">2</sup>
        </td></tr>
      </table>
    </td>
    <td style="vertical-align: middle; padding-left:0px; padding-right:0px">
      = -
    </td>
    <td style="vertical-align: top; padding-left:0px; padding-right:0px">
      <table>
        <tr style="border-bottom: 2px solid white">
          <td style="text-align: center">
`1`
          </td>
        </tr>
        <tr><td>
x
        </td></tr>
      </table>
    </td>
    <td style="vertical-align: middle; padding-left:0px; padding-right:0px">
+ C
    </td>
  </tr>
</table>

<table>
  <tr>
    <td style="font-size: 250%; padding-left:0px; padding-right:0px">&int;</td>
    <td style="vertical-align: top; padding-left:0px; padding-right:0px">
      <table>
        <tr style="border-bottom: 2px solid white">
          <td style="text-align: center">
x
          </td>
        </tr>
        <tr><td>
x<sup style="font-size: 50%">2</sup> &plusmn; `a`<sup style="font-size: 50%">2</sup>
        </td></tr>
      </table>
    </td>
    <td style="vertical-align: middle; padding-left:0px; padding-right:0px">
      dx = &frac12; ln &#124; x<sup style="font-size: 50%">2</sup> &plusmn; `a`<sup style="font-size: 50%">2</sup> &#124; + C
    </td>
  </tr>
</table>

<table>
  <tr>
    <td style="font-size: 250%; padding-left:0px; padding-right:0px">&int;</td>
    <td style="vertical-align: top; padding-left:0px; padding-right:0px">
      <table>
        <tr style="border-bottom: 2px solid white">
          <td style="text-align: center">
dx
          </td>
        </tr>
        <tr><td>
x<sup style="font-size: 50%">2</sup> + `a`<sup style="font-size: 50%">2</sup>
        </td></tr>
      </table>
    </td>
    <td style="vertical-align: middle">
      =
    </td>
    <td style="vertical-align: top; padding-right:0px">
      <table>
        <tr style="border-bottom: 2px solid white">
          <td style="text-align: center">
`1`
          </td>
        </tr>
        <tr><td>
`a`
        </td></tr>
      </table>
    </td>
    <td style="vertical-align: middle; padding-right:0px">
arctg
    </td>
    <td style="font-size:250%; padding-left:0px; padding-right:0px">
(
    </td>
    <td style="vertical-align: top; padding-left:0px; padding-right:0px">
      <table>
        <tr style="border-bottom: 2px solid white">
          <td style="text-align: center">
x
          </td>
        </tr>
        <tr><td>
`a`
        </td></tr>
      </table>
    </td>
    <td style="font-size:250%; padding-left:0px; padding-right:0px">
)
    </td>
    <td style="vertical-align: middle; padding-left:0px; padding-right:0px">
+ C
    </td>
  </tr>
</table>

<table>
  <tr>
    <td style="font-size: 250%; padding-left:0px; padding-right:0px">&int;</td>
    <td style="vertical-align: top; padding-left:0px; padding-right:0px">
      <table>
        <tr style="border-bottom: 2px solid white">
          <td style="text-align: center">
dx
          </td>
        </tr>
        <tr><td>
x<sup style="font-size: 50%">2</sup> - `a`<sup style="font-size: 50%">2</sup>
        </td></tr>
      </table>
    </td>
    <td style="vertical-align: middle">
      =
    </td>
    <td style="vertical-align: top; padding-right:0px">
      <table>
        <tr style="border-bottom: 2px solid white">
          <td style="text-align: center">
`1`
          </td>
        </tr>
        <tr><td>
`2 a`
        </td></tr>
      </table>
    </td>
    <td style="vertical-align: middle; padding-right:0px">
ln
    </td>
    <td style="font-size:250%; padding-left:0px; padding-right:0px">
&#124;
    </td>
    <td style="vertical-align: top; padding-left:0px; padding-right:0px">
      <table>
        <tr style="border-bottom: 2px solid white">
          <td style="text-align: center">
x - `a`
          </td>
        </tr>
        <tr><td>
x + `a`
        </td></tr>
      </table>
    </td>
    <td style="font-size:250%; padding-left:0px; padding-right:0px">
&#124;
    </td>
    <td style="vertical-align: middle; padding-left:0px; padding-right:0px">
+ C
    </td>
  </tr>
</table>

---

## Integrales incalculables

- No pueden ser expresadas mediante un n&uacute;mero finito de operaciones que involucren funciones elementales
- Ejemplos

<span style="font-size:150%">&int;</span> e<sup style="font-size:70%">-x<sup style="font-size:70%">2</sup></sup> dx

<table>
  <tr>
    <td style="font-size: 250%; padding-left:0px; padding-right:0px">&int;</td>
    <td style="vertical-align: top; padding-left:0px; padding-right:0px">
      <table>
        <tr style="border-bottom: 1px solid white"><td>
sin x
        </td></tr>
        <tr><td style="text-align: center">
x
        </td></tr>
      </table>
    </td>
    <td style="vertical-align: middle; padding-left:0px; padding-right:0px">dx</td>
  </tr>
</table>

<table>
  <tr>
    <td style="font-size: 250%; padding-left:0px; padding-right:0px">&int;</td>
    <td style="vertical-align: top; padding-left:0px; padding-right:0px">
      <table>
        <tr style="border-bottom: 1px solid white"><td>
cos x
        </td></tr>
        <tr><td style="text-align: center">
x
        </td></tr>
      </table>
    </td>
    <td style="vertical-align: middle; padding-left:0px; padding-right:0px">dx</td>
  </tr>
</table>

<table>
  <tr>
    <td style="font-size: 250%; padding-left:0px; padding-right:0px">&int;</td>
    <td style="vertical-align: top; padding-left:0px; padding-right:0px">
      <table>
        <tr style="border-bottom: 1px solid white">
          <td style="text-align: center">
dx
        </td></tr>
        <tr><td style="text-align: center">
ln &#124; x &#124;
        </td></tr>
      </table>
    </td>
  </tr>
</table>



