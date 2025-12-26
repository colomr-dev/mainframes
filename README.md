# 🧮 Mainframe Modernization to Google Cloud

> **"The Network is the Computer"** - *Sun Microsystems* > **"Reliability, Availability, Serviceability"** - *IBM Mainframe Core*

En este repositorio guardo documentación de Mainframes y como extender sus funcionalidades con tecnología moderna y escalable en **Google Cloud Platform (GCP)**.

---

## 👨‍💻 Perfil del Autor
* **Background:** Veterano de la infraestructura (IBM UK, Sun Microsystems UK, Research In Motion UK, Telefónica...).
* **Rol Actual:** Responsable de Preventa Google Cloud en Altostratus | Telefónica Tech.
* **Objetivo:** Aprendizaje sobre Mainframes (COBOL/JCL) y cómo integrarlos para aprovechar la elasticidad de Google Cloud.

---

## 🦖 El Mundo Mainframe (Cimientos)

En esta sección guardo referencias sobre los pilares que sostienen el 70% de las cargas transaccionales mundiales.

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

### Herramientas
* **Google Cloud Mainframe Connector (G4):** Ingesta nativa de datos vía JCL hacia BigQuery.
* **Dual Run:** Procesamiento en paralelo y validación de integridad.
* **Mainframe Online Transcoder:** Conversión de Copybooks de COBOL a esquemas de Avro/BigQuery.

---

## 📚 Biblioteca de Referencia

### Libros de Cabecera
* [ ] **IBM Redbook:** *Introduction to the New Mainframe: z/OS Basics*.
* [ ] **O'Reilly:** *Mainframe Modernization* (Bradley Skelton).
* [ ] **Google Cloud:** *Mainframe to Google Cloud Migration Guide*.

### Directorios Destacados
* `/books/`: Libros, Material de Referencia.
* `/jcl/`: Ejemplos de ejecución del Mainframe Connector.
* `/cobol/`: Estructuras de Copybooks para mapeo de datos.
* `/terraform/`: Infraestructura base para entornos de migración en GCP.

---

