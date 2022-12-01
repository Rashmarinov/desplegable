# MarketsFlow

Refactorización By Enrique Estrada

- ¿Faltan archivos?: Todo ok.

- ¿Comprobación de imágenes?: Todo ok.

- ¿Comentarios suficientes?: Encuentro que faltan comentarios en el index.css.
  commit - ["AñadidoComentarios"]

- ¿Identación?: Mal indentado.

commit - ["AñadidoIndentado"]

- ¿Head correcto?: Todo ok.

- ¿Container correcto?: Hay container pero no es flex y no ocupa 100vh.

- Creaciones:

1. Desplegable -> Correcto.
2. Fondo -> Incorrecto (Segmento Blanco en el index).
3. Login -> Correcto.
4. Links Desplegable -> Correcto.

- ¿Colores?: Correcto.

- ¿Texto?: Correcto.

- Arreglo del container: Hecho.

He añadido un container para el login distinto (así no se corrompen los colores), además he establecido el background color para cada container y les he asignado un 100vh para que ocupen toda la pantalla.

commit - ["ContainerFix"]

- Hueco en la parte superior del login: Arreglado.

La clase .tituloSuperior contiene un margin (top) de 3vh que genera un hueco blanco en la parte superior del login bastante horrible. Lo cambio por un padding top 125px y solucionado.

commit - ["MarginFix"]
