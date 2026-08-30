<div align="center">
  <img src="banner.png" alt="Carlos Pizarro — Ingeniería Estadística, Universidad de Santiago de Chile" width="100%">
</div>

# Hola, soy Carlos

Estudiante de **Ingeniería Estadística** en la Universidad de Santiago de Chile, con
formación previa en Ingeniería Matemática. Me interesa el análisis multivariante aplicado
a datos territoriales y sociales, y que el trabajo quede documentado de forma que
cualquiera pueda reproducirlo.

- 🎓 Busco práctica profesional en análisis de datos y estadística aplicada.
- 🧮 Trabajo en **R**, **Python** y **SQL**, documento con **Quarto** y versiono con **Git**.
- 🗣️ Hago clases de matemáticas desde 2018. Explicar bien un resultado es parte del oficio.
- 📄 **[Currículum](https://cpizarrof.github.io/cv/)**

## Tecnologías y herramientas

- **Lenguajes:** R · Python · SQL · LaTeX
- **Análisis y visualización:** RStudio · Quarto · tidyverse · ggplot2 · reveal.js
- **Control de versiones:** Git · GitHub · GitHub Pages
- **Otras:** Stata · Matlab · Java

## Proyectos destacados

### [La deprivación urbana en Chile no es unidimensional](https://github.com/cpizarrof/deprivacion-multivariante)

Análisis multivariante de **4.843 zonas censales urbanas** del Censo 2017 que pone a
prueba el índice oficial de deprivación territorial. El resultado es que una sola escala
no alcanza: hacen falta **tres componentes principales** (75,6 % de la varianza) y el
índice sólo ve la primera. El trabajo identifica **198 zonas** con las peores condiciones
de vivienda del país —29,3 % de población extranjera frente al 4,5 % nacional— a las que
el índice asigna una nota *más baja* que a la periferia clásica; el AUC para detectarlas
cae de **0,993 a 0,650** cuando el único predictor es el índice.

Componentes principales, análisis factorial, T² de Hotelling, MANOVA, clustering
jerárquico y particional, análisis de correspondencia y regresión logística con curva ROC.
Presentación construida en Quarto y reveal.js con vistas interactivas en JavaScript.

**[→ Ver la presentación](https://cpizarrof.github.io/deprivacion-multivariante/)** ·
[Código en R y Python](https://github.com/cpizarrof/deprivacion-multivariante/tree/main/codigo)

### [Percepción de la Gestión Institucional Preventiva](https://github.com/cpizarrof/pgip-psicometria)

Construcción y validación de una escala que mide cómo los apoderados perciben la gestión
preventiva de la violencia escolar, sobre **171.797 casos** del Simce 2024. La base se
ensambló uniendo tres fuentes —cuestionario de apoderados, resultados de la Agencia de
Calidad y Directorio Oficial del Mineduc— por el Rol Base de Datos.

La escala resultó unidimensional y consistente (**α ≈ 0,88**), e invariante frente a
grupo socioeconómico, dependencia, ruralidad y orientación religiosa. Las brechas entre
grupos resultan estadísticamente significativas pero **sustantivamente irrelevantes**:
explican menos del **0,5 %** de la varianza. Y el patrón no es el esperado — el GSE
**Medio Alto** puntúa más bajo (68,0) que el GSE **Bajo** (72,2), lo que apunta a un
sesgo de referencia más que a una diferencia real de gestión.

Análisis de ítems, confiabilidad por Teoría Clásica de los Tests, análisis factorial
confirmatorio con `lavaan`, invarianza, validez convergente y divergente con corrección
por atenuación, y construcción de una métrica escalar 0–100.

**[→ Ver la presentación](https://cpizarrof.github.io/pgip-psicometria/)**
