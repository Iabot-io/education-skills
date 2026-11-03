# Educación y formación · Skills para empleados IA de IAbot.io

Programación, materiales, rúbricas y seguimiento educativo con objetivos y fuentes explícitos.

Procedimientos abiertos y concretos para agentes IA, con entradas, criterios de revisión y entregables. Publicados por [IAbot.io](https://iabot.io), plataforma de empleados IA con memoria, aplicaciones y ordenador virtual Linux.

## Habilidades y uso

| Skill | Empleado en IAbot.io | Entrega que revisar |
| --- | --- | --- |
| [Diseñar secuencias de aprendizaje](skills/learning-sequence-design/SKILL.md) | un empleado de apoyo docente | Secuencia de sesiones, materiales y criterios de seguimiento. |
| [Crear rúbricas de evaluación](skills/assessment-rubric-design/SKILL.md) | un empleado de diseño de evaluación | Rúbrica editable y notas de aplicación para revisión docente. |
| [Adaptar materiales de aprendizaje](skills/accessible-learning-materials/SKILL.md) | un empleado de accesibilidad educativa | Material adaptado y registro de cambios para revisión. |
| [Preparar retroalimentación formativa](skills/learning-feedback-draft/SKILL.md) | un empleado de apoyo a la evaluación | Comentarios por criterio con evidencias y sugerencias de revisión. |
| [Analizar evaluación de cursos](skills/course-evaluation-summary/SKILL.md) | un empleado de calidad formativa | Informe agregado con patrones, ejemplos anonimizados y propuestas. |
| [Comparar oferta formativa](skills/training-catalog-comparison/SKILL.md) | un empleado de coordinación de formación | Matriz de cursos con adecuación, coste y preguntas pendientes. |

## Instalación y uso en IAbot.io

```sh
npx skills add Iabot-io/education-skills --list
npx skills add Iabot-io/education-skills
```

En la plataforma, abre **Skills**, revisa la habilidad e impórtala con el ámbito adecuado. Adjunta sus entradas y da el encargo al empleado. Consulta [la guía de uso en IAbot.io](USO-EN-IABOT.md) para el recorrido completo.

## Ejemplos

- **Diseñar secuencias de aprendizaje:** «Diseña tres sesiones para estos objetivos, con actividades y evidencias de progreso revisables.»
- **Crear rúbricas de evaluación:** «Prepara una rúbrica para esta tarea con descriptores claros y sin duplicar criterios.»
- **Adaptar materiales de aprendizaje:** «Prepara una versión más clara y accesible de este material y señala cualquier cambio de significado.»

## Herramientas y límites

Usa documentos y herramientas de aula autorizadas. El docente conserva las decisiones pedagógicas, las calificaciones finales y el acceso a datos de estudiantes.

La colección no instala aplicaciones ni concede accesos. Las referencias se comprueban según la fecha, jurisdicción y alcance del encargo. Los resultados profesionales o administrativos conservan sus responsables y revisiones.

## Fuentes de referencia

- [Instituto Nacional de Tecnologías Educativas y de Formación del Profesorado](https://intef.es/)
- [AEPD, educación y menores](https://www.aepd.es/)

Las fuentes orientan el método; su enlace no significa que una institución certifique o avale estas skills.

## Comprobación y licencia

```sh
python3 -m pip install -r scripts/requirements-validation.txt
python3 scripts/validate_skills.py
```

Se comprueban formato, recursos y referencias locales. Esa validación no acredita por sí sola un recorrido con un empleado real ni resultados en datos de producción. [Licencia MIT](LICENSE).

Agent Skills for AI employees and agents. Each skill includes an IAbot.io usage example and remains usable in compatible agents outside the platform.
