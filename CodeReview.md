# **Code Review: Frontend Challenge**

## Resumen

¡Hola Maximiliano! Estuve revisando la entrega de tu challenge y quiero compartir con vos algunos comentarios y sugerencias junto a la devolución.

## Objetivos del challenge

### Nivel 1

- [✓] Crear una versión de escritorio

- [✓] Cada producto debe tener un precio visible en puntos.
- [✗] Vínculo al repositorio de GitHub del proyecto (pie de página) Envía al perfil, no al repo
- [✗] El usuario debe poder ordenar los productos por precio, de mayor a menor, y viceversa.
- [✓] El usuario debería poder ver cuántos puntos tiene en su cuenta.
- [✗] Debe haber una forma clara para que el usuario distinga aquellos productos que puede canjear de aquellos que no puede.
- [✓] Un botón "Canjear" debe estar disponible para aquellos productos que el usuario tiene suficientes puntos para reclamar.
- [✗] Una opción "Canjear ahora" debería aparecer cuando el usuario interactúa con un producto que tiene suficientes puntos para reclamar.
- [✗] Cuando el usuario no tiene suficientes puntos para un producto, debería poder ver cuántos puntos más necesita para reclamarlo.
- [✗] El usuario no debería poder canjear un producto para el que no tiene suficientes puntos.
- [✗] Cuando el usuario hace clic en el botón Canjear ahora, el sistema debería deducir automáticamente el precio del artículo de los puntos de los usuarios.
- [✗] El usuario debe poder agregar puntos a su cuenta

### Nivel 2

- [✗] Crea una versión adaptable para dispositivos móviles

- [✓] El botón "ver todos los productos" (en la sección Héroe/Encabezado) debe desplazarse a la vista de los productos enumerados
- [✓] Haga la sección "Navegar, Elegir, Disfrutar"
- [✓] Pon todo tu esfuerzo en hacer que el sitio se vea hermoso
- [✓] Presta atención a los detalles y al sistema de diseño que te proporcionamos
- [✗] El usuario debe poder filtrar productos por categoría
- [✗] El usuario debería poder usar la paginación para ver más productos listados


## Aspectos positivos

- El proyecto sigue una estructura modular
- El formato visual obtenido es muy acorde al solicitado por el desafío
- Alojamiento en vercel
- Utilización de NextJS
- Trabaja con información externa y utiliza variables de entorno

## Áreas de mejora

1. **Funcionalidad**: 
Te recomiendo agregar la funcionalidad faltante. Es un punto muy importante a la hora de evaluar un challenge. Los botones de filtrado recargan la página pero no tienen ningún efecto y los botones de compra no contienen la información real.

2. **Responsividad**:
En este aspecto es aconsejable que practiques el diseño responsive para que tus proyectos puedan ser adaptables a diferentes dispositivos generando una mejor experiencia para el usuario.

3. **Detalles**:
Es bueno poner atención a los detalles en general. Por ejemplo, los botones de ordenamiento no deberían recargar la página


## Conclusiones

En general, el diseño de la página es agradable y condice bastante a lo requerido. Te felicito por haber hecho el detalle de la tarjeta para carga de puntos. Te recomiendo terminar las funcionalidades pedidas por el challenge, para los botones de compra te recomiendo renderizados condicionales en el caso de que el precio sea mayor o menor que el monto que tiene el usuario en su cuenta. Un detalle adicional pero muy importante es que agregues documentación de cómo correr el proyecto de forma local, ya que no está explicado en ningún lado la utilización de variables de entorno para las API key

¡Seguí adelante y seguí mejorando tus habilidades!

Si tenés alguna pregunta o necesitás aclaraciones adicionales, no dudes en preguntar.

Saludos,
[Pablo Ortega]