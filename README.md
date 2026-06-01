# 🌊 AXIOM_WATER_LOG // Monitor Biométrico de Hidratación

Plataforma SaaS móvil e interactiva de uso diario optimizada para la monitorización de la hidratación personal y el consumo volumétrico de agua según el desgaste biológico. 

Esta versión unifica un chasis visual reactivo con simulación de fluidos por hardware, un sistema bifásico de iluminación y un embudo de conversión perimetral conectado a servicios en la nube.

---

## 🛠️ Especificaciones Tecnológicas (Pila Core)

Para garantizar latencias de carga instantáneas en redes móviles y un consumo mínimo de batería, la aplicación se consolida de forma atómica en un **único archivo monolítico (`index.html`)** limitado estrictamente a un ancho de **480px**:

* **HTML5 Semántico:** Estructura pura optimizada para dispositivos táctiles móviles, agrupando el HUD superior, el cilindro hidrodinámico y la botonera de recipientes.
* **CSS3 Avanzado (Aceleración Nativa por GPU):**
    * **Ultra-Glass Chasis:** Capas esmeriladas translúcidas (`backdrop-filter: blur(20px) saturate(180%)`) con bordes finos adaptados al contraste del entorno.
    * **Conmutación Lumínica Bifásica:** Variables globales `:root` y electores `[data-theme]` para mutar la interfaz entre un modo claro puro y un modo oscuro profundo en microsegundos.
    * **Ondas Hidrodinámicas:** Animaciones infinitas con propiedades de rotación matricial (`@keyframes waveMotion`) para simular la oscilación del agua.
* **Vanilla JavaScript (ES6+ Strict Core):** Controlador de inyección de mililitros, manipulación en tiempo real del DOM y orquestación de llamadas OAuth asíncronas.
* **Librerías Críticas Integradas via CDN:**
    * `Supabase Client`: Gestión perimetral del motor de autenticación.
    * `GSAP`: Interpolaciones físicas y cinemática de muelles (*Spring Physics*) aplicadas a la oscilación de la botella y la carga del agua.
    * `Lenis`: Normalización y suavizado crítico del scroll táctil.
    * `Canvas-Confetti`: Detonador procedural de partículas cian, turquesa y plata para la celebración de metas de salud.

---

## 🏎️ Motores Lógicos y Embudo de Conversión

### 1. Canvas de Partículas Procedimentales
Un elemento `<canvas>` fijado en el fondo genera de manera matemática burbujas ascendentes. El script altera dinámicamente la opacidad, la velocidad y el color de las partículas en respuesta inmediata al cambio de tema lumínico del HUD.

### 2. Algoritmo de Hidratación Celular (Rust `no_std` Core Logic)
Al inyectar mililitros a través de las tarjetas elásticas (Taza, Botella, Termo), el script procesa localmente los volúmenes, actualiza el nivel de la malla del fluido y simula el cálculo matemático de una tasa de absorción celular por hora en función de la meta biológica diaria (2500ml).

### 3. Muro de Bloqueo Social (Supabase OAuth Gate)
Las opciones de almacenamiento avanzado (activar el historial semanal o telemetría renal) están protegidas mediante un interceptor de seguridad.
* **Transición Vertical Elástica:** Si el usuario no tiene sesión activa, la interfaz bloquea el paso desplazando verticalmente desde el fondo un modal *Ultra-Glass* con efectos ópticos.
* **Autenticación en Un Clic:** Integra de forma simétrica el inicio de sesión con **Google** y **Cuenta X (Twitter)** operados nativamente bajo Supabase Auth. Al validar la sesión, la UI transmuta y despliega el panel premium de estadísticas semanales.

---
  <sub>AXIOM SYSTEMS // WATER LOG PURIFIED // 100% HYDRO CELL SIMULATION // EDGE DRIVEN</sub>
</p>
