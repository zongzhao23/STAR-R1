# STAR-R1: Razonamiento espacial mediante transformación y refuerzo en modelos lingüísticos multimodales

Los modelos lingüísticos multimodales de gran tamaño (MLLMs) han demostrado una capacidad notable en diversas tareas, pero aún están muy por debajo de los humanos en cuanto a razonamiento espacial. Para abordar esta brecha, investigamos el Razonamiento Visual Basado en Transformaciones (TVR), una tarea compleja que implica identificar cambios en los objetos a través de imágenes con diferentes perspectivas. Aunque el entrenamiento supervisado tradicional (SFT) no logra generar procesos de razonamiento coherentes en entornos de múltiples perspectivas, el aprendizaje por refuerzo con recompensas escasas (RL) presenta problemas de exploración ineficiente y lenta convergencia. Para superar estas limitaciones, proponemos STAR-R1, un nuevo marco que combina un paradigma de aprendizaje por refuerzo de una sola etapa con un sistema de recompensas detallado diseñado específicamente para TVR. STAR-R1 recompensa la corrección parcial, al tiempo que penaliza la enumeración excesiva y la inactividad pasiva, lo que permite una exploración eficiente y un razonamiento preciso. Evaluaciones exhaustivas demuestran que STAR-R1 alcanza un rendimiento líder en todas las 11 métricas, superando a SFT en un 23 % en escenarios de múltiples perspectivas. Además, un análisis más profundo revela el comportamiento antropomórfico de STAR-R1 y su capacidad única para comparar todos los objetos con el fin de mejorar el razonamiento espacial. Nuestro trabajo aporta conocimientos fundamentales para avanzar en la investigación de los MLLMs y los modelos de razonamiento.

## Lista de tareas pendientes

**¡Debido a los múltiples plazos próximos, publicaremos el código definitivo en junio!**

- [ ] Publicar los códigos de entrenamiento y evaluación
- [ ] Publicar los conjuntos de datos de entrenamiento y evaluación
- [ ] Publicar los scripts de entrenamiento y evaluación
- [ ] Publicar los pesos del modelo de STAR-R1

![fig2](https://github.com/user-attachments/assets/90f52c4a-b17c-480c-adc4-0608e8228abe)

![fig3](https://github.com/user-attachments/assets/cfb6930b-d841-4917-9cd6-58dfa8e66c4c)

![fig5](https://github.com/user-attachments/assets/87854fa7-de46-4f4f-bf66-9f062e6a0a71)

![fig6](https://github.com/user-attachments/assets/8bae0484-d75c-463e-869f-6ad93bb954dc)
