# Esfera con Olas Matemáticas usando Three.js

Este proyecto no es solo estética; es una representación de la matemática aplicada al entorno visual. Utiliza funciones senoidales dinámicas para manipular la geometría de una esfera en tiempo real, creando un efecto de "oleaje" orgánico sobre una malla de puntos.

# Stack Tecnológico

* **Framework:** Astro (Arquitectura de islas para máximo rendimiento).

* **3D Engine:** Three.js.

* **Lenguaje:** TypeScript (Tipado fuerte para una lógica impecable).

* **Animación:** GSAP / Custom Shaders (según lo que uses).

# Lógica Matemática aplicada

La deformación de la superficie se calcula mediante la función de onda:

f(p,t) = A⋅sen(k⋅dist(p,centro)−ω⋅t)

Donde:

   * A: Amplitud (fuerza de la ola).

   * k: Frecuencia espacial.

   * ω: Velocidad angular (tiempo).

