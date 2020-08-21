# Biografia
Esta es una pequeña biografia del autor
#
# Este archivo contiene indicadores de configuración para personalizar su sitio
#

# Nombre de su sitio (mostrado en el encabezado)
name : Tu nombre

# Breve biografía o descripción (mostrada en el encabezado)
descripción : Desarrollador web de algún lugar

# URL de su avatar o foto de perfil (puede usar su foto de perfil de GitHub)
avatar : https://raw.githubusercontent.com/barryclark/jekyll-now/master/images/jekyll-logo.png

#
# Las banderas a continuación son opcionales
#

# Incluye un icono en el pie de página para cada nombre de usuario que ingrese
enlaces de pie de página :
  regate :
  correo electronico :
  facebook :
  flickr :
  github : barryclark / jekyll-now
  Instagram :
  linkedin :
  pinterest :
  rss : # simplemente escriba cualquier cosa aquí para ver un icono de RSS que funcione
  gorjeo : jekyllrb
  stackoverflow : # su perfil de stackoverflow, por ejemplo, "usuarios / 50476 / bart-kiers"
  youtube : # channel / <your_long_string> o usuario / <user-name>
  googleplus : # cualquier cosa en su nombre de usuario de perfil que venga después de plus.google.com/


# Ingrese su nombre corto de Disqus (no su nombre de usuario) para permitir comentar en publicaciones
# Puede encontrar su nombre corto en la página de Configuración de su cuenta de Disqus
disqus :

# Ingrese su código de seguimiento web de Google Analytics (por ejemplo, UA-2110908-2) para activar el seguimiento
google_analytics :

# URL de su sitio web (por ejemplo, http://barryclark.github.io o http://www.barryclark.co)
# Se utiliza para Sitemap.xml y su feed RSS
url :

# Si está alojando su sitio en un repositorio de proyectos en páginas de GitHub
# (http://yourusername.github.io/repository-name)
# y NO su repositorio de usuarios (http://yourusername.github.io)
# luego agregue la baseurl aquí, así: "/ nombre-repositorio"
baseurl : " "

#
# !! ¡No necesita cambiar ninguna de las opciones de configuración a continuación!
#

enlace permanente : /: title /

# El lanzamiento de Jekyll Ahora que estás usando
versión : v1.2.0

# Jekyll 3 ahora solo es compatible con Kramdown para Markdown
kramdown :
  # Use la rebaja con sabor a GitHub, incluidos los bloques de código delimitados con triple tilde
  entrada : GFM
  # Jekyll 3 y GitHub Pages ahora solo admiten rouge para resaltado de sintaxis
  syntax_highlighter : colorete
  syntax_highlighter_opts :
    # Use la sintaxis de pigmentos existente resaltando css
    css_class : ' resaltar '

# Configure el directorio de parciales de Sass, ya que estamos usando @imports
descaro :
  estilo :: expandido # Es posible que prefieras minificar usando: comprimido

# Utilice los siguientes complementos
gemas :
  - jekyll-sitemap # Crea un mapa del sitio usando la gema oficial del mapa del sitio Jekyll
  - jekyll-feed # Crea una fuente Atom usando la gema oficial de la fuente Jekyll

# Excluya estos archivos de su _sitio de producción
excluir :
  - Gemfile
  - Gemfile.lock
  - LICENCIA
  - README.md
  - CNAME
