# 🌍 Viajero Planner — Planificador y Bitácora Universal de Viajes

> Tu compañero de viajes inteligente: gestiona presupuestos, divide gastos entre viajeros en tiempo real, compara precios de tours y sigue tu itinerario día a día. Diseñado para celular (*mobile-first*) y funcional offline.

📱 **Pruébalo en vivo:** [https://alasli09.github.io/viajero-planner/](https://alasli09.github.io/viajero-planner/)

---

## ✨ Características Principales

### 1. 🚀 Asistente de Inicio (Onboarding Wizard)
* **Crear viaje desde cero:** Configura el nombre del viaje, fechas de inicio y fin, destinos, monedas (COP, USD, EUR, MXN, etc.), TRM estimada y quiénes viajan.
* **Cargar Plantilla de Ejemplo:** Permite explorar el viaje completo a Europa (Madrid, Roma, París, Disneyland, Inter de Milán) como modelo base.

### 2. ⚖️ Bitácora y Cuentas Claras (Balance entre Viajeros)
* **Adaptable a cualquier grupo:** Funciona tanto para viajes en pareja (Alan & Hillary, Carlos & Andrea), viajes individuales o grupos de amigos (3 o más personas).
* **Cálculo de Deudas en Lenguaje Natural:** Indica al instante quién pagó de más y cuánto le debe a quién (ej: *"Hillary le debe a Alan: $45.000 COP"*).
* **Interactivo:** Toca el balance para ver los gastos detallados o filtrar exclusivamente los desembolsados por un viajero.
* **Buscador en tiempo real:** Encuentra cualquier gasto al instante por palabra clave (comida, taxi, metro, café).

### 3. 📋 Exportación a Excel Personal
* Botón **«Copiar Filas»** que copia los gastos directamente al portapapeles con formato tabular listo para pegar en hojas de cálculo mensuales:
  `Fecha \t Monto \t Deudor \t Observación \t Método`

### 4. 💰 Presupuesto Base (Piso)
* Organizado en: **Transportes**, **Alojamientos** y **Experiencias**.
* **Filtros rápidos:** Filtra por `⏳ Solo Pendientes`, `✅ Solo Pagados`, o por categorías.
* **Buscador:** Encuentra vuelos, hoteles o reservas en segundos.
* **Edición interactiva:** Toca cualquier ítem para cambiar montos, cuotas o estado.

### 5. 🗺️ Itinerario en Vivo
* Generación dinámica de días según la duración del viaje.
* Visualización de vuelos, trenes y planes fijos con horas locales.
* **Gestor de Días Pasados:** Marca días como "Pasados" para archivarlos y mantener limpio el timeline activo.

### 6. 📁 Gestor Multi-Viaje
* Guarda múltiples viajes en un solo navegador (ej: *EuroTrip 2026*, *Vacaciones en Cancún*, *Paseo Fin de Año*).
* Cambia entre viajes con un solo toque desde el encabezado.

---

## 📲 Cómo Compartirlo con un Amigo

1. Envíale el enlace público de GitHub Pages: `https://alasli09.github.io/viajero-planner/`
2. Al abrirlo en su celular:
   * Le aparecerá el asistente de bienvenida para **crear su propio viaje desde cero** o **ver la plantilla de ejemplo**.
   * Todos sus datos se guardarán de forma privada en su propio teléfono (`localStorage`).
   * No requiere registro ni pagar servidores.

---

## 🛠️ Tecnologías
* **HTML5 + Tailwind CSS (CDN)** — Interfaz moderna y responsive orientada a smartphones.
* **JavaScript Puro (ES6+)** — Rápido, liviano, sin dependencias pesadas.
* **LocalStorage API** — Almacenamiento local persistente sin backend.
* **GitHub Pages** — Despliegue estático gratuito y seguro.

---

Desarrollado con ❤️ para viajeros.
