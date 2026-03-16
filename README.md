# 🐍 PYTHON DESDE CERO - GUÍA COMPLETA

**Python desde Cero** es un sitio educativo completo diseñado para enseñar Python desde los fundamentos hasta conceptos avanzados, con explicaciones claras, ejemplos prácticos y código listo para usar.

> *"Python es el segundo lenguaje más popular del mundo y el primero para ciencia de datos e inteligencia artificial."*

---

## 🎯 ¿Qué es este Proyecto?

Este proyecto proporciona un recurso educativo gratuito para aprender Python, incluyendo:

- **Documentación completa** de cada tema
- **Ejemplos de código** listos para ejecutar
- **Ejercicios prácticos** para reforzar el aprendizaje
- **Sitio web educativo** con navegación intuitiva

---

## 📚 Contenido del Curso

### Módulo 1: Fundamentos

1. **Introducción**
   - Historia de Python
   - Filosofía Python (Zen of Python)
   - Casos de uso

2. **Instalación**
   - Python en Windows, Mac, Linux
   - pip y gestión de paquetes
   - Entornos virtuales (venv)
   - IDEs recomendados

3. **Conceptos básicos**
   - Variables y tipos de datos
   - Operadores
   - Estructuras de control
   - Funciones

### Módulo 2: Intermedio

4. **Ejemplos prácticos**
   - Estructuras de datos (listas, diccionarios)
   - Manejo de archivos
   - Módulos y paquetes
   - Programación orientada a objetos

5. **Buenas prácticas**
   - PEP 8 (style guide)
   - Documentación
   - Testing con pytest
   - Virtual environments

### Módulo 3: Avanzado

6. **Casos reales**
   - Desarrollo web (Django/Flask)
   - Data Science (pandas, numpy)
   - Machine Learning (scikit-learn)
   - Automatización y scripting

7. **Proyecto final**
   - Aplicación completa
   - Deploy a producción

---

## 🗂️ Estructura del Proyecto

```
PYTHON-SPAM-WHATSAPP/
├── index.html          # Página principal
├── css/
│   └── styles.css      # Estilos del sitio
├── js/
│   └── main.js         # JavaScript del sitio
└── README.md
```

---

## 🚀 Cómo Usar este Proyecto

### Opción 1: Navegar el Sitio Web

1. Abre `index.html` en tu navegador
2. Navega por las secciones del curso
3. Haz clic en los temas para ver la documentación detallada

### Opción 2: Ejecutar los Ejemplos

1. Instala Python desde python.org
2. Crea un archivo .py
3. Copia los ejemplos y ejecuta con `python archivo.py`

### Requisitos

- **Python 3.8** o superior
- **pip** (incluido con Python)
- Editor de código (VS Code recomendado)

---

## 📝 Ejemplos Rápidos

### Variables y Tipos

```python
nombre = "Juan"
edad = 30
altura = 1.75
es_estudiante = True
hobbies = ["leer", "codificar"]
persona = {"nombre": nombre, "edad": edad}
```

### Funciones

```python
def saludar(nombre):
    return f"Hola {nombre}"

def sumar(a, b=0):
    return a + b

# Lambda
cuadrado = lambda x: x ** 2
```

### Clases

```python
class Persona:
    def __init__(self, nombre):
        self.nombre = nombre
    
    def saludar(self):
        return f"Hola, soy {self.nombre}"

# Uso
juan = Persona("Juan")
print(juan.saludar())
```

### Manejo de Archivos

```python
# Leer archivo
with open('archivo.txt', 'r') as f:
    contenido = f.read()

# Escribir archivo
with open('salida.txt', 'w') as f:
    f.write('Hola Mundo')

# Leer JSON
import json
with open('datos.json') as f:
    datos = json.load(f)
```

### List Comprehension

```python
# Forma tradicional
cuadrados = []
for i in range(10):
    cuadrados.append(i ** 2)

# List comprehension
cuadrados = [i ** 2 for i in range(10)]

# Con condición
pares = [i for i in range(20) if i % 2 == 0]
```

---

## 🎓 Metodología de Aprendizaje

### 1. Leer la Teoría
Cada tema comienza con una explicación clara del concepto.

### 2. Ver Ejemplos
Los ejemplos de código muestran la aplicación práctica.

### 3. Practicar
Los ejercicios te permiten aplicar lo aprendido.

### 4. Experimentar
Modifica los ejemplos para entender cómo funcionan.

---

## 🔧 Comandos Esenciales

### Terminal/Consola

```bash
# Ver versión de Python
python --version

# Ejecutar script
python archivo.py

# Instalar paquete
pip install nombre_paquete

# Crear entorno virtual
python -m venv venv

# Activar entorno virtual (Windows)
venv\Scripts\activate

# Activar entorno virtual (Linux/Mac)
source venv/bin/activate
```

---

## 📖 Recursos Adicionales

### Documentación Oficial

- [Python Documentation](https://docs.python.org/es/)
- [Python.org](https://www.python.org/)
- [PEP Index](https://peps.python.org/)

### Herramientas Recomendadas

- **VS Code** - Editor con extensión Python
- **PyCharm** - IDE profesional
- **Jupyter Notebook** - Para data science
- **Black** - Formateador de código

### Comunidades

- [Python Community](https://www.python.org/community/)
- [Stack Overflow - Python](https://stackoverflow.com/questions/tagged/python)
- [Reddit r/Python](https://www.reddit.com/r/Python/)

---

## 💡 Consejos para Principiantes

1. **Practica todos los días**: La consistencia es clave.
2. **Lee código de otros**: Aprende de proyectos open source.
3. **Construye proyectos**: La mejor forma de aprender es haciendo.
4. **Sigue PEP 8**: Escribe código limpio desde el inicio.
5. **Usa entornos virtuales**: Mantén tus proyectos aislados.

---

## ⚠️ Mejores Prácticas

### Código Limpio

- Sigue PEP 8 para estilo de código
- Usa nombres descriptivos
- Mantén funciones pequeñas

### Seguridad

- Nunca uses `eval()` con datos no confiables
- Valida siempre los datos de entrada
- Usa variables de entorno para secretos

### Rendimiento

- Usa generadores para grandes datasets
- Evita imports innecesarios
- Profilea tu código con cProfile

---

## 🧪 Ejercicios Prácticos

### Nivel Básico

1. Calculadora simple
2. Conversor de unidades
3. Juego de adivinar números

### Nivel Intermedio

1. Web scraper básico
2. API REST con Flask
3. Automatización de tareas

### Nivel Avanzado

1. Aplicación web completa
2. Modelo de Machine Learning
3. Bot de Telegram/Discord

---

## 👨‍💻 Desarrollado por Isaac Esteban Haro Torres

**Ingeniero en Sistemas · Full Stack · Automatización · Data**

- 📧 Email: zackharo1@gmail.com
- 💻 GitHub: https://github.com/ieharo1

---

© 2026 Isaac Esteban Haro Torres - Todos los derechos reservados.
