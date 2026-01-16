# MediRed 🏥✨


**MediRed** es una plataforma de salud integral que combina el poder de la Inteligencia Artificial con el juicio clínico humano para optimizar el proceso de diagnóstico médico. La plataforma guía al paciente desde la manifestación de sus síntomas hasta la recomendación validada de estudios clínicos, reduciendo la incertidumbre y agilizando la atención médica especializada.

---

## 🚀 Propuesta de Valor

A diferencia de los buscadores genéricos que generan ansiedad, **MediRed** cierra el ciclo de atención:

1. **Analiza:** Una IA avanzada procesa los síntomas del usuario.
2. **Canaliza:** Identifica la especialidad médica correcta.
3. **Valida:** Un médico especialista revisa el caso y autoriza la recomendación.
4. **Resuelve:** El paciente obtiene una orden de estudio clínico lista para ejecutarse.

---

## 🛠️ Stack Tecnológico

### Frontend (Arquitectura Híbrida)

* **[Astro](https://astro.build/):** Utilizado para el marketing site, catálogo de estudios y secciones de contenido estático para maximizar el SEO y la velocidad de carga.
* **[React](https://reactjs.org/):** Potencia las "Islas de Interactividad" como el chat de síntomas por IA y el panel de control del médico.
* **[Tailwind CSS](https://tailwindcss.com/):** Para una interfaz limpia, minimalista y totalmente responsiva.

### Backend & IA

* **[Django (Python)](https://www.djangoproject.com/):** Motor robusto para la gestión de usuarios, seguridad de datos médicos y lógica de negocio.
* **[OpenAI API / LangChain](https://www.langchain.com/):** Implementación de modelos de lenguaje (LLM) con técnicas de RAG (Generación Aumentada por Recuperación) para limitar las recomendaciones al catálogo real de estudios.
* **[PostgreSQL](https://www.postgresql.org/):** Base de datos relacional para garantizar la integridad de los expedientes médicos.

---

## 📦 Características Principales

* **Asistente de Triaje Inteligente:** Interfaz de chat que interpreta lenguaje natural y clasifica la gravedad del cuadro clínico.
* **Catálogo de Estudios Médico:** Buscador dinámico de análisis, radiografías y servicios de gabinete con detalles de preparación previa.
* **Panel del Especialista:** Dashboard exclusivo donde los médicos pueden validar, rechazar o modificar las sugerencias de la IA en tiempo real.
* **Gestión de Citas y Órdenes:** Generación de órdenes digitales para estudios una vez aprobadas por el especialista.

---

## 🧬 Flujo de la Plataforma

1. **Entrada de Datos:** El usuario describe sus síntomas.
2. **Pre-análisis (IA):** El motor identifica posibles patologías y especialidades.
3. **Revisión Humana:** El caso aparece en el portal del especialista correspondiente.
4. **Emisión de Orden:** El médico aprueba el estudio necesario y el paciente es notificado.

---

## 🏗️ Configuración del Entorno (Local)

### Prerrequisitos

* Python 3.13+
* Node.js & npm
* Docker (Opcional, recomendado para PostgreSQL)

### Instalación

1. **Clonar el repositorio:**
```bash
git clone https://github.com/LuisVenegas/MediRed.git
cd MediRed

```


2. **Configurar el Backend (Django):**
```bash
python -m venv venv
source venv/bin/activate  # O venv/Scripts/activate en Windows
pip install -r requirements.txt
python manage.py migrate

```


3. **Configurar el Frontend (Astro/React):**
```bash
cd frontend
npm install
npm run dev

```



---

## 🛡️ Seguridad y Privacidad

El proyecto cumple con los estándares de protección de datos personales y sensibles, implementando:

* Encriptación de datos en reposo y en tránsito.
* Anonimización de síntomas para el procesamiento en la nube de IA.
* Protocolos de autenticación segura para personal médico.

---

## 👨‍💻 Desarrollado por:

Este proyecto es una colaboración entre colegas y amigos:

* **Luis Venegas** – *Ingeniero de Software / Co-fundador* 
* **Joshua Marin** – *Ingeniero de Software / Co-fundador*

📍 **Veracruz, México.**

---
