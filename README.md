<div align="center">
  <img src="https://capsule-render.vercel.app/api?type=waving&color=0:0f172a,100:3b82f6&height=280&section=header&text=Manuel%20Marco%20del%20Pino&fontSize=50&fontAlignY=35&desc=AI%20Solutions%20Architect%20%7C%20Business%20Automation%20%7C%20Full%20Stack%20Developer&descAlignY=60&animation=fadeIn&fontColor=ffffff" alt="Header Manuel Marco del Pino" width="100%" />
</div>

<div align="center">
  <h3>🚀 Del <i>cierre de negocios</i> al <i>despliegue de arquitecturas escalables</i>.</h3>

  <p width="80%">
    Soy <b>Manu</b>. He transformado <b>+10 años de liderazgo en ventas y gestión B2B</b> en una carrera de <b>Ingeniería de IA Aplicada</b>.
    <br>
    No escribo scripts sueltos; diseño <b>ecosistemas de software</b> que resuelven problemas reales de negocio, reducen costes y operan de forma autónoma.
  </p>

  <p><i>"Código limpio. Arquitectura robusta. Impacto medible."</i></p>

  <div align="center">
    <a href="https://www.linkedin.com/in/manuel-marco-del-pino/" target="_blank">
      <img src="https://img.shields.io/badge/LinkedIn-Conectar_Profesionalmente-0077B5?style=for-the-badge&logo=linkedin&logoColor=white" alt="LinkedIn"/>
    </a>
    <a href="mailto:manuelmarcodelpino.mmdp@gmail.com">
      <img src="https://img.shields.io/badge/Email-Hablemos_de_Proyectos-EA4335?style=for-the-badge&logo=gmail&logoColor=white" alt="Email"/>
    </a>
    <a href="https://github.com/migranitodearenamanuel">
      <img src="https://img.shields.io/badge/GitHub-Ver_Código-181717?style=for-the-badge&logo=github&logoColor=white" alt="GitHub"/>
    </a>
  </div>
</div>

<br>

## ⚡ Executive Summary: Mi Valor Diferencial
Lo que me hace único no es solo el código, es la **visión híbrida**:

* 🧠 **Business-Driven Development:** Entiendo el ROI antes de abrir el IDE. Si no aporta valor al negocio, no se codea.
* 🏗️ **Arquitectura End-to-End:** Desde el diseño del sistema (UML/Mermaid) hasta el despliegue y la observabilidad.
* 🤖 **AI Native:** Especialista en **Sistemas Agénticos**, **RAG Avanzado** y **Fine-Tuning** de LLMs.

> *Busco roles como **AI Engineer, Automation Architect o Python Developer** en equipos que valoren la autonomía y la excelencia técnica.*

---

## 🛠️ Tech Stack & Arsenal
*Evidencia basada en mis repositorios públicos y privados.*

| Dominio | Tecnologías y Herramientas |
| :--- | :--- |
| **🧠 AI Core & LLMs** | `LangChain`, `OpenAI API`, `Google Gemini`, `Ollama` (Local LLMs), `Hugging Face`, `PyTorch` |
| **🔍 RAG & Vectores** | `ChromaDB`, `FAISS`, `Embeddings`, `Recursive Character Splitting` |
| **⚡ Backend & APIs** | `Python` (AsyncIO, Pydantic), `FastAPI`, `LangServe`, `REST APIs` |
| **📊 Data & Math** | `Pandas`, `NumPy`, `SQLAlchemy`, `SQL` (MySQL), `NoSQL` (MongoDB) |
| **🎨 Frontend & UI** | `Streamlit`, `HTML5`, `CSS3`, `JavaScript` (ES6+), `Vite` |
| **🔊 Audio & Visión** | `Whisper` (ASR), `Google Vision API`, `Librosa`, `TTS Models` |
| **⚙️ DevOps & Tools** | `Git`, `Docker`, `n8n`, `Make`, `Postman`, `VS Code` |

---

## 🔥 Proyecto Insignia: [ZEROX - CORE](https://github.com/migranitodearenamanuel/Zerox-Core)
> **Estado:** *En desarrollo activo* | **Tipo:** *Arquitectura Multi-Agente Autónoma*

**ZEROX** no es un bot de trading. Es una **arquitectura de software compleja** diseñada para la toma de decisiones financieras autónomas en entornos de alta incertidumbre. Combina análisis cuantitativo tradicional con el razonamiento semántico de los LLMs.

### 🧩 Módulos Clave del Sistema

#### 1. El "Cerebro" (Reasoning Engine)
* **Arquitectura:** Sistema Multi-Agente orquestado con **LangChain**.
* **Innovación:** Implementación de **Chain-of-Thought (CoT)** para que los agentes "razonen" antes de actuar, reduciendo alucinaciones.
* **Tech:** Modelos locales (Llama 3) para privacidad y velocidad + Modelos cloud para validación.

#### 2. La "Memoria" (Advanced RAG)
* **Funcionalidad:** Ingesta dinámica de noticias financieras y documentación técnica.
* **Vector Store:** Uso de **ChromaDB** para recuperación semántica de contexto relevante en milisegundos.

#### 3. Los "Ojos" (Observabilidad)
* **Dashboard:** Interfaz en **Streamlit** para monitoreo en tiempo real de los agentes.
* **Logging:** Sistema robusto de logs para auditoría de cada decisión tomada por la IA.

---

## 🧱 Arquitectura del Sistema (High-Level)

```mermaid
graph TD
    subgraph "Ingesta de Datos"
        A[APIs Financieras] -->|JSON| B(Normalizador de Datos)
        DOCS[Documentos / Noticias] -->|Texto| B
    end

    subgraph "Núcleo de IA (Backend Python)"
        B --> C{Orquestador LangChain}
        C <-->|Consultas Semánticas| D[(Vector DB - Chroma)]
        C <-->|Inferencia| E[LLM Engine (Ollama/OpenAI)]
        
        subgraph "Agentes Especializados"
            F[Agente Analista]
            G[Agente de Riesgo]
            H[Agente Ejecutor]
        end
        
        C --> F & G & H
    end

    subgraph "Salida & Control"
        H -->|Ejecución| I[API Exchange]
        F & G -->|Logs & Métricas| J[Streamlit Dashboard]
    end

    style C fill:#f9f,stroke:#333,stroke-width:2px
    style D fill:#bbf,stroke:#333,stroke-width:2px
    style E fill:#bfb,stroke:#333,stroke-width:2px
