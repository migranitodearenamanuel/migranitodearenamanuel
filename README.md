<div align="center">
  <img src="https://capsule-render.vercel.app/api?type=waving&color=0:0ea5e9,100:8b5cf6&height=235&section=header&text=Manuel%20Marco%20del%20Pino&fontSize=54&fontAlignY=34&desc=Soluciones%20de%20IA%20aplicadas%20a%20negocio%20%7C%20Arquitectura%20%2B%20Automatizaci%C3%B3n%20%2B%20Producto%20%7C%20Remoto%20&descAlignY=60" alt="Header Manuel Marco del Pino" width="100%" />
</div>

<div align="center">
  <h2>Del <i>cierre de ventas</i> al <i>despliegue de código</i>.</h2>

  <p>
    Soy <b>Manuel Marco del Pino (Manu)</b>. Combino <b>+10 años en ventas B2B y dirección comercial</b> con <b>ingeniería aplicada de IA</b>
    para construir <b>sistemas</b> (no “scripts”) que automatizan procesos, mejoran decisiones y se miden con métricas reales.
  </p>

  <p><i>“Lo que no se ve… es lo que transforma.”</i></p>

  <a href="https://www.linkedin.com/in/manuel-marco-del-pino/" target="_blank">
    <img src="https://img.shields.io/badge/LinkedIn-Conecta_conmigo-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white" alt="LinkedIn"/>
  </a>
  <a href="mailto:manuelmarcodelpino.mmdp@gmail.com">
    <img src="https://img.shields.io/badge/Email-hablemos_de_impacto-111827?style=for-the-badge&logo=gmail&logoColor=white" alt="Email"/>
  </a>
</div>

<hr/>

## ⚡ En 15 segundos: qué hago (y por qué te interesa)
* **Diseño y construyo** soluciones de IA de punta a punta: *concepto → arquitectura → backend → UI → despliegue*.
* **Automatizo procesos donde hay dinero y fricción**: ventas, soporte, operaciones, reporting y decisión.
* **Me muevo por métricas**: trazabilidad, logs, observabilidad y objetivos. Si no se mide, no existe.

> *Si buscas a alguien que entienda al CTO **y** al CEO en la misma conversación, estás en el sitio correcto.*

---

## 🎯 Rol ideal (para equipos serios)
**Applied AI Engineer / AI Automation Engineer / Solutions Architect / AI Product Engineer**
Enfoque: **RAG + Agentes + Backend + Automatización + Web/UI** (remoto).

---

## 🏆 Señales de impacto (rápidas)
* He liderado proyectos con **crecimientos >30%** en clientes mediante estrategia digital + automatización.
* Experiencia real de “campo”: gestión comercial B2B (España/Portugal), reporting diario y ejecución autónoma.
* Reconocimientos en entornos competitivos (ventas y liderazgo de equipos).

---

# 🔥 [Proyecto Insignia — ZEROX](https://github.com/migranitodearenamanuel/Zerox-Core)
> **ZEROX** es una suite modular de **automatización + analítica con IA** orientada a convertir conocimiento y señales complejas en **decisiones ejecutables**.
> Arquitectura multiagente, aprendizaje incremental, UI de supervisión y reporting.
>
> ⚠️ **Nota importante:** ZEROX se presenta aquí como **proyecto técnico de arquitectura y software**. *No es asesoramiento financiero.*

### Por qué ZEROX es “portfolio de verdad”
Porque no es un demo suelto: es un sistema con **capas**, **métricas**, **observabilidad**, **orquestación** y **criterios de seguridad**.

---

### 🧠 Caso 1 — ZEROX: Agentes + RAG (la “mente”)
**Reto:** Convertir conocimiento disperso (documentos, notas, marcos de análisis) en un sistema que **responda, razone y aprenda**.

* **Qué construí:** Ingesta de documentación → indexación → búsqueda semántica (**RAG**).
* **Orquestación:** Agentes (planificación, ejecución, verificación) usando modelos locales y APIs.
* **Resultado:** Respuestas con estructura: **qué**, **por qué** y **con qué evidencia**.

---

### 📊 Caso 2 — ZEROX: Observabilidad + Dashboard (control)
**Reto:** Si la IA es una caja negra, es un riesgo. Necesitas una cabina de mando.

* **Qué construí:** **UI/Dashboard** para supervisar el sistema, ver métricas y estados.
* **Logs auditables:** Cada decisión deja rastro (inputs, outputs, timestamps).
* **Risk Score:** Métrica propia de vulnerabilidad para apoyar decisiones.

---

### 🔌 Caso 3 — ZEROX: Integraciones (del “pensar” al “hacer”)
**Reto:** Conectar el cerebro (IA) con el mundo real (APIs, datos, reporting) de forma robusta.

* **Qué construí:** Arquitectura de conectores con APIs externas.
* **Workflows:** Automatización de tareas, extracción y normalización de datos.
* **Ledger:** “Fuente de verdad” para consistencia y trazabilidad.

---

## 🧱 Arquitectura de Sistema 

```mermaid
flowchart TB
  A[Fuentes Docs Notas Datos] --> B[Ingesta y Normalizacion]
  B --> C[Embeddings e Indice Vectorial RAG]
  C --> D[Orquestador de Agentes]
  D --> E[Herramientas APIs ETL Reglas Analisis]
  D --> F[Memoria y Estado]
  D --> G[Observabilidad Logs y Metricas]
  G --> H[Dashboard UI]
  E --> H
