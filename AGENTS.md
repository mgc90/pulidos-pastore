# AGENTS.md

# Pulidos Pastore

Sitio web oficial de Pulidos Pastore.

Comienza como una landing page, pero podrá crecer en el futuro. Diseñar únicamente para las necesidades actuales; no anticipar funcionalidades.

---

## Stack

- Astro
- Tailwind CSS
- TypeScript

No agregar dependencias sin consultar.

---

## Principios

Priorizar siempre:

- simplicidad;
- eficiencia;
- rendimiento;
- mantenibilidad;
- código mínimo.

La solución más simple suele ser la correcta.

---

## Hero

La página principal tendrá un Hero compuesto por:

- hasta 3 videos;
- reproducción automática;
- en silencio;
- en bucle;
- overlay oscuro.

Sobre los videos se mostrará un par:

- título;
- subtítulo.

Cada par cambiará cada 7 segundos.

No asumir animaciones, transiciones ni comportamientos no especificados. Preguntar.

---

## Colores

| Nombre | Valor | Uso |
|--------|--------|-----|
| `wood-dark` | `#4A2C17` | Marrón madera oscura |
| `wood-light` | `#9C6B3E` | Marrón madera clara. Acentos y CTAs |
| `marble` | `#2B2A28` | Gris mármol oscuro. Texto y fondos |
| `marble-shine` | `#9A948A` | Variante clara del mármol |

---

## Reglas

- No asumir decisiones de diseño.
- No agregar funcionalidades no solicitadas.
- No crear abstracciones innecesarias.
- No instalar librerías sin consultar.
- No modificar código que no esté relacionado con la tarea.
- Si falta información, preguntar.
- Si existen varias opciones, presentarlas antes de implementar.

---

# Guía de comportamiento

## 1. Pensar antes de programar

- Expón tus suposiciones.
- Si tienes dudas, pregunta.
- Si existen varias interpretaciones, preséntalas.
- Si existe una solución más simple, proponla.
- No adivines.

---

## 2. La simplicidad primero

Escribe únicamente el código necesario.

No agregues:

- funcionalidades futuras;
- abstracciones innecesarias;
- configuraciones que nadie pidió;
- manejo de errores para escenarios imposibles.

Si algo puede resolverse con menos código, simplifícalo.

---

## 3. Cambios quirúrgicos

Modifica únicamente lo necesario.

- No refactorices código que funciona.
- No cambies estilo, formato o comentarios sin motivo.
- Elimina únicamente el código que tus propios cambios hayan dejado sin uso.
- Si encuentras problemas no relacionados, menciónalos pero no los corrijas.

---

## 4. Trabajar por objetivos

Antes de implementar:

1. Explica brevemente el plan.
2. Define cómo verificarás el resultado.
3. Comprueba que todo funciona antes de finalizar.

No des una tarea por terminada sin verificarla.