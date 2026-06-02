# REFLEXION — Ejercicio 1.1: Estructura Semántica HTML

> **Instrucciones:** Completá este archivo DESPUÉS de terminar tu solución. Escribí con tus propias palabras. Respuestas copiadas de internet o generadas por IA sin elaboración propia no son válidas.
>
> Tiempo esperado para completar esta reflexión: 20–30 minutos.

---

## Sección 1 — Explicación de mi solución

*Describí en 150–250 palabras qué hace tu archivo HTML y cuáles fueron las decisiones de estructura que tomaste. No copies el código, explicá el razonamiento.*

> ✏️ **Tu respuesta aquí:**
>
> [el archivo que hice se basa en mostrar un articulo que habla de la IA en el desarrollo de software, sus ventajas y desventajas, ademas de como nos puede jugar en contra. Me base en documentacion, foros e incluso use la IA para verificar que lo que yo hacia estaba bien o si habia algun error que yo no podia encontrar. El HTMl en si es basico, un articulo con secciones que hablan de los temas que mensioné, tiene un footer para el copyright (le puse unos archivos de muestra mas que nada), un encabezado bastante breve e 
informativo para guiarse y unos links para saltar a las secciones directamente]

---

## Sección 2 — Preguntas conceptuales

Respondé cada pregunta. Las respuestas deben ser tuyas. Podés investigar, pero explicá con tus palabras.

### 2.1 — ¿Cuál es la diferencia entre `<section>` y `<article>`? ¿Cuándo usarías cada uno?

> ✏️ **Tu respuesta: article , esta compuesto  de section vendria, a ser los "subtitulos" que van a estar dentro del articulo y que sirven para separar los temas y mejor lectura**

---

### 2.2 — ¿Por qué es importante el atributo `datetime` en la etiqueta `<time>`? ¿Quién lo usa?

> ✏️ **Tu respuesta: Se usa para ver en que momento o fecha fue hecho, un articulo nuevo va a tener mejor resultado que uno desactualizado**

---

### 2.3 — Tu página tiene `<header>` en dos lugares: uno para la página y uno dentro del `<article>`. ¿Eso es válido? ¿Por qué?

> ✏️ **Tu respuesta:si, porque uso uno para la pagina en general y otros para que cada seccion tenga su propio encabezado. Tengo entendido que es totalmente valido**

---

### 2.4 — Un motor de búsqueda como Google lee tu HTML. ¿Qué ventaja le da usar etiquetas semánticas versus usar solo `<div>` con clases?

> ✏️ **Tu respuesta: facilia a los buscadores dar mejores resultados ya que "filtra" por las etiquetas**

---

### 2.5 — Encontrá **un error semántico** en el siguiente fragmento y explicá cómo lo corregirías:

```html
<div class="navigation">
  <div class="nav-item"><a href="/home">Inicio</a></div>
  <div class="nav-item"><a href="/about">Nosotros</a></div>
</div>

<div class="main-content">
  <div class="post-title">Mi primer artículo</div>
  <div class="post-body">
    <p>Contenido del artículo...</p>
  </div>
</div>
```

> ✏️ **Tu respuesta:El error semántico es que se están utilizando etiquetas genéricas <div> en lugar de las etiquetas semánticas de HTML5 que corresponden a cada sección. Para corregirlo, cambiaría el <div class="navigation"> por la etiqueta <nav>. Luego, cambiaría el <div class="main-content"> por <main>, el título por un <h1>, y agruparía el contenido del post dentro de un <article>**

---

## Sección 3 — Decisiones técnicas

### 3.1 — ¿Qué etiqueta usaste para el logo y por qué? ¿Hay alternativas?

> ✏️ **Tu respuesta:use img,porque era la forma mas prolija de trabajar imagenes,ademas que me permitia usar <alt> que era necesaria para la consigna**

---

### 3.2 — ¿Elegiste `<ul>` u `<ol>` para tu lista? ¿Por qué esa y no la otra?

> ✏️ **Tu respuesta:ul es para una lista y ol es para una lista ordenada/numerada, como no era necesaria o logica la numeracion solo use ul**

---

### 3.3 — Si alguien accede a tu página solo con un lector de pantalla (sin ver el HTML), ¿podría navegar y entender el contenido? ¿Qué cambiarías para mejorar la experiencia?

> ✏️ **Tu respuesta:si, ya que le di una buena organizacion con respecto a subtitulos y demas, pero me gustaria decorarlo mas para que sea mas atractivo a la vista**

---

## Sección 4 — Declaración de uso de IA

Marcá con una `x` lo que corresponda:

```
[ ] Resolví el ejercicio completamente sin ayuda de IA
[x] Usé IA para entender algún concepto, pero escribí el código yo
[ ] Usé IA para generar un borrador que luego modifiqué y entendí
[ ] Usé IA extensamente y completé la reflexión para entender lo que hice
```

*Si usaste IA, describí brevemente cómo:*

> ✏️ **Tu respuesta (opcional si no usaste IA): leyendo la teoria y el resumen que hay de html, me fui mandando cada vez mas, pero iba teniendo errores mientras codeaba que no vei y la IA me ayudó a corregirlo ademas de modelarlo un poco mejor**

---

## Sección 5 — Autoevaluación

En una escala del 1 al 5, ¿cuánto entendés ahora el concepto de HTML semántico?

```
[ ] 1 — Muy poco, necesito repasar
[ ] 2 — Entiendo lo básico
[ ] 3 — Lo entiendo bien
[x] 4 — Lo entiendo bien y puedo explicárselo a otro
[ ] 5 — Podría dar una clase sobre esto
```

*¿Qué parte te resultó más difícil?*

> ✏️ **Tu respuesta:se me dificulto con el tiempo que me llevo hacerlo, no se si en cuando a dificultad, pero estoy seguro de las cosas que puse ( no se si estan del todo bien), pero los conceptos los pude captar todos**
