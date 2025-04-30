# Pull Request

## Descripción

<!-- Descripción clara y concisa de lo que hace este Pull Request. Asegúrate de incluir el propósito y los cambios principales. -->

## Tipo de Cambio

- [ ] Bug fix (corrección de errores)
- [ ] Nueva funcionalidad
- [ ] Cambio de funcionalidad existente
- [ ] Refactorización de código
- [ ] Mejoras en rendimiento
- [ ] Actualización de dependencias
- [ ] Documentación
- [ ] Otro: ___(especificar)___

## ¿Cómo se ha probado?

<!-- Describe los métodos utilizados para probar el código, como pruebas manuales, pruebas unitarias, pruebas de integración, etc. Si se han agregado nuevas pruebas, asegúrate de mencionarlas aquí. -->

- [ ] He ejecutado las pruebas unitarias.
- [ ] He probado manualmente el cambio en el entorno de desarrollo.
- [ ] He verificado que no haya nuevos errores en el entorno de integración.
- [ ] He ejecutado pruebas de integración (si aplica).

## Checklist para el Desarrollador

Antes de crear este pull request, asegúrate de haber completado los siguientes pasos:

- [ ] **Código limpio y legible:** He seguido las convenciones de estilo de código del proyecto.
- [ ] **Pruebas unitarias:** He cubierto con pruebas los nuevos cambios de código, si aplica.
- [ ] **Documentación:** He actualizado la documentación si los cambios lo requieren.
- [ ] **No se ha dejado código comentado:** He eliminado cualquier código innecesario o comentado.
- [ ] **No hay errores de compilación:** El código compila sin errores.
- [ ] **El código no introduce vulnerabilidades:** He revisado el código en busca de problemas de seguridad.
- [ ] **Cumplimiento de buenas prácticas:** El código sigue las mejores prácticas del proyecto (ej. SOLID, DRY, KISS).
- [ ] **No hay dependencias innecesarias:** He verificado que no se han añadido nuevas dependencias que no sean estrictamente necesarias.
- [ ] **No se ha roto la funcionalidad existente:** He probado los cambios para asegurarme de que no afecten funcionalidades previas.

## Contexto Adicional

<!-- Si es necesario, proporciona contexto adicional que pueda ser útil para los revisores, como enlaces a tickets de Jira, discusiones previas, o detalles técnicos relevantes. -->

## Tickets Relacionados

<!-- Si este PR está relacionado con algún ticket o issue, menciona los números o enlaces correspondientes. Ejemplo: Closes #123, Related to #456 -->

- Closes: ___(número de ticket/issue)___
- Related to: ___(número de ticket/issue)___

## Capturas de Pantalla (si aplica)

<!-- Si el PR involucra cambios en la interfaz de usuario, proporciona capturas de pantalla o gifs para ilustrar cómo se ve el resultado final. -->

![Imagen de ejemplo](link_a_imagen)

## Notas para los Revisores

<!-- Incluye cualquier detalle relevante para los revisores, como áreas donde necesitas ayuda, dudas que tengas o comentarios sobre decisiones tomadas en el código. -->

---

## Checklist para los Revisores

A continuación se presentan los puntos que debes revisar antes de aprobar el pull request. Marca cada ítem conforme vayas validando:

- [ ] **Cumple con los requisitos del ticket/issue:** El cambio resuelve adecuadamente el problema o implementa la funcionalidad solicitada.
- [ ] **Código limpio y bien estructurado:** El código sigue las buenas prácticas de desarrollo y es fácil de entender.
- [ ] **Pruebas adecuadas:** El código tiene pruebas suficientes que cubren los casos esperados, incluyendo edge cases si aplica.
- [ ] **El código no rompe funcionalidades existentes:** He probado que no se han introducido regresiones ni errores en el código existente.
- [ ] **Rendimiento:** No he detectado problemas de rendimiento relacionados con estos cambios.
- [ ] **Seguridad:** El código no introduce vulnerabilidades conocidas. Las validaciones de seguridad están correctamente implementadas.
- [ ] **Legibilidad del código:** Las funciones y variables tienen nombres claros y descriptivos. El código está bien comentado cuando es necesario.
- [ ] **Cumplimiento de convenciones de estilo:** El código sigue las convenciones de estilo del proyecto.
- [ ] **Dependencias:** No se han introducido dependencias innecesarias o vulnerables.
- [ ] **Documentación:** La documentación está actualizada si el cambio lo requiere (documentación de funciones, README, etc.).
- [ ] **Revisión de cambios visuales (si aplica):** He revisado que los cambios en la UI (interfaz de usuario) sean correctos y consistentes.

## Comentarios Adicionales del Revisor

<!-- Si tienes comentarios o sugerencias adicionales sobre el código o el proceso de desarrollo, añádelos aquí. -->

---

## Responsabilidades del Revisor al Aprobar el Pull Request

Al aprobar un pull request, el revisor asume las siguientes responsabilidades:

1. **Garantizar la Calidad del Código**: El revisor debe asegurarse de que el código sea limpio, legible, y esté bien estructurado. Esto incluye verificar que el código siga las buenas prácticas de desarrollo y el estilo del proyecto.

2. **Validar las Pruebas**: El revisor debe asegurarse de que el código esté suficientemente cubierto por pruebas unitarias e integradas. Esto también incluye la revisión de las pruebas existentes y la verificación de que cubren todos los escenarios posibles.

3. **No Introducir Errores**: El revisor debe comprobar que los cambios no rompen la funcionalidad existente y que no se introducen errores o problemas de rendimiento. Es fundamental asegurarse de que los cambios no afecten negativamente el sistema.

4. **Validar la Seguridad**: El revisor debe verificar que el código no introduzca vulnerabilidades o debilidades de seguridad, y que cualquier entrada de usuario esté correctamente validada y sanitizada.

5. **Revisar el Cumplimiento de los Requisitos**: El revisor debe verificar que el PR cumpla con los requisitos establecidos en el ticket o en la historia de usuario, asegurándose de que el código resuelva el problema o implemente la funcionalidad requerida.

6. **Considerar el Impacto en el Proyecto**: El revisor debe considerar cómo los cambios afectarán al proyecto en su conjunto, incluyendo el impacto en otras partes del código, dependencias y rendimiento.

7. **Dar Retroalimentación Constructiva**: En caso de encontrar problemas, el revisor debe proporcionar comentarios constructivos para que el desarrollador pueda mejorar el código. Los comentarios deben ser claros y orientados a la mejora continua.

8. **Asumir la Responsabilidad Final**: Al aprobar el PR, el revisor asume la responsabilidad de que el código es adecuado para ser integrado al repositorio principal, y que no introducirá problemas en el software.

Al aprobar el pull request, el revisor debe tener la confianza de que el código es adecuado para su integración, y que cumple con los estándares de calidad y buenas prácticas del equipo.
