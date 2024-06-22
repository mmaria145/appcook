# AppCook
Realizamos esta app puesto que en muchos hogares, los alimentos se desperdician porque no se utilizan antes de que se estropeen. Además, a menudo las personas no saben qué cocinar con los ingredientes que tienen disponibles. Este problema no solo tiene un impacto económico negativo, sino que también contribuye a problemas ambientales debido al desperdicio de alimentos.

## Escribir sobre el contexto de su solución
AppCook es una aplicación diseñada para ayudar a los usuarios a generar recetas basadas en los ingredientes que tienen disponibles en casa. Esta solución surge de la necesidad de optimizar el uso de los alimentos que ya tenemos, reduciendo el desperdicio y facilitando la preparación de comidas de manera creativa y eficiente. La aplicación está dirigida a cualquier persona que busque nuevas ideas para cocinar con lo que tiene a mano, ya sean cocineros principiantes o experimentados.

# Modelo Relacional
## Adjuntar modelo
**Receta**
  - IdReceta (clave primaria)
  - NombreReceta
  - Instrucciones
  - TiempoPreparacion
  - Dificultad
  - Calorias
    
**Ingrediente**
  - IdIngrediente (clave primaria)
  - NombreIngrediente
  - Categoria
    
**Usuario**
  - IdUsuario (clave primaria)
  - NombreUsuario
  - CorreoElectronico
# Desarrollo de propuesta 
## Escribir sobre la solucion a realizar
Nuestra propuesta está relacionada para los fanáticos en la cocina y a los que están aprendiendo a cocinar, de esta forma puedan descubrir una gran variedad de recetas.

Búsqueda de Recetas: Los usuarios podrán buscar recetas filtrando por ingredientes principales.

Generación de Recetas Aleatorias: Opción para descubrir nuevas recetas de forma aleatoria.

Perfiles de Usuario: Capacidad para que los usuarios creen perfiles donde puedan guardar sus recetas favoritas y preferencias de ingredientes.

Interacción Social: Posibilidad de compartir recetas con otros usuarios y recibir comentarios y valoraciones.

Notificaciones Personalizadas: Alertas sobre nuevas recetas basadas en las preferencias de usuario.

Ingreso de Ingredientes: Los usuarios pueden ingresar los ingredientes que tienen en casa a través de una interfaz simple y fácil de usar.

Lista de Compras: La aplicación puede generar una lista de compras basada en las recetas seleccionadas, incluyendo solo los ingredientes que faltan.

Modo Offline: Los usuarios pueden acceder a las recetas y listas de compras sin necesidad de estar conectados a Internet.
