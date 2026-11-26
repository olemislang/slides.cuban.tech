
# Movimiento rotacional

 F&iacute;sica &dash; Mec&aacute;nica

---

## Agenda

- Movimiento rotacional. Definici&oacute;n
- Cinem&aacute;tica de la rotaci&oacute;n
  * Variables de la rotaci&oacute;n. Naturaleza vectorial
  * Rotaci&oacute;n con aceleraci&oacute;n angular constante
  * Relaci&oacute;n entre las variables de traslaci&oacute;n y rotaci&oacute;n
- Din&aacute;mica de la rotaci&oacute;n
  * Torque. Inercia rotacional
  * Movimiento compuesto
- Momento angular
  * Conservaci&oacute;n del momento angular

---

## Movimiento compuesto

![Movimiento compuesto](../../img/complex_motion.png)

- Se puede descomponer en
  * traslaci&oacute;n de un punto fijo del cuerpo
  * rotaci&oacute;n de una l&iacute;nea de referencia
    + entre dos puntos fijos del cuerpo

---

## Rotaci&oacute;n pura

- Todos los puntos de un cuerpo se mueven en trayectorias circulares
- Los centros de estas circunferencias tienen que estar ubicados en una l&iacute;nea recta
  * eje de rotaci&oacute;n
- Todas las trayectorias perpendiculares al eje de rotaci&oacute;n
  * mismo &aacute;ngulo en los mismos intervalos de tiempo

--

## Rueda

![Rueda](../../img/wheel.png)

---

## Posici&oacute;n angular

![Posici&oacute;n angular](../../img/rot_pos.png)

- sentido positivo contrario al reloj
- &Phi; = s / r

---

## Desplazamiento angular

![Desplazamiento angular](../../img/rot_da.png)

- Velocidad angular
  * &omega; = lim<sub style="font-size:50%">&Delta;t &rarr; 0</sub> &Delta;&Phi; / &Delta;t = d&Phi;/dt
- Aceleraci&oacute;n angular
  * &alpha; = lim<sub style="font-size:50%">&Delta;t &rarr; 0</sub> &Delta;&omega; / &Delta;t = d&omega;/dt

--

## Aplicaciones sucesivas

![Desplazamientos angulares sucesivos](../../img/rot_da_novector.png)

- Desplazamiento angular &Delta;&Phi; no es un vector


--

## Desplazamiento angular infinitesimal

![Desplazamiento angular infinitesimal](../../img/rot_da_vector.png)

- Desplazamiento angular d&Phi; s&iacute; es un vector

---

## Velocidad angular (vector)

![Vector velocidad angular](../../img/rot_va_vector.png)

- Regla de la mano derecha

---

## Magnitudes angulares vs lineales

Rotaci&oacute;n pura. Cuerpo r&iacute;gido

![Magnitudes lineales vs angulares](../../img/rot_vs_linear.png)

- **v** = **&omega;** &times; **R**
- **a** = **a<sub style="font-size:50%">T</sub>** + **a<sub style="font-size:50%">R</sub>**
- **a<sub style="font-size:50%">T</sub>** = **&alpha;** &times; **R**
- **a<sub style="font-size:50%">R</sub>** = **&omega;** &times; **v**

---

## Comprendiendo el torque

![Torque vs aceleraci&oacute;n angular](../../img/torque_door.png)

- Aceleraci&oacute;n var&iacute;a seg&uacute;n
  * direcci&oacute;n de la fuerza
  * distancia desde el eje de rotaci&oacute;n

---

## Torque

![Torque](../../img/torque.png)

- Direcci&oacute;n fija del eje de rotac&oacute;n
  * **&tau;** = **r** &times; **F**
- L&iacute;nea de acci&oacute;n
- Brazo de la fuerza

--

## Torque (ejemplo)

![Torque de un p&eacute;ndulo](../../img/torque_pendulum.png)

- Fuerza de gravedad
- Se desprecia la masa de la cuerda
- El torque cambia de sentido mientras oscila

---

## Inercia rotacional (part&iacute;cula)

![Torque de una part&iacute;cula](../../img/rot_force.png)

- &tau;<sub style="font-size:50%">z</sub> = I &alpha;<sub style="font-size:50%">z</sub>
- I = m r<sup style="font-size:50%">2</sup>
  * Inercia rotacional
- Se deduce de la segunda ley de Newton

---

## Inercia rotacional (sistema de part&iacute;culas)

![Torque de una part&iacute;cula](../../img/rot_force_sys.png)

- &Sigma; &tau;<sub style="font-size:50%">z</sub> = I &alpha;<sub style="font-size:50%">z</sub>
- I = &Sigma; m<sub style="font-size:50%">i</sub> r<sub style="font-size:50%">i</sub><sup style="font-size:50%">2</sup>
  * Inercia rotacional

---

## Teorema de Huygens-Steiner

![Variacio&oacute;n seg&uacute;n el eje](../../img/rot_inertia_cm.png)

- I = I<sub style="font-size:50%">cm</sub> + Mh<sup style="font-size:50%">2</sup>
- I : con respecto a cualquier eje
- I<sub style="font-size:50%">cm</sub> : alrededor de un eje
  * paralelo
  * que pasa por el centro de masas

---

## Inercia rotacional de un s&oacute;lido r&iacute;gido

![Inercia rotacional de un cuerpo](../../img/rot_inertia_body.png)

- I = <span style="font-size:150%">&int;</span> r<sup style="font-size:50%">2</sup> dm

--

## Inercia rotacional (ejemplos)

Aro girando sobre su eje

![Varios ejemplos de inercia rotacional](../../img/rot_i_hoop_axis.png)

--

## Inercia rotacional (ejemplos)

Cilindro hueco o anillo girando sobre su eje

![Varios ejemplos de inercia rotacional](../../img/rot_i_cyl_axis.png)

--

## Inercia rotacional (ejemplos)

Cilindro s&oacute;lido girando sobre su eje

![Varios ejemplos de inercia rotacional](../../img/rot_i_bar_axis.png)

--

## Inercia rotacional (ejemplos)

Cilindro s&oacute;lido girando sobre su di&aacute;metro central

![Varios ejemplos de inercia rotacional](../../img/rot_i_bar_center.png)

--

## Inercia rotacional (ejemplos)

Barra fina girando sobre su di&aacute;metro central

![Varios ejemplos de inercia rotacional](../../img/rot_i_rod_center.png)

--

## Inercia rotacional (ejemplos)

Barra fina girando sobre un extremo

![Varios ejemplos de inercia rotacional](../../img/rot_i_rod_end.png)

--

## Inercia rotacional (ejemplos)

Esfera girando sobre un di&aacute;metro

![Varios ejemplos de inercia rotacional](../../img/rot_i_sphere.png)

--

## Inercia rotacional (ejemplos)

Esfera hueca o globo girando sobre un di&aacute;metro

![Varios ejemplos de inercia rotacional](../../img/rot_i_baloon.png)

--

## Inercia rotacional (ejemplos)

Aro girando sobre un di&aacute;metro

![Varios ejemplos de inercia rotacional](../../img/rot_i_hoop_diam.png)

--

## Inercia rotacional (ejemplos)

L&aacute;mina rect&aacute;ngular fina girando sobre su centro

![Varios ejemplos de inercia rotacional](../../img/rot_i_plate_rect.png)

---

## Movimiento compuesto (simple)

- Sistema de referencia inercial
- Hip&oacute;tesis sobre el eje de rotaci&oacute;n
  * pasa por el centro de masas
  * siempre mantiene la misma direcci&oacute;n
- Se descompone en dos movimientos independientes
  * Traslaci&oacute;n del centro de masas
  * Rotaci&oacute;n alrededor del eje

--

## An&aacute;lisis de un punto en una rueda

![Movimiento de una rueda](../../img/rot_ex_wheel.png)

--

## Instant&aacute;nea de la rotaci&oacute;n

![Movimiento de una rueda](../../img/rot_wheel_instant.png)

- Rotaci&oacute;n alrededor de un eje instant&aacute;neo
  * ... en el punto de contacto

---

## Momento angular

![Momento angular](../../img/rot_momentum.png)

- **l** = **r** &times; **p**
- **p** = m **v**

<table>
  <tr>
    <td style="vertical-align:middle;font-size: 150%; padding-left:0px; padding-right:0px">&Sigma;</td>
    <td style="vertical-align:middle; padding-left:0px; padding-right:0px">
      **&tau;** =
    </td>
    <td style="vertical-align: top; padding-left:0px; padding-right:0px">
      <table>
        <tr style="border-bottom: 1px solid white"><td>
d**l**
        </td></tr>
        <tr><td>
dt
        </td></tr>
      </table>
    </td>
  </tr>
</table>

---

## Momento angular (sistema de part&iacute;culas)

![Momento angular](../../img/rot_momentum.png)

- **l<sub style="font-size:50%">n</sub>** = **r**<sub style="font-size:50%">n</sub> &times; **p<sub style="font-size:50%">n</sub>**
- **L** = <span style="font-size:150%">&Sigma;</span> **l<sub style="font-size:50%">n</sub>**

<table>
  <tr>
    <td style="vertical-align:middle;font-size: 150%; padding-left:0px; padding-right:0px">&Sigma;</td>
    <td style="vertical-align:middle; padding-left:0px; padding-right:0px">
      **&tau;** =
    </td>
    <td style="vertical-align: top; padding-left:0px; padding-right:0px">
      <table>
        <tr style="border-bottom: 1px solid white"><td>
d**L**
        </td></tr>
        <tr><td>
dt
        </td></tr>
      </table>
    </td>
  </tr>
</table>

---

## Coordenadas en el centro de masas

- **L** = **R** &times; **P** + <span style="font-size:150%">&Sigma;</span><sub style="font-size:50%">i</sub> **r<sub style="font-size:50%">i</sub>** &times; **p<sub style="font-size:50%">i</sub>**
  * Respecto al sistema de coordenadas global
    + **L** : momento angular total del sistema de part&iacute;culas
    + **R** : posici&oacute;n del centro de masas respecto al sistema original
    + **P** : cantidad de movimiento de toda la masa concentrada en el centro de masas
  * Respecto al centro de masas
    + **r<sub style="font-size:50%">i</sub>** : posici&oacute;n de cada part&iacute;cula
    + **p<sub style="font-size:50%">i</sub>** : cantidad de movimiento de cada part&iacute;cula

---

## Influencia del torque en la rotaci&oacute;n

![Componentes del torque y momento angular](../../img/rot_momentum_vs_torque.png)

- Variaci&oacute;n de la magnitud del momento angular
- Cambio de direcci&oacute;n del eje de rotaci&oacute;n

---

## Rotaci&oacute;n de una part&iacute;cula

![Part&iacute;cula girando sobre eje fijo](../../img/rot_particle.png)

- Momento vs velocidad angular
  * no son paralelos
- Diferencia con el movimiento de desplazamiento
  * **v** siempre es paralelo a **p**

---

## Rotaci&oacute;n de dos part&iacute;culas

![Dos part&iacute;culas girando sobre eje fijo](../../img/rot_particles_2.png)

- Simetr&iacute;a de masas alrededor del eje 
- Momento y velocidad angular paralelos 
  * **L** = I **&omega;**
- Extensible a s&oacute;lido r&iacute;gido

---

## Conservaci&oacute;n del momento angular

- Hip&oacute;tesis
  * Toque externo neto sobre un sistema es nulo
- ... entonces
  * El momento angular se mantiene constante
- V&aacute;lido para cualquier componente del momento angular

--

## Conservaci&oacute;n del momento angular

Ejemplos 

![Atleta con pesos](../../img/rot_conserv_ma.png)

--

## Conservaci&oacute;n del momento angular

Ejemplos 

![Clavados](../../img/cliff_diving.png)

---

## Precesi&oacute;n

![Trompo](../../img/rot_spinning_top.png)

- Rotaci&oacute;n o desviaci&oacute;n de la direcci&oacute;n del eje
- Fuerzas externas (e.g. gravitacional)
- Componente perpendicular de **&tau;** respecto a **L**

---

## Cuerpo r&iacute;gido. Caso general

![Tensor de inercia](../../img/rot_inertia_tensor.webp)

- **L** = &image; **&omega;*
- &image; = <span style="font-size:125%">&Sigma;</span> m (( **R**<sup style="font-size:50%">T</sup> &middot; **R** ) **1** - **R** &middot; **R**<sup style="font-size:50%">T</sup> )
  * Tensor de inercia
  * **1** = matriz identidad

--

## Tensor de inercia

<table>
  <tr>
    <td style="vertical-align: middle;padding: 0px;">&image; =</td>
    <td style="font-size:550%; padding: 0px">(</td>
    <td style="padding: 0px;vertical-align: middle;">
      <table>
        <tr>
          <td>I<sub style="font-size:50%">xx</sub></td>
          <td>I<sub style="font-size:50%">xy</sub></td>
          <td>I<sub style="font-size:50%">xz</sub></td>
        </tr>
        <tr>
          <td>I<sub style="font-size:50%">yx</sub></td>
          <td>I<sub style="font-size:50%">yy</sub></td>
          <td>I<sub style="font-size:50%">yz</sub></td>
        </tr>
        <tr>
          <td>I<sub style="font-size:50%">zx</sub></td>
          <td>I<sub style="font-size:50%">zy</sub></td>
          <td>I<sub style="font-size:50%">zz</sub></td>
        </tr>
      </table>
    </td>
    <td style="font-size:550%; padding:0px">)</td>
  </tr>
</table>

- I<sub style="font-size:50%">xx</sub> = <span style="font-size:125%">&int;</span> (y<sup style="font-size:50%">2</sup> + z<sup style="font-size:50%">2</sup>) dm
- I<sub style="font-size:50%">yy</sub> = <span style="font-size:125%">&int;</span> (z<sup style="font-size:50%">2</sup> + x<sup style="font-size:50%">2</sup>) dm
- I<sub style="font-size:50%">zz</sub> = <span style="font-size:125%">&int;</span> (x<sup style="font-size:50%">2</sup> + y<sup style="font-size:50%">2</sup>) dm
- Productos de inercia
  * I<sub style="font-size:50%">xy</sub> = I<sub style="font-size:50%">yx</sub> = - <span style="font-size:125%">&int;</span> xy dm
  * I<sub style="font-size:50%">yz</sub> = I<sub style="font-size:50%">zy</sub> = - <span style="font-size:125%">&int;</span> yz dm
  * I<sub style="font-size:50%">zx</sub> = I<sub style="font-size:50%">xz</sub> = - <span style="font-size:125%">&int;</span> zx dm

---

## Propiedades del tensor de inercia

- Tensor de segundo orden
- &image; = &image;<sup style="font-size:50%">T</sup>
  * es sim&eacute;trico
- Depende (de las direcciones) del sistema de ccoordenadas
  * si est&aacute; ligado al cuerpo, no var&iacute;a en el tiempo
- Casos en que **L** es paralelo a **&omega;**
  * **&omega;** en direcci&oacute;n de un eje principal
  * dentro de un espacio degenerado equi-inercial

---

## Direcciones principales

- Para cualquier cuerpo y sistema de coordenadas
- Para (al menos) tres direcciones perpendiculares de **&omega;**
  * **L** = &lambda; **&omega;** (&lambda; &isin; &real;)
- Si las direcciones del sistema de coordenadas coincide con los ejes principales
  * Sean &lambda;<sub style="font-size:50%">1</sub>, &lambda;<sub style="font-size:50%">2</sub>, &lambda;<sub style="font-size:50%">3</sub> momentos de inercia principales
  * Tensor diagonal

<table>
  <tr>
    <td style="vertical-align: middle;padding: 0px;">&image; =</td>
    <td style="font-size:550%; padding: 0px">(</td>
    <td style="padding: 0px;vertical-align: middle;">
      <table>
        <tr>
          <td>&lambda;<sub style="font-size:50%">1</sub></td>
          <td>`0`</td>
          <td>`0`</td>
        </tr>
        <tr>
          <td>`0`</td>
          <td>&lambda;<sub style="font-size:50%">2</sub></td>
          <td>`0`</td>
        </tr>
        <tr>
          <td>`0`</td>
          <td>`0`</td>
          <td>&lambda;<sub style="font-size:50%">3</sub></td>
        </tr>
      </table>
    </td>
    <td style="font-size:550%; padding:0px">)</td>
  </tr>
</table>

--

## Curiosidades sobre ejes principales

- Momentos de inercia principales
  * dependen de la distribuci&oacute;n espacial de masas del cuerpo
  * son independientes del sistema de coordenadas
- Direcciones principales determinados para el centro de masas
  * Ejes de rotaci&oacute;n libre

--

## Ejes principales para cuerpos sim&eacute;tricos

- Si dos momentos principales de inercia coinciden
  * e.g. &lambda;<sub style="font-size:50%">1</sub> = &lambda;<sub style="font-size:50%">2</sub>
  * existen infinitos ejes principales
    + en el plano determinado por las direcciones principales correspondientes
    + perpendiculares a la tercera
  * cuerpos con simetr&iacute;a axial
- Direcciones principales de una esfera homogenea
  * cualquier eje que pase por su centro

--

## Elipsoide de inercia

![Elpisoide de inercia](../../img/rot_inertia_ellipsoid.png)

- Momento de inercia en la direcci&oacute;n **n** (I<sub style="font-size:50%">n</sub>)
- Sistema de coordenadas
  * Or&iacute;gen en el centro de masas
  * Direcciones principales: **n<sub style="font-size:50%">1</sub>**, **n<sub style="font-size:50%">2</sub>**, **n<sub style="font-size:50%">3</sub>**
- Semiejes del elipsoide &radic;<span style="border-top: 2px solid">1 / &lambda;<sub style="font-size:50%">1</sub></span>, &radic;<span style="border-top: 2px solid">1 / &lambda;<sub style="font-size:50%">2</sub></span>, &radic;<span style="border-top: 2px solid">1 / &lambda;<sub style="font-size:50%">3</sub></span>
- &rho;<sup style="font-size:50%">2</sup> = 1 / I<sub style="font-size:50%">n</sub>
- Elipsoide se parece al cuerpo

---

## Transformaci&oacute;n de coordenadas

- Sea
  * Q una matriz de transformaci&oacute;n ortonormal
    + i.e **r'** = Q **r**
- ... entonces
  * &image;' = Q &image; Q<sup style="font-size:50%">T</sup>

---

## Generalizaci&oacute;n del teorema de ejes paralelos

- I<sub style="font-size:50%">O</sub> = I<sub style="font-size:50%">CM</sub> + M ((**d**<sup style="font-size:50%">T</sup> &middot; **d**) **1** - **d** **d**<sup style="font-size:50%">T</sup>)
  * O : nuevo or&iacute;gen de coordenadas
  * I<sub style="font-size:50%">O</sub> : tensor de inercia en el sistema centrado en O
  * I<sub style="font-size:50%">CM</sub> : tensor de inercia respecto al centro de masas
  * M : masa total
  * **d** : vector posici&oacute;n del centro de masas respecto a O
  * **1** : matriz identidad

--

## Desplazamiento en el eje X

<table>
  <tr>
    <td style="vertical-align: middle;padding: 0px;">
      &image;<sub style="font-size:50%">O</sub> = &image;<sub style="font-size:50%">CM</sub> + M d<sup style="font-size:50%">2</sup>
    </td>
    <td style="font-size:550%; padding: 0px">(</td>
    <td style="padding: 0px;vertical-align: middle;">
      <table>
        <tr>
          <td>0</td>
          <td>0</td>
          <td>0</td>
        </tr>
        <tr>
          <td>0</td>
          <td>1</td>
          <td>0</td>
        </tr>
        <tr>
          <td>0</td>
          <td>0</td>
          <td>1</td>
        </tr>
      </table>
    </td>
    <td style="font-size:550%; padding:0px">)</td>
  </tr>
</table>

--

## Desplazamiento en el eje X y Y

- Sea **d** = (`a`, `b`, `0`)

<table>
  <tr>
    <td style="vertical-align: middle;padding: 0px;">
      &image;<sub style="font-size:50%">O</sub> = &image;<sub style="font-size:50%">CM</sub> + M 
    </td>
    <td style="font-size:550%; padding: 0px">(</td>
    <td style="padding: 0px;vertical-align: middle;">
      <table>
        <tr>
          <td style="text-align:right">`b`<sup style="font-size:50%">2</sup></td>
          <td style="text-align:right">-`a` `b`</td>
          <td style="text-align:right">0</td>
        </tr>
        <tr>
          <td style="text-align:right">-`a` `b`</td>
          <td style="text-align:right">`a`<sup style="font-size:50%">2</sup></td>
          <td style="text-align:right">0</td>
        </tr>
        <tr>
          <td style="text-align:right">0</td>
          <td style="text-align:right">0</td>
          <td style="text-align:right">
            `a`<sup style="font-size:50%">2</sup> + `b`<sup style="font-size:50%">2</sub>
          </td>
        </tr>
      </table>
    </td>
    <td style="font-size:550%; padding:0px">)</td>
  </tr>
</table>

---

## Equilibrio seg&uacute;n fuerza de gravedad

![Posiciones de equilibrio](../../img/rot_g_equilibrium.png)

- Centro de gravedad en la vertical bajo el punto de suspensi&oacute;n
- Si cuelga del centro de gravedad
  * siempre est&aacute; en equilibrio
  * rotaci&oacute;n libre

---

## Errores comunes con la rotaci&oacute;n

- Tratar el momento de inercia como un escalar en rotaci&oacute;n 3D arbitraria
- Asumir que **L** es siempre paralelo a **&omega;**
- Olvidar el signo de menos en I<sub style="font-size:50%">xy</sub> ...
- Pasar por alto la convenci&oacute;n del signo del producto de inercia
- Asumir autom&aacute;ticamente que todos los productos de inercia son cero
- Equivocaciones en el uso de la simetr&iacute;a para simplificar integrales con productos de coordenadas

--

## Errores comunes con la rotaci&oacute;n (cont.)

- Asumir que un tensor &image; diagonal asegura **L** | **&omega;** para todo **&omega;**
- Confundir una representaci&oacute;n diagonal con un tensor de inercia esf&eacute;rico con valores iguales
- Calcular el momento de inercia en una direcci&oacute;n sin normalizar el vector de direcci&oacute;n
- Olvidar que los componentes del tensor de inercia dependen de
  * el or&iacute;gen de coordenadas
  * la orientaci&oacute;n de los ejes

--

## Errores comunes con la rotaci&oacute;n (cont.)

- Aplicar el teorema del eje paralelo escalar cuando lo que procede es la transformaci&oacute;n del tensor
- Pasar por alto que el cambio del or&iacute;gen de coordenadas puede modificar entradas del tensor fuera de la diagonal
- Concluir que hay desplazamiento del centro de masas basado en productos de inercia no nulos
- Confundir el tensor de inercia con otros tensores
- Olvidar que el tensor de inercia es sim&eacute;trico

