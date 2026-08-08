# Trilladora de Cartago - Coffee Roaster Monitor

![Miniatura del Proyecto](./assets/minuatura.jpg)

[🇪🇸 Español](#español) | [🇬🇧 English](#english)

---

<a name="español"></a>
## 🇪🇸 Sistema de Monitoreo de Tostación de Café

Solución económica, robusta y de código abierto diseñada para el monitoreo en tiempo real de temperaturas y curvas de tostación, creada como una alternativa de bajo costo en reemplazo de módulos comerciales costosos para la trilladora de Cartago.

### 🚀 Características Principales
* **Lectura Dual de Temperatura:** Monitoreo simultáneo del **Tambor** y la **Tolva** mediante termocuplas de alta precisión.
* **Visualización Local:** Pantalla TFT integrada para ver el estado del proceso, tiempo transcurrido y la evolución gráfica de las curvas de temperatura y RoR (Rate of Rise).
* **Control Industrial:** Interfaz de control mediante interruptor industrial (Normally Open) con lógica antirrebote y lectura estable adaptada a entornos ruidosos.
* **Compatibilidad:** Envío de datos por puerto serial para integración con software de gestión y registro de tuestes (como Artisan).

### 🎥 Video y Funcionamiento del Sistema
Puedes ver el video de demostración y funcionamiento del sistema dentro de la carpeta [`assets/`](./assets/).

### 🛠️ Hardware Utilizado
* **Microcontrolador:** Arduino Uno.
* **Sensores de Temperatura:** 2 x Módulos MAX6675 con termocuplas.
* **Pantalla:** Pantalla TFT 1.8" (Driver ST7735 con Hardware SPI).
* **Interfaz de Control:** Interruptor industrial (Conectado a pines A2 y GND con resistencia pull-up interna).

### 🔮 Futuras Mejoras
* **Diseño de PCB:** Fabricación de una tarjeta de circuito impreso propia optimizada utilizando **KiCad**.
* **Migración a ESP32:** Sustitución del Arduino Uno por un ESP32 para dotar al sistema de conectividad inalámbrica y comunicación directa con **Artisan vía protocolo TCP**.

### 👨‍💻 Autor
* **Juan Sebastián Valencia Londoño** 
* *Código asistido con IA*

---

<a name="english"></a>
## 🇬🇧 Coffee Roasting Monitoring System

An economical, robust, and open-source solution designed for real-time temperature monitoring and roasting curves, created as a low-cost alternative to expensive commercial modules for the Cartago coffee mill.

### 🚀 Main Features
* **Dual Temperature Reading:** Simultaneous monitoring of the **Drum** and **Hopper** using high-precision thermocouples.
* **Local Display:** Integrated TFT screen to view process status, elapsed time, and the graphical evolution of temperature curves and RoR (Rate of Rise).
* **Industrial Control:** Control interface via an industrial switch (Normally Open) with debounce logic and stable readings adapted to noisy environments.
* **Compatibility:** Serial port data transmission for integration with roast logging software (such as Artisan).

### 🎥 System Operation & Video
You can watch the system operation and demonstration video inside the [`assets/`](./assets/) folder.

### 🛠️ Hardware Used
* **Microcontroller:** Arduino Uno.
* **Temperature Sensors:** 2 x MAX6675 modules with thermocouples.
* **Display:** 1.8" TFT Screen (ST7735 driver with Hardware SPI).
* **Control Interface:** Industrial switch (Connected to pins A2 and GND with internal pull-up resistor).

### 🔮 Future Improvements
* **PCB Design:** Fabrication of a custom optimized printed circuit board using **KiCad**.
* **Migration to ESP32:** Replacing the Arduino Uno with an ESP32 to provide wireless connectivity and direct communication with **Artisan via TCP protocol**.

### 👨‍💻 Author
* **Juan Sebastián Valencia Londoño** 
* *AI-assisted code*
