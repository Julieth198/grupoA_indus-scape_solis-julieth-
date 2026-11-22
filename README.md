# Indus Scape 

**Grupo A**

## Integrantes
- Adrian Alejandra
- Estrella Juan
- Solis Julieth
- Briones Khatia
- León Paulina
- Torres Scarleth

## Introducción

Indus Scape es un videojuego educativo cooperativo desarrollado como propuesta para Roblox. Su propósito es reforzar el aprendizaje de ecuaciones lineales y cálculo de derivadas mediante desafíos matemáticos dentro de una planta industrial en emergencia. Los jugadores trabajan en equipo para resolver ejercicios, superar obstáculos y avanzar por distintas salas antes de que termine el tiempo disponible. El sistema busca ofrecer práctica dinámica, retroalimentación inmediata y una experiencia de aprendizaje motivadora para estudiantes universitarios que cursan Cálculo Diferencial.

## Tabla de análisis de requisitos y pruebas

| ID | Tipo | Descripción del requisito | Caso de prueba propuesto | Resultado esperado |
|---|---|---|---|---|
| RF-01 | Funcional | El sistema permitirá que los jugadores se unan a uno de los ocho grupos del lobby. | Seleccionar un grupo y pulsar ¡LISTOS! | El jugador queda registrado en el grupo seleccionado. |
| RF-02 | Funcional | El sistema presentará ejercicios matemáticos y validará las respuestas ingresadas. | Ingresar una respuesta correcta y otra incorrecta en una terminal. | La respuesta correcta permite avanzar y la incorrecta resta 15 segundos. |
| RF-03 | Funcional | El sistema permitirá resolver el desafío de la Sala de Emergencia y seleccionar una de las cuatro rutas finales. | Ajustar las cuatro válvulas, votar por una ruta y resolver el ejercicio final. | Se desbloquean las salidas y, si responde correctamente a tiempo, el equipo escapa. |
| RNF-01 | No funcional | La validación de respuestas deberá realizarse en un máximo de 3 segundos bajo condiciones normales de conexión. | Medir el tiempo de respuesta de varias validaciones. | Cada validación tarda 3 segundos o menos. |
| RNF-02 | No funcional | El videojuego deberá poder utilizarse desde computadora, tablet y celular. | Abrir el juego en los tres dispositivos y probar el lobby y las terminales. | Las funciones principales funcionan en los tres dispositivos. |

## Documento completo

[TPE4_Requerimientos_y_Pruebas.pdf](TPE4_Requerimientos_y_Pruebas.pdf)



