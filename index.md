---
layout: default
title: Inicio
---

# Bienvenido a mi blog

Contenido de bienvenida...

<!-- mo blog usa la erramienta https://giscus.app/es; la cual me permite que puedas contactarte con la comunidad a travez de los cometarios -->
{{ content }}

{% if page.comments %}
  <div id="giscus-comments"></div>
  <script src="https://giscus.app/client.js"
          data-repo="srg-info/srg-info.github.io"
          data-repo-id="TU_REPO_ID"
          data-category="Comentarios"
          data-category-id="TU_CATEGORY_ID"
          data-mapping="pathname"
          data-reactions-enabled="1"
          data-emit-metadata="0"
          data-input-position="bottom"
          data-theme="light"
          crossorigin="anonymous"
          async>
  </script>
{% endif %}
