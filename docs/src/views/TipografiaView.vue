<template>
  <h1>Tipografia</h1>
  <div class="contenedor ancho-lectura contenedor-izq">
    <p>Todas las tipografías se calculan en <b>rem</b> para que al momento de cambiar el tamaño de la tipograía a la raiz, todos crezcan manteniendo la relación jerárquica del tamaño.</p>
  </div>
  
  <h2 class="m-t-10">Titulos</h2>
  <div class="contenedor ancho-lectura contenedor-izq">
    <p>Para todas las etiquetas de heading y clases de titulos y subtitlos el interlineado se mantiene de 1.25em y el peso de la tipografia es medium (500).</p>
  </div>
  <div class="flex" style="align-items: flex-start;">
    <div class="columna-2 sombra-profundidad-2 m-y-1 texto-centrado"> <h1>h1</h1> </div>
    <div class="columna-2">
      <p>2.25rem<br>36px</p>
    </div>
  
    <div class="columna-2 sombra-profundidad-2 m-y-1 texto-centrado"> <h2>h2</h2> </div>
    <div class="columna-2">
      <p>2rem<br>32px</p>
    </div>
    
    <div class="columna-2 sombra-profundidad-2 m-y-1 texto-centrado"> <h3>h3</h3> </div>
    <div class="columna-2">
      <p>1.75rem<br>28px</p>
    </div>
   
    <div class="columna-2 sombra-profundidad-2 m-y-1 texto-centrado"> <h4>h4</h4> </div>
    <div class="columna-2">
      <p>1.5rem<br>24px</p>
    </div>
   
    <div class="columna-2 sombra-profundidad-2 m-y-1 texto-centrado"> <h5>h5</h5> </div>
    <div class="columna-2">
      <p>1.25rem<br>20px</p>
    </div>
 
    <div class="columna-2 sombra-profundidad-2 m-y-1 texto-centrado"> <h6>h6</h6> </div>
    <div class="columna-2">
      <p>1rem<br>16px</p>
    </div>
  </div>

  <h2 class="m-t-10">Titulos especiales (responsivos)</h2>
  <div class="contenedor ancho-lectura contenedor-izq">
    <p>Las clases especiales de titulos funcionan sobre cualquier etiqueta. Es importante mantener el ordenen de los headings <code>h1 ... h6</code> por buenas prácticas de código, para mejorar el posicionamiento orgánico y por accesibilidad.</p>
    <p>Tienen dos tamaños que se formatean automaticamente con el breakpoint del sistema de diseño, lo único que se necesita es poner la clase</p>
  </div>
  <div class="flex" style="align-items: flex-start;">
    <div class="columna-8 sombra-profundidad-2 m-y-1 texto-centrado"> <p class="titulo-eni">titulo eni</p> </div>
    <div class="columna-2">
      <p><b>Celular</b><br> 3rem <br> 48px</p>
    </div>
    <div class="columna-2">
      <p><b>Escritorio</b><br> 5rem <br> 80px</p>
    </div>
    <div class="columna-4">
<pre class="m-x--1">
  &lt; p class="titulo-eni">
    titulo eni
  &lt;/ p>
</pre>
    </div>
 
    <div class="columna-8 sombra-profundidad-2 m-y-1 texto-centrado"> <p class="titulo-capitulo">titulo capitulo</p> </div>
    <div class="columna-2">
      <p><b>Celular</b><br> 2.25rem <br> 36px</p>
    </div>
    <div class="columna-2">
      <p><b>Escritorio</b><br> 3.5rem <br> 56px</p>
    </div>
    <div class="columna-4">
<pre class="m-x--1">
  &lt; p class="titulo-capitulo">
    titulo capitulo
  &lt;/ p>
</pre>
    </div>

    <div class="columna-8 sombra-profundidad-2 m-y-1 texto-centrado"> <p class="subtitulo-capitulo">subtitulo capitulo</p> </div>
    <div class="columna-2">
      <p><b>Celular</b><br> 1.125rem <br> 18px</p>
    </div>
    <div class="columna-2">
      <p><b>Escritorio</b><br> 1.5rem <br> 24px</p>
    </div>
    <div class="columna-4">
<pre class="m-x--1">
  &lt; p class="subtitulo-capitulo">
    subtitulo capitulo
  &lt;/ p>
</pre>
    </div>
  
    <div class="columna-8 sombra-profundidad-2 m-y-1 texto-centrado"> <p class="titulo-pagina">titulo pagina</p> </div>
    <div class="columna-2">
      <p><b>Celular</b><br> 1.75rem <br> 28px</p>
    </div>
    <div class="columna-2">
      <p><b>Escritorio</b><br> 2.25rem <br> 36px</p>
    </div>
    <div class="columna-4">
<pre class="m-x--1">
  &lt; p class="titulo-pagina">
    titulo pagina
  &lt;/ p>
</pre>
    </div>
 
    <div class="columna-8 sombra-profundidad-2 m-y-1 texto-centrado"> <p class="subtitulo-pagina">subtitulo pagina</p> </div>
    <div class="columna-2">
      <p><b>Celular</b><br> 1.125rem <br> 18px <br> Regular (400) </p>
    </div>
    <div class="columna-2">
      <p><b>Escritorio</b><br> 1.5rem <br> 24px <br> Regular (400) </p>
    </div>
    <div class="columna-4">
<pre class="m-x--1">
  &lt; p class="subtitulo-pagina">
    subtitulo pagina
  &lt;/ p>
</pre>
    </div>
  
    <div class="columna-8 sombra-profundidad-2 m-y-1 texto-centrado"> <p class="titulo-seccion">titulo seccion</p> </div>
    <div class="columna-2">
      <p><b>Celular</b><br> 1.125rem <br> 18px </p>
    </div>
    <div class="columna-2">
      <p><b>Escritorio</b><br> 1.5rem <br> 24px </p>
    </div>
    <div class="columna-4">
<pre class="m-x--1">
  &lt; p class="titulo-seccion">
    titulo seccion
  &lt;/ p>
</pre>
    </div>
  
    <div class="columna-8 sombra-profundidad-2 m-y-1 texto-centrado"> <p class="titulo-subseccion">titulo subseccion</p> </div>
    <div class="columna-2">
      <p><b>Celular</b><br> 1.125rem <br> 18px <br> Regular (400) <br> color: #6f7271 </p>
    </div>
    <div class="columna-2">
      <p><b>Escritorio</b><br> 1.5rem <br> 24px <br> Regular (400) <br> color: #6f7271 </p>
    </div>
    <div class="columna-4">
<pre class="m-x--1">
  &lt; p class="titulo-subseccion">
    titulo subseccion
  &lt;/ p>
</pre>
    </div>
  </div>


  <h2 class="m-t-10">Parrafos</h2>
  <div class="contenedor ancho-lectura contenedor-izq">
    <p>Los parrafos o texto en general sin clase, están a 1rem con interlineado de 1.5em en regular (400). </p>
  </div>
  <div class="flex">
    <div class="columna-16">
      <p>Lorem ipsum dolor sit amet consectetur adipisicing elit. Aspernatur culpa pariatur suscipit recusandae, modi sit ipsa fugiat facere doloremque animi repellat similique perspiciatis error, accusantium voluptatum nemo corporis, ipsum cumque.</p>
    </div>
  </div>
  <h3 class="m-t-5">Auxiliares de color</h3>
  <div class="flex">
    <div class="columna-4">
      <p class="texto-color-base">Lorem ipsum dolor sit amet consectetur adipisicing elit. Aspernatur culpa pariatur suscipit recusandae, modi sit ipsa fugiat facere doloremque animi repellat similique perspiciatis error, accusantium voluptatum nemo corporis, ipsum cumque.</p>
    </div>
  <div class="columna-4">
<pre class="m-x--1">
  &lt; p class="texto-color-base">
    Lorem ipsum . . .
  &lt;/ p>
</pre>
      <p>#141414</p>
    </div>
    <div class="columna-4">
      <p class="texto-color-1">Lorem ipsum dolor sit amet consectetur adipisicing elit. Aspernatur culpa pariatur suscipit recusandae, modi sit ipsa fugiat facere doloremque animi repellat similique perspiciatis error, accusantium voluptatum nemo corporis, ipsum cumque.</p>
    </div>
  <div class="columna-4">
<pre class="m-x--1">
  &lt; p class="texto-color-1">
    Lorem ipsum . . .
  &lt;/ p>
</pre>
      <p>#fff</p>
    </div>
    <div class="columna-4">
      <p class="texto-color-2">Lorem ipsum dolor sit amet consectetur adipisicing elit. Aspernatur culpa pariatur suscipit recusandae, modi sit ipsa fugiat facere doloremque animi repellat similique perspiciatis error, accusantium voluptatum nemo corporis, ipsum cumque.</p>
    </div>
  <div class="columna-4">
<pre class="m-x--1">
  &lt; p class="texto-color-2">
    Lorem ipsum . . .
  &lt;/ p>
</pre>
      <p>#6f7271</p>
    </div>
    <div class="columna-4">
      <p class="texto-color-3">Lorem ipsum dolor sit amet consectetur adipisicing elit. Aspernatur culpa pariatur suscipit recusandae, modi sit ipsa fugiat facere doloremque animi repellat similique perspiciatis error, accusantium voluptatum nemo corporis, ipsum cumque.</p>
    </div>
  <div class="columna-4">
<pre class="m-x--1">
  &lt; p class="texto-color-3">
    Lorem ipsum . . .
  &lt;/ p>
</pre>
      <p>#404041</p>
    </div>
  </div>
  <h3 class="m-t-5">Parrafos especiales</h3>
  <div class="flex">
    <div class="columna-8">
      <p class="parrafo-texto-alto">Lorem ipsum dolor sit amet consectetur adipisicing elit. Veniam enim nobis ipsam temporibus. Obcaecati adipisci, laborum quos numquam sequi vero architecto libero, repellendus illo, accusamus consequatur voluptatibus distinctio ut atque!</p>
    </div>
    <div class="columna-4">
<pre class="m-x--1">
  &lt; p class="parrafo-texto-alto">
    Lorem ipsum . . .
  &lt;/ p>
</pre>
    </div>
    <div class="columna-4">
      <p>1.25rem <br> 20px</p>
    </div>
    <div class="columna-8">
      <p class="parrafo-texto-desplazado">Lorem ipsum dolor sit amet consectetur adipisicing elit. Veniam enim nobis ipsam temporibus. Obcaecati adipisci, laborum quos numquam sequi vero architecto libero, repellendus illo, accusamus consequatur voluptatibus distinctio ut atque!</p>
    </div>
    <div class="columna-4">
<pre class="m-x--1">
  &lt; p class="parrafo-texto-desplazado">
    Lorem ipsum . . .
  &lt;/ p>
</pre>
    </div>
    <div class="columna-4">
      <p>1.125rem <br> 18px <br> Medium (500)</p>
    </div>
    <div class="columna-8">
      <p class="parrafo-texto-entresacado">(Responsiva) Lorem ipsum dolor sit amet consectetur adipisicing elit. Veniam enim nobis ipsam temporibus. Obcaecati adipisci, laborum quos numquam sequi vero architecto libero, repellendus illo, accusamus consequatur voluptatibus distinctio ut atque!</p>
    </div>
    <div class="columna-4">
<pre class="m-x--1">
  &lt; p class="parrafo-texto-entresacado">
    Lorem ipsum . . .
  &lt;/ p>
</pre>
    </div>
    <div class="columna-2">
      <p><b>Celular</b><br>1.5rem <br> 24px <br> #404041</p>
    </div>
    <div class="columna-2">
      <p><b>Escritorio</b><br>1.75rem <br> 28px <br> #404041</p>
    </div>
  </div>

  <h2 class="m-t-10">Notas</h2>
  <div class="contenedor ancho-lectura contenedor-izq">
    <p>Única clase de notas a 0.875rem con interlineado de 1.3em en regular (400). </p>
  </div>
  <div class="flex">
    <div class="columna-8">
      <p class="notas">Notas: Lorem ipsum dolor sit amet consectetur adipisicing elit. Eveniet, officia nesciunt error nisi id laborum atque a, pariatur eligendi ipsam rem maxime in deserunt eum sapiente quis vero. Rerum, aut!</p>
    </div>
    <div class="columna-4">
<pre class="m-x--1">
  &lt; p class="notas">
    Notas: Lorem ipsum . . .
  &lt;/ p>
</pre>
    </div>
    <div class="columna-4">
      <p> 0.875rem <br> 14px <br> Regular (400)</p>
    </div>
  </div>


  <h2 class="m-t-10">Visualizaciones</h2>
  <div class="flex">
    <div class="columna-8">
      <p class="vis-titulo-proyecto">Título de proyecto</p>
    </div>
        <div class="columna-4">
<pre class="m-x--1">
  &lt; p class="vis-titulo-proyecto">
    Título de proyecto
  &lt;/ p>
</pre>
    </div>
    <div class="columna-4">
      <p> 1rem <br> 16px <br> Regular (400)</p>
    </div>
    
    <div class="columna-8">
      <p class="vis-titulo-leyenda">Título de leyenda</p>
    </div>
        <div class="columna-4">
<pre class="m-x--1">
  &lt; p class="vis-titulo-leyenda">
    Título de leyenda
  &lt;/ p>
</pre>
    </div>
    <div class="columna-4">
      <p> 1rem <br> 16px <br> Semibold (600)</p>
    </div>

    <div class="columna-8">
      <p class="vis-titulo-ejes">Título de ejes</p>
    </div>
        <div class="columna-4">
<pre class="m-x--1">
  &lt; p class="vis-titulo-ejes">
    Título de ejes
  &lt;/ p>
</pre>
    </div>
    <div class="columna-4">
      <p> .75rem <br> 12px <br> Semibold (600)</p>
    </div>

    <div class="columna-8">
      <p class="vis-valores-ejes">Valores de ejes</p>
    </div>
        <div class="columna-4">
<pre class="m-x--1">
  &lt; p class="vis-valores-ejes">
    Valores de ejes
  &lt;/ p>
</pre>
    </div>
    <div class="columna-4">
      <p> .75rem <br> 12px <br> Medium (500)</p>
    </div>

    <div class="columna-8">
      <p class="vis-fecha-actualizacion">Fecha de actualización</p>
    </div>
        <div class="columna-4">
<pre class="m-x--1">
  &lt; p class="vis-fecha-actualizacion">
    Fecha de actualización
  &lt;/ p>
</pre>
    </div>
    <div class="columna-4">
      <p> .75rem <br> 12px <br> Medium (500) <br> #6f7271</p>
    </div>

    <div class="columna-8">
      <p class="vis-instruccional">Instruccional</p>
    </div>
        <div class="columna-4">
<pre class="m-x--1">
  &lt; p class="vis-instruccional">
    Instruccional
  &lt;/ p>
</pre>
    </div>
    <div class="columna-4">
      <p> 1rem <br> 16px <br> Medium (500) </p>
    </div>

    <div class="columna-8">
      <p class="vis-titulo-visualizacion">Titulo de visualizacion (responsiva)</p>
    </div>
        <div class="columna-4">
<pre class="m-x--1">
  &lt; p class="vis-titulo-visualizacion">
    Titulo de visualizacion
  &lt;/ p>
</pre>
    </div>
    <div class="columna-2">
      <p> <b>Celular</b><br> 1.125rem <br> 18px <br> Semibold (600) </p>
    </div>
    <div class="columna-2">
      <p> <b>Escritorio</b><br> 1.5rem <br> 24px <br> Semibold (600) </p>
    </div>

    <div class="columna-8">
      <p class="vis-leyenda">Leyenda (responsiva)</p>
    </div>
        <div class="columna-4">
<pre class="m-x--1">
  &lt; p class="vis-leyenda">
    Leyenda
  &lt;/ p>
</pre>
    </div>
    <div class="columna-2">
      <p> <b>Celular</b><br> 1rem <br> 16px <br> Regular (400) <br> Interlineado 1.3em </p>
    </div>
    <div class="columna-2">
      <p> <b>Escritorio</b><br> 1rem <br> 16px <br> Regular (400) <br> Interlineado 1.5em </p>
    </div>

  </div>

</template>
