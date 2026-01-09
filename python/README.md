# Tarea Dev Junior - Ruuf

## 🎯 Objetivo

El objetivo de este ejercicio es poder entender tus habilidades como programador/a, la forma en que planteas un problema, cómo los resuelves y finalmente cómo comunicas tu forma de razonar y resultados.

## 🛠️ Problema

El problema a resolver consiste en encontrar la máxima cantidad de rectángulos de dimensiones "a" y "b" (paneles solares) que caben dentro de un rectángulo de dimensiones "x" e "y" (techo).

## 🚀 Cómo Empezar

### Opción 1: Solución en TypeScript
```bash
cd typescript
npm install
npm start
```

### Opción 2: Solución en Python
```bash
cd python
python3 main.py
```

## ✅ Casos de Prueba

Tu solución debe pasar los siguientes casos de prueba:
- Paneles 1x2 y techo 2x4 ⇒ Caben 4
- Paneles 1x2 y techo 3x5 ⇒ Caben 7
- Paneles 2x2 y techo 1x10 ⇒ Caben 0

---

## 📝 Tu Solución

Que tal amigos,
Pensé cómo obtener el resultado y llegué a la conclusión de sacarlos por metro cuadrado, que es lo más común cuando quieres saber por ejemplo cuántas cerámicas, necesitas para tu piso.  Pero antes de sacar los cálculos por metro cuadrado, primero hice validaciones de los posibles valores de entrada donde puede haber incongruencias.

Luego:
Multiplicas el largo y ancho del techo para obtener los metros cuadrados
Seguido multiplicas el largo y ancho del panel solar para obtener el metro cuadrado
Por último divide los metros cuadrados del techo por los metros cuadrados del panel solar y obtienes el resultado de las cantidades de paneles que necesitas.


Deja acá el link a tu video explicando tu solución con tus palabras

https://www.youtube.com/watch?v=LoKfkd2l_i0
---

## 💰 Bonus (Opcional)

Si completaste alguno de los ejercicios bonus, explica tu solución aquí:

### Bonus Implementado
*[Indica cuál bonus implementaste: Opción 1 (techo triangular) o Opción 2 (rectángulos superpuestos)]*




### Explicación del Bonus
*[Explica cómo adaptaste tu algoritmo para resolver el bonus]*




---

## 🤔 Supuestos y Decisiones

*[Si tuviste que tomar algún supuesto o decisión de diseño, explícalo aquí]*

