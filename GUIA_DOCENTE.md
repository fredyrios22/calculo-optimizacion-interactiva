# Guía docente — Sesión 15: Optimización y modelación

**Autor:** John Fredy Ríos Restrepo.

**Público:** estudiantes de primer semestre de Ingeniería en Cálculo Diferencial.  
**Duración:** 90 minutos de clase; el trabajo independiente no está incluido.

## Objetivos de aprendizaje
1. Identificar variables, restricciones y función objetivo.
2. Construir y analizar el dominio admisible.
3. Calcular puntos críticos y justificar extremos absolutos.
4. Explicar por qué una exploración numérica no equivale a una demostración.

## Secuencia de clase
| Etapa | Tiempo | Preguntas e intervenciones |
|---|---:|---|
| Inicio | 10 min | ¿Una caja más alta siempre tiene mayor volumen? Recoger predicciones antes de mostrar el simulador. |
| Simulador | 15 min | Variar x, observar base y volumen. ¿Qué pasa cerca de los límites? Pedir registrar conjetura. |
| Modelo | 15 min | ¿Por qué cada lado de la base pierde 2x? ¿Qué significa x=15? |
| Derivadas | 20 min | Resolver V'=0; discriminar soluciones admisibles; estudiar signos de V' para probar máximo absoluto. |
| Práctica | 15 min | Ejemplo del cercado; actividades con soluciones ocultas. |
| Evaluación | 10 min | Dos retos con criterios publicados en la web. Pedir argumentos, no solo resultados. |
| Cierre | 5 min | Sintetizar modelación y asignar trabajo independiente. |

## Fundamento matemático
Para una lámina de 30×30 cm: V(x)=x(30−2x)², 0<x<15. V'(x)=12(x−5)(x−15). V' positiva en (0,5) y negativa en (5,15). Máximo absoluto: V(5)=2000 cm³, caja de 20×20×5 cm. No existe mínimo absoluto en el dominio abierto; ínfimo 0.

## Dificultades anticipadas
- Confundir aumento de altura con aumento de volumen: comparar recortes x=2, 5, 10.
- Considerar x=15 solución física porque V'(15)=0: exigir dominio y explicación geométrica.
- Inferir máximo absoluto únicamente de V''(5)<0: distinguir criterio local de argumento global por monotonía.

## Verificación del simulador
El control restringe x a [0.5,14.5] con pasos de 0.1 cm para evitar cajas degeneradas. La función matemática admite todo 0<x<15; el deslizador muestra un subconjunto. Las dimensiones y el volumen se calculan directamente con x, 30−2x y x(30−2x)². La gráfica SVG representa esa función sobre [0,15] solo como referencia visual, incluyendo los valores límite de volumen 0 en extremos que **no pertenecen** al dominio físico.

## Trabajo independiente
Lámina rectangular de 30×20 cm: V=x(30−2x)(20−2x), 0<x<10. Derivada V'=12x²−200x+600. Solución óptima x=(25−5√7)/3 cm, con prueba por signos. Respuesta en la web.

## Entrega y pendientes
Abrir index.html en un navegador moderno, sin instalación. Publicar en alojamiento web estático y comprobar el enlace público, los permisos, los botones, los cálculos y la visualización en móvil. Personalizar identificación del estudiante. Incorporar bibliografía **realmente consultada** y declaración de IA con herramienta, empresa, modelo/versión, plan, fechas, aportes y procedimiento de verificación. No se deben inventar referencias ni fechas.

## Transparencia de IA
Se utilizó ChatGPT (OpenAI, GPT-6) como apoyo para redactar el prototipo, la guía y las explicaciones en noviembre de 2026. El autor revisó el prototipo visualmente y tomó decisiones sobre el recorrido didáctico. Antes de entregar, consultar DECLARACION_IA.md (plan ChatGPT Plus confirmado) y documentar la verificación integral efectivamente realizada. Incorporar solo bibliografía consultada.


## Bibliografía de referencia del curso
Smith, Robert T.; Minton, Roland B.; Rafhi, Ziad A. T. *Cálculo: trascendentes tempranas*. Quinta edición. McGraw Hill (la ficha aportada indica McGraw Hill Interamericana y 2019). ISBN indicado en la ficha: 9781456269876; ISBN ebook: 9781456271428. **Nota de verificación:** la portada presenta título en español y tres autores, mientras la ficha indica idioma inglés y solo a Robert Smith; no se ha confirmado que los ISBN y el año correspondan exactamente a la edición de la portada.
