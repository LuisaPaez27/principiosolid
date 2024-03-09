# principiosolid
2. Principio Liskov LSK
Crea un programa principal que ejecute los métodos de la clase Configuración.

Cumple la clase Configuracion en Principio OCP. Justifica la respuesta.

Si cumple, ya que para añadir nuevas configuraciones solo debemos crear la clase que implemente la interface RecursoPersistente y solo debemos agregar la linea en el metodo cargarConfiguracion.

Cumple la clase Configuracion el Principio de Liskov. Justifica la respuesta.

No cumple, ya que la clase ConfiguracionHoraria solo podria implementar el metodo cargar hora y no deberia salvar la configuracion de hora. El pricipio indica que toda subclase debe usar todos los metodos de la claseSuper y en este caso se incumple

Explica de forma general (independientemente del ejemplo) cual es el problema y la solución propuesta.

Toda sub clase debe implementar todos los metodos de la superclase, si una subclase no utiliza uno de los metodos significa que se incumple el principio de liskov, en este caso se extraen los metodos que tenia la superclase en interfaces y se implemtas en cada sub clase solo los metodos que esta usara, de esta forma no se incumple el principio.
