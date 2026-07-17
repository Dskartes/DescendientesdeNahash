---
title: Podcast
eyebrow: "✦ Resúmenes en audio"
subtitle: "Resúmenes en audio de los libros y publicaciones del proyecto, generados con NotebookLM."
---

<div class="card-grid">

  <div class="card">
    <div class="card-top">
      <div class="card-mark">✦</div>
      <div class="card-tag">Podcast</div>
    </div>
    <h3 class="card-title">Génesis entre el Big Bang y Babilonia</h3>
    <p class="card-desc">Resumen del libro En el principio del Génesis.</p>
    <audio class="card-audio" controls preload="none">
      <source src="{{ '/podcast/Génesis_entre_el_Big_Bang_y_Babilonia.mp3' | relative_url }}" type="audio/mpeg">
      Tu navegador no soporta audio HTML5.
    </audio>
    <div class="card-meta">
      <span class="card-info">Basado en: En el principio del Génesis</span>
      <a class="card-btn" href="{{ '/podcast/Génesis_entre_el_Big_Bang_y_Babilonia.mp3' | relative_url }}" download>Descargar</a>
    </div>
  </div>

</div>

<!--
  Para el siguiente episodio, copia el bloque <div class="card"> de arriba (entre
  <div class="card-grid"> y </div>), pégalo justo antes del </div> de cierre del grid,
  y cámbiale: título, descripción, "Basado en", y el nombre del archivo .mp3
  (en las DOS líneas que lo mencionan) por el del nuevo episodio.
  Sube el audio a la carpeta podcast/, ej. podcast/nombre-del-episodio.mp3
-->

<!--
  Cuando tengas el primer episodio, copia este bloque dentro de un <div class="card-grid"> y complétalo:
  (sube el audio a la carpeta podcast/, ej. podcast/nombre-del-episodio.mp3)

  <div class="card-grid">
    <div class="card">
      <div class="card-top">
        <div class="card-mark">✦</div>
        <div class="card-tag">Podcast</div>
      </div>
      <h3 class="card-title">Título del episodio</h3>
      <p class="card-desc">Resumen breve de una o dos líneas — de qué libro o publicación es.</p>
      <audio class="card-audio" controls preload="none">
        <source src="{{ '/podcast/nombre-del-episodio.mp3' | relative_url }}" type="audio/mpeg">
        Tu navegador no soporta audio HTML5.
      </audio>
      <div class="card-meta">
        <span class="card-info">Basado en: nombre del libro</span>
        <a class="card-btn" href="{{ '/podcast/nombre-del-episodio.mp3' | relative_url }}" download>Descargar</a>
      </div>
    </div>
  </div>
-->
