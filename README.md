# ✝ CRUZADAS ☪ — Simulador de Naciones

Juego de estrategia por turnos ambientado en la **Era de las Cruzadas (1095 A.D.)**.
Controlas una potencia medieval (cristiana u musulmana), administras recursos, conquistas territorios y tomas decisiones narrativas para alcanzar la supremacía.

## 🎮 ¿De qué trata?
En cada partida eliges una facción histórica y juegas hasta 100 turnos (años). Tu objetivo es consolidar tu reino mediante:

- **Guerra y expansión territorial**.
- **Gestión económica** (oro e ingresos por turno).
- **Fe, cultura y prestigio**.
- **Diplomacia** (alianzas y conflictos).
- **Eventos aleatorios** que cambian el rumbo de la partida.

## 🗺️ Mecánicas principales

- **Mapa interactivo en SVG** con territorios conectados por fronteras.
- **Selección de nación inicial** con estadísticas y bonificaciones distintas.
- **Sistema de acciones por turno** (3 acciones):
  - Reclutar tropas.
  - Recaudar impuestos.
  - Fortalecer defensas.
  - Declarar guerra / atacar.
  - Enviar misiones religiosas.
  - Impulsar cultura.
  - Proponer alianzas.
  - Construir mercados.
- **IA de facciones rivales**, que recluta, se expande y te puede conquistar territorios.
- **Eventos narrativos** (plagas, cruzadas, yihad, revueltas, caravanas, etc.) con decisiones de riesgo/recompensa.

## 🏆 Condiciones de victoria
Ganas la partida si cumples **una** de estas condiciones:

1. Alcanzar **500 de prestigio**.
2. Controlar **Jerusalén** y tener al menos **8 territorios**.

## ☠️ Condiciones de derrota
Pierdes si ocurre cualquiera de estas situaciones:

- Te quedas sin territorios.
- Colapsas por bancarrota extrema (oro muy negativo y ejército mínimo).
- Llegas al final de los 100 turnos sin cumplir una condición de victoria.

## ▶️ Cómo jugar

1. Abre el archivo `cruzadas.html` en tu navegador.
2. Elige una facción en la pantalla inicial.
3. Selecciona territorios en el mapa y usa tus acciones.
4. Finaliza turno para procesar economía, IA y eventos.

> No requiere instalación ni dependencias: es un juego **HTML + CSS + JavaScript vanilla** en un único archivo.

## 🧠 Consejos rápidos

- No gastes todo tu oro: necesitarás reservas para guerra y eventos.
- Fortalece fronteras clave antes de expandirte demasiado.
- Usa alianzas para estabilizar frentes peligrosos.
- Jerusalén da una ventaja fuerte de fe/prestigio: planifica su control.

## 📁 Estructura del proyecto

- `cruzadas.html`: juego completo (interfaz, lógica, eventos e IA).
- `README.md`: documentación general del proyecto.

## 📜 Licencia

Si vas a publicar o distribuir el proyecto, te recomiendo añadir una licencia explícita (por ejemplo, MIT) en un archivo `LICENSE`.
