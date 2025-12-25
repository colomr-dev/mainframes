# 🧮 Mainframe Modernization to Google Cloud

> **"The Network is the Computer"** - *Sun Microsystems* > **"Reliability, Availability, Serviceability"** - *IBM Mainframe Core*

Este repositorio es mi centro de conocimiento y laboratorio técnico durante el path de aprendizaje de **GCP Mainframe Modernization**. Aquí documento la transición desde los sistemas tradicionales (IBM z/OS, AS/400) hacia arquitecturas modernas y escalables en **Google Cloud Platform (GCP)**.

---

## 👨‍💻 Perfil del Mentor & Autor
* **Background:** Veterano de la infraestructura (IBM Greenock 2004, Sun Microsystems UK, Research In Motion).
* **Rol Actual:** Responsable de Preventa Google Cloud en Altostratus | Telefónica Tech.
* **Objetivo:** Traducir 60 años de lógica de negocio crítica (COBOL/JCL) a la potencia analítica de BigQuery y la elasticidad de GKE.

---

## 🏛️ El Mundo Legacy (Cimientos)

En esta sección guardo referencias sobre los pilares que sostienen el 68% de las cargas transaccionales mundiales.

### Conceptos Clave
* **MIPS & MSUs:** Entendiendo la métrica de capacidad vs. la métrica de facturación.
* **Storage:** Diferencias entre Datasets, VSAM (Key-Value ancestral) e IMS (Bases de datos jerárquicas).
* **EBCDIC:** El reto del transcoding binario.

### Stack Tecnológico
| Componente | Descripción | Equivalente en GCP |
| :--- | :--- | :--- |
| **COBOL / PL/I** | Lenguaje de lógica de negocio. | Cloud Run (Java/Go/Python) |
| **JCL** | Orquestación de Jobs (Batch). | Cloud Workflows / Airflow |
| **DB2 / IMS** | Capa de persistencia. | Cloud Spanner / Cloud SQL |
| **CICS** | Monitor de transacciones. | GKE / Microservicios |

---

## ☁️ El Mundo GCP (Modernización)

Documentación y snippets sobre las herramientas de Google para la coexistencia híbrida.

### Herramientas de "Élite"
* **Google Cloud Mainframe Connector (G4):** Ingesta nativa de datos vía JCL hacia BigQuery.
* **Dual Run:** La red de seguridad para procesamiento en paralelo y validación de integridad.
* **Mainframe Online Transcoder:** Conversión de Copybooks de COBOL a esquemas de Avro/BigQuery.

---

## 📚 Biblioteca de Referencia

### Libros de Cabecera
* [ ] **IBM Redbook:** *Introduction to the New Mainframe: z/OS Basics*.
* [ ] **O'Reilly:** *Mainframe Modernization* (Bradley Skelton).
* [ ] **Google Cloud:** *Mainframe to Google Cloud Migration Guide*.

### Snippets Destacados
* `/jcl/`: Ejemplos de ejecución del Mainframe Connector.
* `/cobol/`: Estructuras de Copybooks para mapeo de datos.
* `/terraform/`: Infraestructura base para entornos de migración en GCP.

---

## 📈 Roadmap de Aprendizaje (GCP Skills Boost)
- [x] **Módulo 1:** Introducción e Historia del Mainframe.
- [ ] **Módulo 2:** Patrones de Modernización (Rehost, Replatform, Refactor).
- [ ] **Módulo 3:** Deep Dive en Mainframe Connector (G4).
- [ ] **Módulo 4:** Estrategias de Coexistencia y Dual Run.

---

