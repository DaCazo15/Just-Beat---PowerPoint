<p align="center">
  <a href="" rel="noopener">
 <img width=200px height=200px src="https://i.postimg.cc/kMTbTZQD/Just_Beats.jpg"></a>
</p>

# 🎮 Just Beats

**Just Beats** es un prototipo de videojuego interactivo desarrollado íntegramente en **Microsoft PowerPoint**. Utiliza la lógica de "eventos al pasar el cursor" para simular colisiones, trampas y navegación, ofreciendo una experiencia jugable técnica y creativa sin necesidad de programación tradicional.

---

## 🧠 Concepto
Inspirado en la estética de los juegos rítmicos y minimalistas, este proyecto propone una dinámica de movimiento libre. El desafío radica en la precisión del usuario para navegar por mapas complejos dentro de una presentación de diapositivas transformada en un entorno interactivo.

## 🕹️ Mecánicas de Juego
* **Control por cursor:** El movimiento del mouse es tu personaje.
* **Colisiones simuladas:** Las formas actúan como disparadores (*triggers*). Si el cursor toca un obstáculo, se activa automáticamente la transición a la pantalla de derrota.
* **Objetivo:** Navegar desde el punto de inicio hasta la zona de meta.
* **Estados del juego:** Sistema de navegación fluido entre menús, niveles y estados de victoria/derrota.

### 🧩 Leyenda Visual
| Elemento | Color | Función |
| :--- | :--- | :--- |
| **Meta** | 🔴 Rojo | Zona de victoria (avanza al siguiente nivel) |
| **Enemy** | 🔵 Azul | Obstáculo (activa la pantalla de *Perdiste*) |

---

## 🗺️ Estructura del Juego

### Pantallas Principales
* **JUST BEATS:** Menú de inicio.
* **Play:** Acceso principal a los niveles.
* **ZI.Code:** Firma del desarrollador.
* **Niveles 1–8:** Mapas con obstáculos y rutas progresivas.
* **Boss:** Desafío final de alta dificultad.
* **Ganaste / Perdiste:** Pantallas de estado final.

### Flujo del Juego
```

[Inicio]
   |
   ▼
[Play] ──▶ [Nivel 1]
             |
             ▼
         [Nivel 2]
             |
             ▼
         [Nivel 3]
             |
             ▼
         [Nivel 5]
             |
             ▼
         [Nivel 6]
             |
             ▼
         [Nivel 7]
             |
             ▼
           [Boss]
             |
     ┌───────┴────────┐
     ▼                ▼
[Ganaste]         [Perdiste]
     |                |
     └───────┬────────┘
             ▼
          [Volver]

```
---

## 🛠️ Especificaciones Técnicas
* **Formato:** `.ppsx` (Microsoft PowerPoint Slide Show).
* **Plataforma:** Microsoft PowerPoint.
* **Interacción:** Eventos al pasar el cursor (*Mouse Over*) y navegación por hipervínculos.

## 🚀 Cómo Jugar
1.  Abre el archivo `Just Beats.ppsx`.
2.  Haz clic en **Play** para comenzar.
3.  Mueve el cursor con precisión evitando los obstáculos azules.
4.  Si colisionas, verás la pantalla de **Perdiste**. Si llegas a la meta roja, verás **Ganaste**.
5.  Usa el botón **Volver** para reintentar o explorar otras secciones.

---

## 📈 Próximos Pasos (Roadmap)
* [ ] **Dificultad Escalonada:** Añadir niveles con obstáculos móviles sincronizados.
* [ ] **Audio Integrado:** Música rítmica que acompañe la acción.
* [ ] **Migración a Engine:** Portar el prototipo a motores como **Unity** o **Godot**.
* [ ] **Editor de Niveles:** Crear una base para que otros usuarios diseñen sus desafíos.

---

## ✍️ Autoría
* **Desarrollador:** ZI.Code
* **Diseño Visual y Mecánica:** Daniel
* **Ubicación:** Nueva Esparta, Venezuela 🇻🇪 (UDONE)

---
> **Nota:** Este proyecto demuestra el potencial de las herramientas de oficina para la creación de prototipos rápidos y lógica de videojuegos experimental.
