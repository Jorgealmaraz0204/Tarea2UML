# Tarea2UML
![diagrama](https://github.com/user-attachments/assets/ec54c987-60f7-4a14-b26d-3235bcc7d47e)


# Explicación del diagrama:

#Clases:
Animal, Gato, Perro, PerroGuardian, Veterinaria.
#Interfaz:
Domesticable.
#Abstracta: 
La clase Animal es abstracta, representada por un nombre en cursiva.
#Atributos: 
Los atributos se muestran con su visibilidad (privados: -, protegidos: #), si son estáticos (static) y si tienen un valor inicial.
#Métodos: 
Los métodos se muestran con su visibilidad (+: público, -: privado), si son abstractos (abstract) y sus argumentos y tipo de retorno.
#Constructores:
Los constructores se muestran con su visibilidad y argumentos.
#Asociaciones: 
Hay asociaciones entre Veterinaria y Gato, y Veterinaria y Perro.
#Multiplicidad/Cardinalidad:
Veterinaria puede tener cero o más gatos y perros (0..*), mientras que cada gato y perro pertenece a una sola veterinaria (1).
#Agregación:
La asociación entre Veterinaria y Gato/Perro es de tipo agregación (representada por un diamante blanco en el lado de Veterinaria), lo que significa que Veterinaria contiene instancias de Gato y Perro, pero estos no tienen una existencia independiente.


#Comentarios adicionales:

La interfaz Domesticable define el método serSociable.
Las clases Gato y Perro implementan la interfaz Domesticable.
La clase PerroGuardian hereda de Perro y sobrescribe algunos métodos.
La clase Veterinaria puede contener un número limitado de gatos y perros (máximo 5).


AFL-3.0
