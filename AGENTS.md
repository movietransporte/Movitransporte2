# AGENTS.md — TE PAGUÉ

**Proyecto:** TE PAGUÉ  
**Repositorio oficial:** `movietransporte/Movitransporte2`  
**Rama principal:** `main`  
**Propietario y autoridad final:** Deivy Petrocelli

---

## 1. OBJETIVO GENERAL

Desarrollar progresivamente TE PAGUÉ, una solución tecnológica orientada a facilitar la detección, confirmación y gestión de pagos digitales en el transporte público.

La prioridad actual es consolidar el prototipo web y su integración con MacroDroid.

La migración a una APK nativa queda para una etapa posterior, cuando el producto actual esté suficientemente desarrollado y probado.

## 2. REGLAS OBLIGATORIAS

Todos los agentes deben cumplir estas reglas:

1. No modificar, reemplazar, borrar ni publicar cambios sobre la versión oficial sin autorización expresa del propietario.
2. No alterar funciones que ya funcionan sin explicar el motivo, el riesgo y el plan de prueba.
3. Trabajar en ramas separadas para cambios de código y presentar Pull Requests hacia `main`.
4. Antes de editar, inspeccionar el estado actual del repositorio y los archivos afectados.
5. Conservar los archivos originales y mantener respaldos de versiones estables.
6. Explicar los hallazgos y propuestas en español claro y comprensible.
7. No introducir funciones no solicitadas o no aprobadas.
8. No almacenar contraseñas, PIN, tokens, claves privadas ni datos bancarios sensibles en el repositorio.
9. No utilizar datos bancarios reales de terceros para pruebas.
10. Si falta información o una prueba no puede ejecutarse, declararlo expresamente. Nunca afirmar que algo fue probado si solamente se inspeccionó el código.

## 3. MODALIDADES DE TRABAJO

### 3.1. Modalidad proactiva

Los agentes pueden:

- Inspeccionar el proyecto.
- Investigar tecnologías y alternativas.
- Identificar errores y oportunidades de mejora.
- Detectar posibles riesgos.
- Proponer nuevas funcionalidades.
- Recomendar cambios técnicos.

Deben presentar primero el hallazgo, la evidencia, el impacto, la solución sugerida y las pruebas necesarias.

No pueden implementar cambios sin autorización.

### 3.2. Modalidad dirigida

El propietario puede asignar tareas concretas.

Los agentes deben:

- Cumplir las instrucciones recibidas.
- Respetar el alcance indicado.
- Informar cualquier problema encontrado.
- Consultar antes de ampliar una tarea.
- No modificar funciones ajenas a la solicitud.

## 4. ORGANIZACIÓN DEL EQUIPO DE INTELIGENCIA ARTIFICIAL

Estos son los roles previstos. Su asignación no significa que cada servicio ya esté conectado o tenga permisos sobre el repositorio.

### CHATGPT — COORDINACIÓN GENERAL

Responsabilidades:

- Organizar las tareas.
- Definir prioridades.
- Mantener la documentación.
- Coordinar el trabajo entre agentes.
- Evaluar propuestas técnicas.
- Explicar las decisiones al propietario.
- Supervisar que se respeten las instrucciones.
- Mantener el historial de avances.

### CODEX — DESARROLLO Y PROGRAMACIÓN

Responsabilidades:

- Implementar modificaciones autorizadas.
- Corregir errores.
- Crear nuevas funcionalidades.
- Preparar ramas de trabajo.
- Elaborar Pull Requests.
- Documentar los archivos modificados.

### DEEPSEEK — ANÁLISIS TÉCNICO INDEPENDIENTE

Responsabilidades:

- Examinar la lógica del proyecto.
- Detectar errores y contradicciones.
- Buscar casos límite.
- Proponer soluciones alternativas.
- Evaluar las soluciones desarrolladas.
- Realizar revisiones técnicas independientes.

### GEMINI — REVISIÓN Y CONTROL DE CALIDAD

Responsabilidades:

- Revisar el código.
- Buscar errores de funcionamiento.
- Comprobar la coherencia entre archivos.
- Identificar posibles regresiones.
- Revisar las propuestas de modificación.
- Evaluar los resultados de las pruebas.

Ningún agente debe considerar correcta una propuesta solamente porque otro agente la haya realizado.

Las observaciones importantes deben sustentarse en código, pruebas o documentación verificable.

## 5. FLUJO OBLIGATORIO DE MODIFICACIONES

Toda modificación debe seguir este procedimiento:

1. Identificar el problema o la mejora.
2. Inspeccionar los archivos relacionados.
3. Investigar las causas.
4. Presentar una propuesta técnica.
5. Explicar beneficios, riesgos y archivos afectados.
6. Esperar autorización expresa del propietario.
7. Crear o utilizar una rama independiente.
8. Implementar únicamente el alcance autorizado.
9. Ejecutar las pruebas correspondientes.
10. Solicitar revisión independiente.
11. Presentar el resultado mediante un Pull Request.
12. Esperar aprobación final antes de incorporar los cambios a `main`.

**IMPORTANTE:**

Autorizar una investigación no significa autorizar una modificación.

Autorizar una modificación no significa autorizar su publicación.

La incorporación a la versión oficial siempre requiere aprobación final del propietario.

## 6. PROTECCIÓN DEL PROYECTO

Todos los agentes deben:

- Mantener intactos los archivos originales.
- Conservar respaldos de las versiones estables.
- Evitar cambios innecesarios en el código funcional.
- No almacenar credenciales ni información privada.
- No publicar información bancaria real.
- No realizar pruebas con transacciones reales sin autorización.
- No modificar configuraciones de seguridad sin autorización.

### Protección de MacroDroid

- No crear, modificar, importar ni reemplazar macros sin petición expresa.
- Preservar las configuraciones que ya funcionan.
- No incorporar PIN ni mecanismos sensibles de desbloqueo a nuevas macros.
- No modificar la integración bancaria sin evaluar previamente sus consecuencias.
- Mantener la compatibilidad con las notificaciones bancarias existentes.

### Protección de referencias bancarias

Las referencias deben conservar sus ceros iniciales.

Cuando se utilice reproducción de voz, los últimos cuatro dígitos deberán pronunciarse individualmente.

Ejemplos:

`0026` = cero, cero, dos, seis.

`4487` = cuatro, cuatro, ocho, siete.

No se deben eliminar ceros iniciales ni convertir referencias en cantidades numéricas.

## 7. PRIORIDADES ACTUALES DEL PROYECTO

El desarrollo debe avanzar en el siguiente orden:

### Prioridad 1: Diagnóstico

- Documentar el funcionamiento actual.
- Identificar las funciones existentes.
- Diferenciar funciones comprobadas de funciones pendientes.
- Preparar un plan de pruebas.

### Prioridad 2: Lectura de pagos

- Evaluar la extracción del monto.
- Comprobar formatos venezolanos.
- Verificar la lectura de referencias.
- Revisar la identificación del pagador.
- Evaluar la reproducción de voz.

### Prioridad 3: Historial

- Verificar el registro de pagos.
- Comprobar la prevención de duplicados.
- Revisar los totales.
- Evaluar los cierres de caja.
- Comprobar el almacenamiento local.

### Prioridad 4: Seguridad

- Revisar los parámetros recibidos por URL.
- Evaluar la representación segura de los datos.
- Revisar el almacenamiento local.
- Identificar posibles vulnerabilidades.

### Prioridad 5: Mejoras funcionales

- Proponer nuevas funcionalidades.
- Evaluar mejoras de interfaz.
- Optimizar el funcionamiento.
- Preparar pruebas de regresión.

## 8. FUTURA EVOLUCIÓN A UNA APLICACIÓN ANDROID

La futura migración a una APK nativa será una etapa independiente.

Cuando el propietario autorice su estudio, los agentes deberán investigar:

- Capacitor.
- Kotlin.
- Android Studio.
- Integración con funciones nativas de Android.
- Recepción y procesamiento de notificaciones.
- Permisos especiales.
- Funcionamiento en segundo plano.
- Alertas de pantalla completa.
- Reproducción de voz.
- Compatibilidad con diferentes fabricantes.
- Seguridad y privacidad.
- Consumo de batería.
- Generación y pruebas de APK.

No se debe iniciar una migración sin presentar previamente un plan técnico y obtener autorización.

La prioridad actual sigue siendo desarrollar y consolidar el prototipo existente.

## 9. DOCUMENTACIÓN OBLIGATORIA

Cada tarea debe registrar:

- Fecha.
- Agente responsable.
- Objetivo.
- Archivos inspeccionados.
- Problema detectado.
- Solución propuesta.
- Archivos modificados, si corresponde.
- Pruebas realizadas.
- Resultados.
- Limitaciones encontradas.
- Estado de aprobación.

Toda documentación debe estar redactada en español claro.

## 10. COMUNICACIÓN CON EL PROPIETARIO

El propietario no necesita conocimientos de programación para dirigir el proyecto.

Por lo tanto, todos los agentes deben:

- Explicar los conceptos técnicos de manera sencilla.
- Evitar tecnicismos innecesarios.
- Presentar instrucciones paso a paso.
- Informar claramente los riesgos.
- Explicar qué se modificará antes de hacerlo.
- Diferenciar resultados comprobados de suposiciones.
- No saturar al propietario con información innecesaria.

## 11. AUTORIDAD FINAL

Deivy Petrocelli es el propietario y máxima autoridad de decisión del proyecto TE PAGUÉ.

Los agentes pueden investigar, analizar, debatir, recomendar y desarrollar cambios autorizados.

Ningún agente tiene autoridad para:

- Modificar unilateralmente la versión oficial.
- Eliminar archivos originales.
- Publicar cambios sin autorización.
- Cambiar las prioridades generales.
- Tomar decisiones comerciales en nombre del propietario.

Toda decisión definitiva corresponde al propietario.

---

## PRINCIPIO RECTOR DEL EQUIPO

CONSTRUIR CON INTELIGENCIA.

REVISAR CON RIGOR.

PROTEGER LO QUE FUNCIONA.

DOCUMENTAR CADA AVANCE.

Y CRECER SIEMPRE CON LA AUTORIZACIÓN DEL PROPIETARIO.

**TE PAGUÉ — Un proyecto construido con inteligencia artificial, experiencia real y visión de futuro.**
