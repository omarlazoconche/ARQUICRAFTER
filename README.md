# ARQUICRAFTER
INSPECTOR IA QUE CORRIGE PLANOS ARQUITECTONICOS DE ACUERDO A LAS NORMAS PERUANAS Y MAS!
# 🏛️ ArquiCraft Studio & Plano Vivo

**ArquiCraft Studio** es un entorno de desarrollo integrado (IDE) web de código abierto, diseñado bajo los principios de soberanía tecnológica, rendimiento extremo y arquitectura *offline-first*. Está enfocado enteramente en el sector de **Arquitectura, Ingeniería y Construcción (AEC)**[cite: 4], emulando la flexibilidad de plataformas en la nube pero especializado en el diseño, auditoría y modelado de proyectos.

---

## 🤖 Plano Vivo: Asistente Arquitectónico e Inspector Experto

Dentro de este ecosistema, **Plano Vivo** funciona como un sistema experto y supervisor autónomo que replica el rigor técnico, académico y legal de un arquitecto titulado en el Perú[cite: 7]. Sus capacidades principales abarcan:

1. **Inspector Correctivo y Normativo:** Audita de forma continua los planos bajo las normativas del **Reglamento Nacional de Edificaciones (RNE)** (normas A.010, A.020, accesibilidad, iluminación y ventilación natural al 10%) y los parámetros urbanísticos municipales[cite: 6].
2. **De Fotografía Real a Plano 2D Vectorial:** Interpreta fotografías o bocetos de edificaciones mediante visión computacional para transformarlos automáticamente en planos arquitectónicos 2D acotados[cite: 6].
3. **De Plano 2D a Renderizado 3D:** Procesa planimetría bidimensional para extruir y generar previsualizaciones y modelos tridimensionales interactivos en el navegador[cite: 6].

---

## 🛠️ Stack Tecnológico

* **Frontend UI:** React / Svelte + Tailwind CSS para una interfaz modular y fluida[cite: 4].
* **Visor & Motor Gráfico:** Three.js / HTML5 Canvas / SVG Vectorial para renderizado 2D y 3D[cite: 4].
* **Core de Lógica & RNE:** **Rust compilado a WebAssembly (Wasm)** para cálculos geométricos ultrarrápidos y validación normativa sin latencia[cite: 4].
* **Persistencia Local:** IndexedDB + SQLite (Wasm) para almacenamiento *offline-first*[cite: 4].
* **Sincronización:** Control de versiones descentralizado mediante Git Wasm y la API de GitHub[cite: 4].

---

## 📚 Fundamentación Académica y Malla Curricular Base

El razonamiento de Plano Vivo se fundamenta en los planes de estudio de facultades de referencia (como la PUCP y la UNI)[cite: 8] y en el marco legal del Ministerio de Vivienda, Construcción y Saneamiento (**MVCS**):
* **Eje I:** Urbanismo, Legislación y Normativa Nacional (RNE)[cite: 8].
* **Eje II:** Diseño Arquitectónico, Composición y Ergonomía[cite: 8].
* **Eje III:** Estructuras, Materiales y Construcción Sismorresistente (Normas E.030 y E.070)[cite: 8].
* **Eje IV:** Representación Avanzada y Geometría Computacional[cite: 8].

---

## 📂 Estructura del Repositorio

```text
arquicraft-studio/
├── README.md                                   # Documentación principal
├── docs/
│   ├── ArquiCraft_Studio_Arquitectura_Base.md  # Especificaciones generales del IDE
│   ├── Especificacion_Replit_Personalizado.md  # Blueprint de la interfaz y módulos
│   ├── Perfil_Profesional_Arquitecto.md        # Perfil y malla curricular de Plano Vivo
│   └── Fundamentacion_Academica_RNE.md         # Marco bibliográfico y legal (RNE/PUCP/URP)
└── src/                                        # Código fuente (Rust/Wasm + UI)
🚀 Contribución y Licencia
Este proyecto se distribuye bajo los principios del código abierto. Las contribuciones orientadas a optimizar el motor geométrico en Rust o ampliar las reglas del RNE son totalmente bienvenidas.
