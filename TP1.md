## DIAGNÓSTICO

### 1 - ¿A qué nos referimos cuando hablamos de APP?
Cuando hablo de una APP, me refiero a una aplicación de software diseñada específicamente para ser ejecutada en dispositivos móviles, como teléfonos o tablets. Para mí, la diferencia clave es que están optimizadas para aprovechar las funciones propias del dispositivo (como el GPS, la cámara o los sensores) y para ser usadas de forma táctil y rápida.

### 2 - ¿Qué es el Frontend y qué es el Backend? De una definición con sus palabras y explique cómo se comunican habitualmente.
 El FRONTEND es la parte que yo puedo ver y tocar; es el diseño y la interfaz con la que interactúo. 
El BACKEND, en cambio, es la parte "invisible", donde se procesa la lógica y se guarda la información en los servidores. 
Habitualmente se comunican a través de internet: el Frontend envía una petición (como querer ver una foto) y el Backend le responde enviando los datos necesarios para que la pantalla los muestre.

### 3 - ¿Qué es una API REST? ¿Cuál es su función principal cuando desarrollamos una aplicación para dispositivos móviles? 
Entiendo que una API REST es como un puente o un conjunto de reglas que permite que mi aplicación se comunique con un servidor. Su función principal en el desarrollo móvil es permitir que la app obtenga información actualizada de internet en tiempo real, sin necesidad de que todo el contenido esté guardado dentro del teléfono, lo que hace que la aplicación sea mucho más eficiente y liviana.

### 4 - ¿Qué es el formato JSON? Escribe un ejemplo simple de cómo se vería un objeto "Alumno" con nombre, apellido y una lista de 3 notas en este formato. 
El JSON es un formato de texto ligero que usamos para intercambiar datos de forma que sea fácil de leer tanto para nosotros como para las máquinas. Un objeto "Alumno" se vería así:
JSON
{
  "nombre": "Mariana",
  "apellido": "Gauna",
  "notas": [8, 9, 10]
}

### 5 - ¿Qué es una librería (o biblioteca) y qué es un Framework? ¿Son lo mismo? Justifique su respuesta. 
No, no son lo mismo. 
Una LIBRERÍA es una colección de funciones que yo elijo llamar cuando necesito resolver algo puntual (yo tengo el control del código). 
Un FRAMEWORK, por otro lado, es una estructura completa que me dice cómo debo organizar mi aplicación; es como un "esqueleto" que ya viene con reglas predefinidas a las que me tengo que adaptar.

### 6 - ¿Qué es un sistema de control de versiones y para qué sirve? Explique qué sucede si dos desarrolladores modifican la misma línea de código en el mismo archivo y cómo se resuelve. 
Es una herramienta (como Git) que sirve para registrar todos los cambios que se hacen en el código de un proyecto. Si dos personas modifican la misma línea al mismo tiempo, se produce lo que conocemos como "problema". Para resolverlo, el sistema nos obliga a revisar manualmente ambas versiones para decidir con cuál quedarnos o cómo fusionarlas de forma que el programa siga funcionando bien.

### 7 - ¿Qué es la Programación Orientada a Objetos (POO)? Defina brevemente los conceptos de Clase, Objeto y Herencia. 
Es un modelo de programación en el que organizamos el código imitando cosas de la vida real.
•	CLASE: Es el plano o molde general (por ejemplo, el plano de un "Auto").
•	OBJETO: Es la representación real de ese molde (mi auto rojo estacionado afuera).
•	HERENCIA: Es la capacidad de crear una clase nueva basada en otra ya existente, heredando sus características para no tener que escribirlas de nuevo.

### 8 - ¿Cuál es el propósito de los modificadores de acceso public y private en el contexto de la programación orientada a objetos? 
Su propósito es controlar la visibilidad y seguridad de los datos. 
Uso PUBLIC cuando quiero que cualquier parte del programa pueda acceder a esa información. 
Uso PRIVATE para proteger los datos, permitiendo que solo se puedan usar dentro de la propia clase donde fueron creados, evitando así que otras partes del código los rompan o modifiquen sin permiso.

### 9 - Explique las principales diferencias entre los sistemas operativos iOS (iPhone) y Android desde el punto de vista del desarrollo (lenguajes nativos, tiendas de aplicaciones y tipos de dispositivos). Además, mencione si conoce algún otro sistema operativo para móviles que exista o haya existido en el mercado. 
La principal diferencia es que Android es un sistema abierto que funciona en muchísimas marcas de dispositivos y se programa principalmente en Java o Kotlin, usando la Google Play Store. 
En cambio, iOS es exclusivo de Apple, se programa en Swift y su tienda es la App Store. 
Otros sistemas que existieron son Windows Phone, BlackBerry OS y el antiguo Symbian de Nokia.

### 10 - ¿Cómo piensa que una aplicación móvil podría facilitar la vida de una persona con discapacidad visual en Las Lajitas?
 Pienso que sería de gran ayuda una aplicación que use comandos de voz y GPS adaptados a nuestra localidad. Podría guiar a la persona indicándole por audio en qué calle se encuentra, qué comercios tiene cerca o cuándo está por pasar el colectivo. También sería útil que pueda usar la cámara para "leerle" a la persona los precios en los negocios o identificar billetes, dándole así mucha más independencia en su día a día aquí en el pueblo.

### Serrato Gauna Mariana
