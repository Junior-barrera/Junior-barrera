# Bienvenido soy Junior Barrera

<div align="center">
  <img src="https://readme-typing-svg.herokuapp.com?font=Fira+Code&pause=1000&color=36BCF7&center=true&vCenter=true&width=500&lines=Ingeniero+Civil+Industrial;Desarrollador;Especialista+en+IA+%26+ML;Computer+Vision+Engineer;Fundador+de+JR+Services" alt="Typing SVG" />
</div>

---

# Sobre Mí

Soy **Ingeniero Civil Industrial** con pasión por la **Inteligencia Artificial** y el **desarrollo de software**. Me especializo en la implementación de soluciones tecnológicas innovadoras que combinan mi formación en ingeniería con habilidades avanzadas en programación y  deep learning.

- 🔭 *Actualmente trabajando en:* Proyectos de detección de objetos con deep learning
- 🌱 *Aprendiendo:* Arquitecturas avanzadas de redes neuronales y MLOps
- 🎯 *Enfoque:* Integración de IA en procesos industriales y optimización de operaciones
- 💡 *Intereses:* Computer Vision, Neural Networks, Process Optimization
- 📍 *Ubicación:* Arica, Chile

---


# Proyectos Personales

| Demo principal |
|:---:|
| ![Demo principal](./DEMO_5.gif) |

| Demo1 | Demo2 | Demo_segmentacion&yolo |
|:---:|:---:|:---:|
| ![demo](./DEMO_1.gif) | ![demo](./DEMO_2.gif) | ![demo](./DEMO_3.gif) |

# 🚀 Servicos y Empresas

## [JR Services](https://jrservices.cl/) – Fundador & CEO
*Emprendimiento de Inteligencia Artificial & Sistemas WEB aplicados a la industria*

Servicios tecnológicos especializados en IA, desarrollo de software y soluciones industriales para empresas de todos los tamaños.

**Servicios clave:**
- 🤖 Soluciones de Computer Vision y Deep Learning
- 🌐 Desarrollo de sistemas web a medida
- 📊 Optimización de procesos con Machine Learning
- 🔧 Integración de IA en sistemas existentes

---

## [VINCENTI SpA](https://www.vincenti.cl/) – Cliente & Partner Tecnológico
*Seguridad Electrónica & Telecomunicaciones*

Empresa líder con +10 años de experiencia, +200 proyectos y +50 clientes en Chile. **JR Services desarrolló y sigue manteniendo su plataforma digital completa.**

### 🎯 Lo que JR Services le aportó a VINCENTI:

| Aporte | Descripción | Estado |
|--------|-------------|--------|
| 🌐 **Creación completa del sitio web** | Desarrollo frontend y backend de vincenti.cl con diseño moderno y responsive | ✅ Entregado |
| 📘 **Brochure digital interactivo** | Catálogo digital de sus servicios, trabajos y tecnologías (Hikvision, Cisco, Dahua, Ubiquiti) | ✅ Entregado |
| 🏢 **Intranet empresarial** | Sistema interno para gestión de proyectos, clientes y técnicos en terreno | ✅ Entregado |
| 📊 **Dashboards de gestión** | Paneles de control para seguimiento de instalaciones y mantenimientos | ✅ Entregado |


### 📋 Detalle de lo desarrollado:

**1. Sitio Web Completamente Funcional**
- Landing page con catálogo de servicios
- Sistema de cotización express (respuesta en 10 min)
- Portafolio de proyectos con filtros
- Evaluación gratuita interactiva (5 preguntas)
- Sección de testimonios y calificaciones 
- Blog/afiches de seguridad
- Mapa de ubicación y formulario de contacto

**2. Brochure Digital Interactivo**
- Catálogo de servicios: Cámaras, alarmas, control de acceso, citofonía, portones eléctricos
- Tecnologías utilizadas: Hikvision, Cisco, Dahua, Ubiquiti
- Casos de éxito con CODELCO, ADT, LIPIGAS, REDSALUD
- Proyectos destacados con fotos reales (Botillería los Pepes, Residencial Los Jerez, etc.)

**3. Intranet Empresarial (Gestión Interna)**
- Panel administrativo para gestión de cotizaciones
- Seguimiento de proyectos en tiempo real
- Asignación de técnicos a órdenes de trabajo
- Base de datos de clientes y equipos instalados
- Reportes automáticos de mantenimiento


---
# jrjson

*Convierte matrices a JSON de forma simple, rápida y sin dependencias pesadas.*

[![PyPI Version](https://img.shields.io/pypi/v/jrjson)](https://pypi.org/project/jrjson/)
[![Python Versions](https://img.shields.io/pypi/pyversions/jrjson)](https://pypi.org/project/jrjson/)
[![License](https://img.shields.io/pypi/l/jrjson)](https://opensource.org/licenses/MIT)

Descripción
jrjson es una librería ligera y eficiente que convierte matrices (listas de listas) a JSON de forma simple, rápida y sin dependencias externas. Ideal para procesar datos tabulares, exportar desde Excel/CSV o transformar estructuras de datos.

⚡ Características
Característica	Descripción
🔄 Convierte matrices a JSON	Transforma cualquier lista de listas en JSON estructurado
🏷️ Soporta encabezados automáticos	Usa la primera fila como keys del objeto JSON
📄 Salida formateada	JSON con indentación legible para humanos
💻 CLI incluida	Ejecuta desde terminal sin escribir código Python
🪶 Ligero y fácil de usar	Sin dependencias pesadas, solo Python puro
🐍 Python 3+	Compatible con Python 3.x
🚀 Uso en Python
Con encabezados (recomendado)
---

## 📦 Instalación

```bash
pip install jrjson
from jrjson import convertir

matriz = [
    ["nombre", "edad", "ciudad"],
    ["Juan", 25, "Santiago"],
    ["Ana", 30, "Valparaíso"]
]

resultado = convertir(matriz, usar_header=True)
print(resultado)
Output:

json
[
  {
    "nombre": "Juan",
    "edad": 25,
    "ciudad": "Santiago"
  },
  {
    "nombre": "Ana",
    "edad": 30,
    "ciudad": "Valparaíso"
  }
]
Sin encabezados
python
from jrjson import convertir

matriz = [
    ["Juan", 25],
    ["Ana", 30]
]

resultado = convertir(matriz)
print(resultado)
Output:

json
[
  {
    "0": "Juan",
    "1": 25
  },
  {
    "0": "Ana",
    "1": 30
  }
]

