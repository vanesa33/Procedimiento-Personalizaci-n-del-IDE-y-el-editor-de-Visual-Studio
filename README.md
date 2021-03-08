# Procedimiento-Personalizaci-n-del-IDE-y-el-editor-de-Visual-Studio
Procedimiento Personalización del IDE y el editor de Visual Studio
El tema de color predeterminado de la interfaz de usuario de Visual Studio se denomina Azul. Se va a cambiar a Oscuro.
En la barra de menús, que es la fila de menús, como Archivo y Editar, elija Herramientas > Opciones.
En la página de opciones Entorno > General, cambie la selección de Tema de color a Oscuro y, después, elija Aceptar.
El tema de color de todo el entorno de desarrollo (IDE) de Visual Studio se cambia a Oscuro.
Ahora se van a personalizar algunos colores de texto para el editor. En primer lugar, se va a crear un nuevo archivo XML para ver los colores predeterminados.
En la barra de menús, seleccione Archivo > Nuevo > Archivo.
En el cuadro de diálogo Nuevo archivo, en la categoría General, elija Archivo XML y, después, elija Abrir.
Pegue el código XML siguiente debajo de la línea que contiene <?xml version="1.0" encoding="utf-8"?>.

<Catalog>
  <Book id="bk101">
  <Author>Garghentini, Davide</Author>
  <Title>XML Developer's Guide</Title>
  <Genre>Computer</Genre>
  <Price>44.95</Price>
  <PublishDate>2000-10-01</PublishDate>
  <Description>
    An in-depth look at creating applications with XML.
  </Description>
</Book>
<Book id="bk102">
  <Author>Garcia, Debra</Author>
  <Title>Midnight Rain</Title>
  <Genre>Fantasy</Genre>
  <Price>5.95</Price>
  <PublishDate>2000-12-16</PublishDate>
  <Description>
    A former architect battles corporate zombies, an evil
    sorceress, and her own childhood to become queen of the world.
  </Description>
</Book>
</Catalog>

Tenga en cuenta que los números de línea son de color azul turquesa y los atributos XML (como id="bk101") son de color azul claro. Ahora se va a cambiar el color del texto de estos elementos.

Para abrir el cuadro de diálogo Opciones, elija Herramientas > Opciones en la barra de menús.
En Entorno, elija la categoría Fuentes y colores.
Observe que el texto en Show settings for (Mostrar configuración para) reza Text Editor (Editor de texto), que es justamente lo que queremos. Expanda la lista desplegable solo para ver la extensa lista de lugares donde puede personalizar las fuentes y el color del texto.
Para cambiar el color del texto de números de línea, en la lista Mostrar elementos, elija Número de línea. En el cuadro Primer plano del elemento, elija Oliva.

Hemos explorado solo un par de formas de personalizar los colores en Visual Studio. Esperamos que explore las otras opciones de personalización en el cuadro de diálogo Opciones para que Visual Studio sea realmente suyo.
