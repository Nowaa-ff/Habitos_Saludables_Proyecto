# Ruta de Hábitos: Compañeros de Bienestar RPG 🐾

**Proyecto Interdisciplinario de Biología e Informática**  
**Escuela Técnica de la Universidad de Mendoza (ETec)** — 3er Año Informática (2026)

---

## 👥 Integrantes del Grupo
- **Noa Fischer** 
- **Constanza Smaha** 
- **María Villalobos**
- **Paulina Olguin** 
- **Amparo Salinas**

---

## 📖 Descripción del Proyecto

**Ruta de Hábitos: Compañeros de Bienestar RPG** es una aplicación web educativa e interactiva diseñada para fomentar hábitos saludables en estudiantes adolescentes mediante mecánicas de gamificación (RPG) y acompañamiento virtual.

El objetivo principal es transformar el cuidado de la salud física, mental y digital en una experiencia cotidiana motivadora: cada acción saludable cumplida en la vida real (hidratarse, desayunar, descansar bien, mantener una postura erguida o realizar pausas activas) otorga **Experiencia (XP)**, **Monedas de Oro**, **Rachas de Constancia** y permite cuidar y personalizar a un compañero virtual evolutivo.

---

## 🧬 Abordaje Interdisciplinario

### 1. Área de Biología y Promoción de la Salud
La plataforma incluye una **Academia de Hábitos Saludables** con 6 módulos fundamentados científicamente y un cuestionario interactivo de autoevaluación sobre temas clave para la etapa escolar:
- **💧 Hidratación y Rendimiento Cerebral:** Importancia del agua en la transmisión neuronal (75% de composición cerebral), semáforo de hidratación y calculadora personalizada según peso corporal y actividad física.
- **🥗 Nutrición Inteligente y Plato Saludable:** Distribución equilibrada de macronutrientes (50% frutas y verduras, 25% cereales integrales, 25% proteínas) e impacto de los alimentos ultraprocesados y azúcares libres en la glucemia.
- **🌙 Arquitectura del Sueño y Memoria:** Consolidación de la memoria a largo plazo durante el sueño profundo, limpieza metabólica neuronal y efecto inhibitorio de la luz azul sobre la **melatonina**.
- **🏃 Actividad Física y Ergonomía Escolar:** Prevención del *cuello de texto*, postura correcta en el pupitre (regla de los 90°), peso adecuado de la mochila escolar (máximo 10%–15% del peso corporal) y pausas activas.
- **🧠 Salud Mental y Manejo del Estrés:** Regulación del sistema nervioso parasimpático mediante la respiración guiada **4-7-8** y organización del estudio con el **Método Pomodoro**.
- **🔬 Bienestar Digital y Ciencia de los Hábitos:** Protección ocular con la **regla 20-20-20** y neurociencia del bucle del hábito (*Señal → Rutina → Recompensa*).

### 2. Área de Informática y Desarrollo Web
El proyecto fue desarrollado como una **Single Page Application (SPA)** ligera, responsiva y autocontenida:
- **Tecnologías utilizadas:** HTML5 semántico, Tailwind CSS para diseño responsivo *mobile-first*, JavaScript moderno (ES6+), gráficos vectoriales dinámicos en **SVG** y síntesis de efectos de sonido en tiempo real mediante **Web Audio API**.
- **Persistencia de datos:** Almacenamiento local estructurado (`localStorage`) con control automático de cambio de día, cálculo de rachas consecutivas, historial semanal de 7 días y sistema de escudos protectores.
- **Alertas y Temporizadores:** Notificaciones programables en tiempo real (`Notification API` + alarmas sonoras) y cronómetro integrado para bloques de estudio y pausas activas.
- **Despliegue en la nube:** Control de versiones en **GitHub** (`Nowaa-ff/ruta-de-habitos`) y despliegue continuo en **Vercel**.

---

## ✨ Funcionalidades Principales

- **🐉 Compañero Virtual Personalizable:** 10 especies disponibles (Dragón, Zorro, Búho, Axolote, Panda, Gatito, Lobito, Osito, Pingüino y Capibara), 8 paletas de colores, 5 personalidades con diálogos motivacionales y reacciones animadas según el cumplimiento de metas.
- **✅ Gestor de Hábitos y Retos Escolares:** Creación de hábitos diarios o repetibles con niveles de dificultad, seguimiento de rachas individuales y catálogo de retos saludables preconfigurados.
- **💧 Contador Interactivo de Hidratación:** Registro visual de vasos de 250 ml hasta alcanzar la meta diaria de 2 litros.
- **⏱️ Zona de Enfoque y Calma:** Temporizador integrado con modos de **Estudio (25 min)**, **Pausa Activa (5 min)** y **Respiración Guiada 4-7-8**.
- **🛍️ Tienda del Bosque Místico:** Canje de monedas ganadas por accesorios (cabeza, cuerpo, mano, auras, mini-mascotas), escenarios de fondo y consumibles como el *Escudo de Racha*.
- **🎓 Credencial Escolar Compartible:** Resumen exportable con estadísticas, medallas desbloqueadas y evolución del estudiante para presentar en clase.

---

## 🚀 Estructura del Repositorio

```text
ruta-de-habitos/
├── index.html      # Aplicación web completa (Interfaz, estilos, lógica RPG y Academia de Salud)
└── README.md       # Documentación institucional y técnica del proyecto
```

---

## 🌐 Acceso y Uso

1. Ingresa al enlace público desplegado en **Vercel** desde cualquier computadora, tablet o teléfono móvil.
2. Configura tu nombre de estudiante y personaliza tu compañero virtual.
3. Registra tus hábitos diarios, explora la **Academia de Salud** y pon a prueba tus conocimientos en el **Quiz de 12 preguntas**.

---

## 🌟 Características Principales
1. **Compañero Animal RPG Personalizable**:
   - 11 Especies adorables (Zorro, Gatito, Panda, Axolote, Dragón, Búho, Capibara, Lobito, Osito, Pingüino, Conejito).
   - Ojos expresivos kawaii, animaciones interactivas al acariciarlo, sistema de niveles, experiencia (XP), monedas y felicidad.
   - Poses y más de 20 accesorios equipables (coronas, lentes, capas, auras de estrellas/fuego, mascotas acompañantes).

2. **Guía Biológica de Nutrición y Comidas Reales**:
   - Catálogo interactivo de desayunos, almuerzos, cenas y snacks basados en el **Plato para Comer Saludable de Harvard** y las guías de la **OMS**.
   - Fichas con macronutrientes, micronutrientes esenciales y explicación biológica de cómo actúan en las células y el cerebro.
   - Botón directo para sumar cualquier alimento como hábito diario.

3. **Calculadora Celular de Hidratación**:
   - Cálculo personalizado de requerimiento hídrico en litros según masa corporal (kg) y nivel de actividad física.
   - Seguidor interactivo de vasos de agua diarios con retroalimentación sonora y confetti.

4. **Gestión de Hábitos y Rutinas**:
   - Hábitos continuos (+ y -) con contador de rachas.
   - Rutinas diarias con verificación instantánea.
   - Recordatorios con sonido, vibración y aviso en tiempo real.

5. **Fundamentación Científica y Fisiológica**:
   - Neurobiología del bucle de hábitos y dopamina en los ganglios basales.
   - Metabolismo celular y regulación del índice glucémico.
   - Ritmos circadianos, síntesis de melatonina y activación del sistema glinfático.
   - Homeostasis osmótica y volemia hídrica.

---

Desarrollado con React 18, Tailwind CSS, Canvas Confetti y Web Audio API.
