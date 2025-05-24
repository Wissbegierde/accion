# Simulador de la Curva Braquistócrona

Un simulador interactivo que demuestra el principio de la curva braquistócrona - la curva más rápida entre dos puntos bajo la influencia de la gravedad.

## ¿Qué es la Curva Braquistócrona?

La curva braquistócrona es la curva que permite que una partícula se deslice desde un punto A hasta un punto B en el menor tiempo posible bajo la influencia de la gravedad uniforme. Fue descubierta por Johann Bernoulli en 1696 y resulta ser una cicloide.

## Características del Simulador

### ✨ Funcionalidades Principales

- **Comparación de trayectorias**: Simula simultáneamente tres caminos diferentes:
  - Línea recta (roja)
  - Curva braquistócrona (azul) - siempre la más rápida
  - Curva personalizable (verde)

- **Interactividad total**:
  - Haz clic en los puntos A y B para modificar posiciones
  - Arrastra los puntos de control de la curva personalizada
  - Ajusta el peso y tamaño de las bolitas en tiempo real

- **Controles físicos**:
  - Peso de las bolitas (0.1 - 2.0 kg)
  - Radio de las bolitas (5 - 20 px)
  - Física realista basada en gravedad

- **Medición de tiempos**: Cronómetro preciso para cada trayectoria

### 🎮 Cómo Usar

1. **Abrir el simulador**: Simplemente abre `index.html` en tu navegador
2. **Configurar puntos**: Haz clic cerca de los puntos A o B para reposicionarlos
3. **Personalizar curva**: Arrastra los puntos naranjas numerados para modificar la curva verde
4. **Ajustar parámetros**: Usa los deslizadores para cambiar peso y tamaño de las bolitas
5. **Iniciar simulación**: Presiona "Iniciar Simulación" y observa los resultados
6. **Agregar puntos**: Usa "Agregar Curva Personalizada" para añadir más puntos de control

### 🔬 Principio Físico

El simulador demuestra que:
- La línea recta NO es siempre la más rápida
- La curva braquistócrona (cicloide) siempre gana
- Las curvas que "caen" más rápido al inicio pueden compensar la distancia extra

## Estructura del Proyecto

```
accion/
├── index.html          # Interfaz principal
├── styles.css          # Estilos modernos y responsivos
├── script.js           # Lógica del simulador y cálculos físicos
└── README.md           # Documentación
```

## Tecnologías Utilizadas

- **HTML5 Canvas**: Para renderizado de gráficos y animaciones
- **JavaScript ES6+**: Programación orientada a objetos
- **CSS3**: Interfaz moderna con gradientes y efectos
- **Matemáticas**: Ecuaciones paramétricas de cicloide para la braquistócrona

## Instalación y Ejecución

No requiere instalación. Simplemente:

1. Clona o descarga el repositorio
2. Abre `index.html` en cualquier navegador moderno
3. ¡Empieza a experimentar!

## Detalles Técnicos

### Cálculo de la Braquistócrona

La curva braquistócrona se calcula usando las ecuaciones paramétricas de una cicloide:
```
x = R(t - sin(t))
y = R(1 - cos(t))
```

### Simulación Física

- Velocidad basada en conservación de energía: `v = √(2gh)`
- Actualización en tiempo real usando `requestAnimationFrame`
- Física simplificada pero demostración efectiva del principio

## Próximas Mejoras

- [ ] Añadir fricción y resistencia del aire
- [ ] Múltiples bolitas simultáneas
- [ ] Exportar resultados a CSV
- [ ] Modo de comparación con datos históricos
- [ ] Animaciones más suaves con interpolación

## Contribuciones

¡Las contribuciones son bienvenidas! Este es un proyecto educativo perfecto para:
- Estudiantes de física y matemáticas
- Desarrolladores interesados en simulaciones
- Educadores que buscan herramientas interactivas

---

**Creado para demostrar uno de los problemas más elegantes de la física matemática** 🚀
