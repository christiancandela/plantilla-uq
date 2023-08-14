---
marp: true
header: <div class="encabezado"><img src='franjaSuperior.png'  /><div class="titulo"><h1 class="texto"></h1></div></div>
footer: '![image](franjaInferior.png)' 
_header: '' 
_footer: '' 
paginate: true
_paginate: false
_backgroundImage: url('fondo.png')
style: |

  .encabezado {
    position: relative; left: 0; top:0;display: inline-block; text-align: center;
  }
  .titulo {
    position: absolute; top: 40%; left: 50%; transform: translate(0%, -50%); color: gray;
  }
  .columns {
    display: grid;
    grid-template-columns: repeat(2, minmax(0, 1fr));
    gap: 1rem;
  }
  .rows {
    display: grid;
    grid-template-rows: repeat(2, minmax(0, 1fr));
    gap: 1rem;
  }
  .texto:after {
    content: 'Titulo';
  }
  
  h1 { color: gray }
---

<div style="position: absolute; left: 45%; top:20%; background-color: rgb(212, 231, 205); width: 550px; display:table-cell; text-align: center; padding: 30px 0;">
<b>
<h2>OTRO TITULO</h2>
</b>
</div>

<div style="position: absolute; left: 30%; top:45%; width: 70%; text-align: left"><h1 style="color: gray">TITULO PRESENTACION</h1></div>
<div style="position: absolute; left: 30%; top:55%; width: 70%; text-align: left"><h5 style="color: gray">Autor</h5></div>

<div style="position: absolute; left: 93%; top:10px; ">

![width:80](licencia.png)
</div>

---

<!-- 
_header: ''
_footer: ''
-->

![bg](fondo.png)

<div style="position: absolute; left: 45%; top:20%; background-color: rgb(212, 231, 205); width: 550px; display:table-cell; text-align: center; padding: 30px 0;">
<b>
<h2>OTRO TITULO</h2>
</b>
</div>

<div style="position: absolute; left: 30%; top:45%; width: 70%; text-align: left"><h1 style="color: gray">TITULO PRESENTACION</h1></div>
<div style="position: absolute; left: 30%; top:55%; width: 70%; text-align: left"><h5 style="color: gray">Autor</h5></div>

<div style="position: absolute; left: 93%; top:10px; ">

![width:80](licencia.png)
</div>

---


<!-- 
_header: ''
_footer: ''
-->

![bg](fondo.png)

<div style="position: absolute; left: 45%; top:20%; background-color: rgb(212, 231, 205); width: 550px; display:table-cell; text-align: center; padding: 30px 0;">
<b><h2>OTRO TITULO</h2></b>
</div>

<div style="position: absolute; left: 30%; top:45%; width: 70%; text-align: left"><h1 style="color: gray">TITULO PRESENTACION</h1></div>
<div style="position: absolute; left: 30%; top:55%; width: 70%; text-align: left"><h5 style="color: gray">Autor</h5></div>

<div style="position: absolute; left: 93%; top:10px; ">

![width:80](licencia.png)
</div>

---

<style scoped>
.texto:after {
    content: 'Titulo temporal';
  }
</style>

## Prueba 0

---

<style >
.texto:after {
    content: 'Fijanfo un Titulo';
  }
</style>

## Prueba 1

---

<style scoped>
.texto:after {
    content: 'Imagen flotante';
  }
</style>


## Imagen flotante

- uno
- dos
- tres
- cuatro
- cinco
- seis
- ocho

<div style="position: absolute; left: 50%; top:140px; ">

![](imagen.png)
</div>

---

<style >
.texto:after {
    content: 'Dos columnas con texto a la derecha';
  }
</style>


<div class="columns">
  <div>

  ![](imagen.png)
  </div>
  <div>

  ## Dos columnas con texto a la derecha

  - 1
  - 2

  </div>
</div>

---

<style >
.texto:after {
    content: 'Dos columnas con texto a la izquierda';
  }
</style>

<div class="columns">
  <div>

  ## Dos columnas con texto a la izquierda

  - puedad  ds fadfas df f sfa sdf asdf asd f dfa sdf asdf sf s dfas df s fd sdfa sfsadf 
  - 2

  </div>
  <div>

  ![](imagen.png)

  </div>
</div>


---

<div style="position: absolute; left: 0; top:35%; background-color: rgb(212, 231, 205); width: 100%; display:table-cell; text-align: center; padding: 30px 0;">
<b>
<h1>SUB TITULO</h1>
</b>
</div>

---
<style >
.texto:after {
    content: 'Dos filas, tres columnas';
  }
</style>

<div class="rows">
  <div class="columns" style="grid-template-columns: repeat(3, minmax(0, 1fr));">
  <div>
  
   - Col 1
  </div>
  <div>
  
   - Col 2
  </div>
  <div>
  
   - Col 3
  </div>
  </div>
  <div class="columns" style="grid-template-columns: repeat(3, minmax(0, 1fr));">
  <div>

  ![height:200](imagen.png)
  </div>
  <div>

  ![height:200](imagen.png)
  </div>
  <div>

  ![height:200](imagen.png)
  </div>
  </div>
</div>

---

<!-- 
_header: ''
_footer: '' 
_paginate: false
-->
![bg](gracias.png)


---

<!-- 
_header: ''
_footer: '' 
_paginate: false
_backgroundImage: url('gracias.png')
-->
