# 🎩 Geoffrey Butler Plugin

> **Mayordomo y Crítico Implacable de Producto & UX/UI para Antigravity / Claude Code.**  
> *Inspirado en la filosofía de pensamiento crítico de Addy Osmani y en el mayordomo más elegante de la televisión.*

---

## 🎯 ¿Qué es Geoffrey?

`geoffrey` es un skill para agentes de IA diseñado específicamente para **Diseñadores de Producto (UX/UI)** y Product Managers. Su misión es erradicar la **rendición cognitiva (*cognitive surrender*)** y el **aprobado ciego (*rubber stamping*)**: esa tentación de dar por buena una interfaz generada por IA solo porque se ve bonita y elegante.

Geoffrey audita tus pantallas, flujos y componentes haciéndote las preguntas incómodas que un desarrollador o usuario te harían en producción. Y si no tienes la respuesta, se arremanga contigo para definirla.

---

## 🏛️ El Ecosistema de Mayordomos

Geoffrey forma parte de un equipo coordinado de mayordomos virtuales:

| Mayordomo / Skill | Rol | Responsabilidad |
| :--- | :--- | :--- |
| **`grill-me`** | Interrogador de Ideas | Sesión inicial de estrés técnico y de negocio. |
| **`geoffrey`** | Crítico de Producto UX/UI | Examen crítico, auditoría de estados y generación de los 5 artefactos clave de UX. |
| **`alfred`** | Mayordomo Documental | Estructuración en `docs/` (Vault Markdown), trazabilidad y Git. |

---

## 📦 Los 5 Artefactos de UX que Produce

Geoffrey estructura su trabajo en 5 fases obligatorias:

1. **`01-user-story-brief.md`**: User Persona, JTBD, Hipótesis de Valor y Criterios de Aceptación.
2. **`02-user-flow-states.md`**: Diagrama Mermaid del flujo y Matriz de los 5 Estados (Ideal, Loading, Empty, Error, Edge cases).
3. **`03-component-spec.md`**: Anatomía del componente, estados de interacción, responsive y teclado móvil.
4. **`04-ux-copy-matrix.md`**: UX writing, microcopy, CTAs y mensajes de error orientados a soluciones.
5. **`05-ux-handoff-checklist.md`**: Definición de terminado (DoD), métricas de impacto y el Quiz de Geoffrey.

---

## 🚀 Instalación en Antigravity

1. Clona el repositorio:
   ```bash
   git clone https://github.com/bigsome/geoffrey.git ~/Projects/skills/geoffrey-plugin
   ```
2. Crea un enlace simbólico en tu carpeta de plugins de Antigravity:
   ```bash
   ln -s ~/Projects/skills/geoffrey-plugin ~/.gemini/config/plugins/geoffrey-plugin
   ```
3. Reinicia tu sesión en Antigravity y actívalo invocando a Geoffrey o pidiéndole que audite una pantalla o feature.

---

## 📄 Licencia

MIT © David Roselló
