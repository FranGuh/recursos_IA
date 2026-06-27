# 🚀 Roadmap de Aceleración de Ingeniería: De Pica-Código a Director de Orquesta (2026)

> **Paper by FranGuh 4 all.**
https://github.com/franguh

> *Seniors de la industria ya han resumido esta información por ti, el límite está en cómo usas y qué haces con esta información.*

==Creditos a sus respectivos creadores.==

Este recurso está diseñado bajo la metodología de **Desarrollo Aumentado por IA**. El objetivo no es que memorices sintaxis (la IA la escupe en segundos), sino que domines la **Arquitectura, los Requerimientos y los Arneses de Pruebas (TDD/SDD)** para liderar el software.

Se recomienda abrir con ***obsidian***.
> Es un editor y lector de formatos md, te va a encantar.
---

## 📊 Matriz de Control y Checklist de Progreso

Utiliza esta tabla para trackear tu avance y anotar los *trade-offs* o conceptos clave que descubras en cada sección.

| Tema / Componente   | Recurso                                 | Estado ([ ] / ✅) | Notas de Arquitectura y Comentarios |
| :------------------ | :-------------------------------------- | :--------------: | :---------------------------------- |
| **Fundamentos IA**  | Curso Desarrollo con IA                 |       [ ]        |                                     |
| **Ecosistema**      | Agentes de IA para Código               |       [ ]        |                                     |
| **Herramientas**    | Curso Opencode                          |       [ ]        |                                     |
| **Metodología**     | 20 Agent Harness (Disciplina)           |       [ ]        |                                     |
| **Integración**     | Engram + SDD + Skills                   |       [ ]        |                                     |
| **Especialización** | Backend Acelerado                       |       [ ]        |                                     |
| **Especialización** | Frontend Eficiente                      |       [ ]        |                                     |
| **Ciencia de S.**   | ¿Qué debería aprender?                  |       [ ]        |                                     |
| **Estructuras**     | Estructuras de Datos ($O(1)$ vs $O(N)$) |       [ ]        |                                     |
| **Paradigma**       | Paradigmas de Programación              |       [ ]        |                                     |
| **Sistemas**        | Patrones de Arquitectura                |       [ ]        |                                     |
| **Diseño**          | Patrones de Diseño (Strategy/Factory)   |       [ ]        |                                     |

---

## 🛠️ Indexación de Conocimiento y Justificación Técnica

### 1. Fundamentos para Desarrollo con IA
* **¿Por qué importa?** Para dejar de usar la IA como un simple "autocompletar" de código (tipo Copilot perezoso) y entender cómo estructurar prompts basados en especificaciones.
* 🎥 [Curso Desarrollo con IA (Ideal para comenzar)](https://youtu.be/X0oHLHIL7Mk?si=jfqm31-VMbRTU53q) *(Duración: 3 horas)*

### 2. Herramientas de Desarrollo (AI-Native IDEs & CLIs)
* **¿Por qué importa?** El entorno de desarrollo en 2026 define tu velocidad de salida a producción. No te cases con ninguna herramienta; aprende a evaluar sus capacidades multiagente y compatibilidad con proveedores de contexto locales o distribuidos.

#### 📋 Tabla de Clasificación de Herramientas (Tier List)

| Tier | Herramienta | Ventaja Competitiva | Restricción / Trade-off |
| :---: | :--- | :--- | :--- |
| **Tier S** | **Opencode** | Programación multiagente, reversión de sesiones, multi-proveedor. | Curva de aprendizaje inicial. |
| **Tier S** | **Pi agent** | Altamente recomendado en entornos de automatización. | Requiere configuración de API keys. |
| **Tier B** | **Codex / Claude Code** | Excelente comprensión de contexto de proyectos medianos. | Costo de tokens/Suscripción. |
| **Tier B** | **Cursor / Antigravity** | Indexación rápida del workspace local. | Dependencia de interfaces visuales. |
| **Tier B** | **Qwen code / CLIs Chinas**| Inferencia económica, alta velocidad, soporte local. | Documentación a veces fragmentada. |
| **Tier C** | **VS Code Tradicional** | Altamente estable, ecosistema gigante de extensiones. | Es síncrono; no está diseñado nativamente para agentes autónomos. |

* 🎥 [Probé TODOS los Agentes de IA para Código… Esto Aprendí](https://www.youtube.com/watch?v=NRELko2BoRk) *(Duración: 20 minutos)*
* 🎥 [Curso Opencode](https://youtu.be/ZZq4TpNgnvg?si=X9TXw4UfilDFBkOY) *(Duración: 2 horas)*

---

## 🏗️ Metodologías Avanzadas: SDD, TDD y MCPs
* **¿Por qué importa?** Aquí se divide a los juniors de los ingenieros. **Spec-driven Development (SDD)** dicta que la IA no toca una línea de código hasta que los requerimientos y el arnés de pruebas (*Harness*) estén perfectamente validados. Esto evita el código basura y las alucinaciones.

* 🎥 [El PADRE de todos los CURSOS de IA: 20 Agent Harness para programar con disciplina](https://www.youtube.com/watch?v=5Q7jV8TpMXA) *(Duración: 40 minutos)*
* 🎥 [El ECOSISTEMA de IA que le falta a tu agente \| Engram + SDD + Skills \| Tutorial Completo](https://www.youtube.com/watch?v=UoS_LP-PCG8&t=6s) *(Duración: 30 minutos)*
* ⏩ *[Saltar directo a la instalación práctica del ecosistema](https://youtu.be/UoS_LP-PCG8?si=4l5v_OmqmMXHnrHp&t=805)*

---

## 🎯 Aplicación por Capas (Delivery)
* **¿Por qué importa?** Para entender cómo los agentes abordan arquitecturas desacopladas. En Backend, priorizando contratos de API robustos; en Frontend, aislando el estado de la vista.

* 🎥 [Especialización en Backend Acelerado](https://youtu.be/l3HJsXA-Fa4?si=Wy3hDrUinuHrnkSA) *(Duración: 29 minutos)*
* 🎥 [Especialización en Frontend Eficiente](https://youtu.be/Rla0IMxIlNc?si=HOtfowRTNzJ_q2Vr) *(Duración: 19 minutes)*

---

## 🧠 Fundamentos de Ciencias de la Computación (El Filtro de Calidad)
* **¿Por qué importa?** La IA genera opciones; tú tomas decisiones basadas en limitantes físicas y lógicas. Si no conoces estos conceptos, no podrás auditar el código que la IA genera, convirtiendo tu software en una bomba de tiempo de rendimiento.

* 🧠 [¿Qué debería aprender para tener criterio técnico?](https://youtu.be/Ywgn96xVjqc?si=Zf6SLV0XzhYbgpwq)
* 📊 [Estructuras de Datos: Cuándo usar Arrays vs Maps ($O(1)$ vs $O(N)$)](https://youtu.be/J1_UIf17p7I?si=MKcBy9y_Khw8v3ka)
* 🧩 [Paradigmas de Programación (Funcional, OOP, Reactiva)](https://youtu.be/GehWsIr6oFo?si=eoTpFNDbRfB6x_3-)
* 🏛️ [Cada Patrón de Arquitectura Explicado en 18 Minutos](https://www.youtube.com/watch?v=q3YQy1lJutw)
* ⚙️ [Patrones de Diseño (Strategy, Factory, Observer, Singleton)](https://youtu.be/rqOaZf4xMlI?si=UldVOxv06a6RpnVu)
* 🏛️ [El agent loop ha llegado](https://www.youtube.com/watch?v=aZML4zJaai8)
* 🎥 [Cómo construir lo único que la IA no puede copiar](https://www.youtube.com/watch?v=GnBRh5TGYxI)
