Material docente para Infraestructura Virtual
==

[Infraestructura virtual](http://grados.ugr.es/informatica/pages/infoacademica/guias_docentes/espti/infraestructuravirtual)
es una asignatura optativa del primer cuatrimestre del cuarto de Grado
de Ingeniería Informática.

La asignatura se imparte en el curso 2013-2014 los lunes de 11:30 a
13:30 en la 1.5 y los viernes de 9;30 a 11:30 en la 3.2. Se usará
[GitHub](http://github.com) para las prácticas y trabajo final.

Estos son los [objetivos de la asignatura](documentos/objetivos.md). 

Temario
------------

<ol>
  {% for page in site.pages %}
	  {{page.url | split: /  }}
	  {{page.url | split: / | first }}
      {{page.url | split: / | first | first }}
	  {% if {{page.url | split: / | first | first }} == 'temas' %}
    <li>
      <a href="{{ page.url  }}">{{ page.title }}</a>
    </li>
	   {% endif %}
  {% endfor %}
</ol>
