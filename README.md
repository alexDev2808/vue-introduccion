# vue-introduccion
Introduccion a Vue.js


Interpolación de datos

La variable vm es el objeto principal que contiene toda la aplicación donde puede tener un solo componente o más.

Tenemos 2 opciones para construir para poder crear aplicaciones:

    Primera opción: Tener 2 instancias separadas, para 2 elementos html

    Segunda opción: Crear componentes dentro componentes, es este caso dentro del componente principal, se podría crear subcomponentes y todo estaría contenido dentro de un único div id=”app”

En este caso lo que más se suele hacer es la segunda opción, de crear componentes anidados; porque todo este dentro del mismo objeto principal se va compartir un contexto de varias cosas y va facilitar el trabajo.

La primera opción es válida ya que hay proyectos que no se usan al 100% que trabajan una pequeña parte de una sección.
Template

La Sintaxis que contienen dentro de las dobles llaves, podemos ingresar cualquier expresión valida de JavaScript o en este caso algo que este dentro del contexto de datos del objeto de vue.js.

También el elemento div, deja de ser considerado un simple elemento html y forma parte dentro del componente que se acaba de crear, en términos de Vue.js se conoce como “Template” del Componente.

Cuando creemos componentes mas avanzados necesitaremos un elemento html; pero no siempre necesitaremos estar agregando directamente sobre el elemento html el Template; sino que dentro del mismo objeto de configuración de las opciones vue.js se podrá agregar Templates para que se rendericen de la forma correcta y estén todos separados y reutilizables.