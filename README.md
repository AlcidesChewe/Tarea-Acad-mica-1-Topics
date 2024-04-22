# Tópicos en Ciencias de la Computación - TAREA ACADÉMICA 1

## Información del Curso
**Profesor:** Luis Martin, Canaval Sanchez  
**Sección:** CC82  
**Fecha:** Enero 2024

## Integrantes
- Charapaqui Reluz, Rommel Alcides - U202021294
- Barrionuevo Gutierrez, Daniel Ulises - U201922128
- Castilla Ochoa, Carlos Alonso - U202116277

## Aplicación de Programación por Restricciones (CSP) en la Asignación de Tripulación Aérea

### Introducción
En la presente tarea académica, nos proponemos abordar el desafiante problema de la asignación de tripulaciones aéreas a los vuelos de una aerolínea. Este problema implica no solo la óptima distribución del personal sino que también debe atender a diversas restricciones y preferencias, lo que lo convierte en un candidato ideal para la aplicación de técnicas de Programación por Restricciones (CSP).

### Problema y Motivación
El problema seleccionado para esta investigación surge de la necesidad de optimizar la asignación de los 20 miembros de la tripulación aérea a 10 vuelos diferentes, garantizando la cobertura adecuada de azafatas y auxiliares de vuelo por vuelo y asegurando que se cumplan los requerimientos lingüísticos y operativos. La motivación detrás de este estudio radica en mejorar la eficiencia operativa y la satisfacción del personal de la aerolínea, elementos críticos en la industria de la aviación.

### Objetivos
**Objetivo General:**  
Desarrollar un modelo de CSP que optimice la asignación de la tripulación aérea, satisfaciendo todas las restricciones y preferencias establecidas.

**Objetivos Específicos:**
- Identificar y definir las variables, dominios y restricciones relevantes para el modelo de CSP.
- Aplicar técnicas de programación por restricciones para la resolución del problema de asignación.
- Evaluar la eficacia del modelo propuesto mediante simulaciones y comparaciones con asignaciones actuales.

**Función Objeto:**  
Optimizar la asignación de los 20 miembros de la tripulación aérea a 10 vuelos diferentes, garantizando la cobertura adecuada y cumpliendo con los requerimientos lingüísticos y operativos, haciendo uso de CSP.

### Marco Teórico
1. **Fundamentos de la Programación por Restricciones (CSP):**
   - Definición de CSP: Presenta una explicación detallada sobre qué es CSP, incluyendo su historia y desarrollo en el campo de la inteligencia artificial.
   - Componentes clave de CSP: Variables, dominios y restricciones; cómo cada componente se utiliza para formular problemas y encontrar soluciones.

2. **Técnicas de Solución en CSP:**
   - Búsqueda y Retroceso (Backtracking): Describe el algoritmo de búsqueda y retroceso, una técnica fundamental en CSP que permite encontrar soluciones al probar combinaciones de valores y retrocediendo cuando se encuentra con una restricción que no se puede satisfacer.
   - Consistencia y Propagación de Restricciones: Explica cómo la propagación de restricciones se utiliza para simplificar el espacio de búsqueda y aumentar la eficiencia del proceso de solución.

3. **Aplicaciones de CSP en la Asignación y Planificación:**
   - Estudios de Caso Relacionados: Proporciona ejemplos de cómo CSP se ha utilizado exitosamente para resolver problemas similares en la asignación de recursos o planificación de horarios.

4. **Aspectos Computacionales de CSP:**
   - Solucionadores de CSP y Herramientas de Programación: Presenta las herramientas de software más comunes para trabajar con CSP, como MiniZinc o Choco Solver, y cómo se integran en ambientes de desarrollo como Python o Java.

5. **Relevancia del CSP en la Industria de la Aviación:**
   - Eficiencia Operativa y Satisfacción del Personal: Relaciona los beneficios potenciales de un sistema optimizado de asignación de tripulación con el rendimiento operativo y la moral del personal.

### Planteamiento del Problema
Para el planteamiento de este problema, consideraremos las siguientes variables y restricciones:
- **Variables:** Cada variable representará a un miembro de la tripulación y su asignación a un vuelo específico.
- **Dominios:** Los dominios estarán compuestos por los vuelos disponibles que cada miembro de la tripulación podría operar.
- **Restricciones:**
  - Restricciones de cantidad de personal por vuelo.
  - Requerimientos lingüísticos por vuelo.
  - Restricciones de no asignación múltiple para un mismo miembro de la tripulación.

Se detallará el modelo de CSP propuesto, incluyendo las funciones de filtrado y propagación de restricciones que reducirán el espacio de búsqueda y facilitarán la solución del problema.
