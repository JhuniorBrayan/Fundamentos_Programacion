# Herramientas Básicas para la Programación 💻

## Introducción

Para desarrollar software de manera eficiente, es fundamental contar con herramientas adecuadas que faciliten la escritura, prueba y depuración del código. Las herramientas básicas de programación permiten a los desarrolladores optimizar su flujo de trabajo y evitar errores comunes.

### Objetivo

Este documento presenta las herramientas esenciales para iniciarse en la programación, con un enfoque en Python. Se abordarán editores de texto, entornos de desarrollo, control de versiones y herramientas de depuración.

## Desarrollo


### 1. Editores de Texto y Entornos de Desarrollo

Para escribir y ejecutar código en Python, es recomendable utilizar un editor de texto o un entorno de desarrollo integrado (IDE) que facilite la escritura del código. Algunas opciones populares incluyen:

- **Visual Studio Code (VS Code)**: Ligero, con soporte para extensiones y compatibilidad con Python.
- **PyCharm**: IDE especializado en Python, con herramientas avanzadas de depuración y autocompletado.
- **Jupyter Notebook**: Ideal para pruebas y desarrollo interactivo, muy utilizado en ciencia de datos.
- **IDLE**: Editor básico que viene por defecto con Python. Si eres pricipiante no lo recomiendo, comienza con Pycharm, Jupyter Notebook o Visual Studio Code (VS Code)

---
### 2. Intérprete y Gestor de Paquetes

Python requiere un intérprete para ejecutar el código. Además, cuenta con herramientas que facilitan la gestión de bibliotecas y dependencias. Algunas de las opciones más utilizadas son:

### Intérprete de Python
- **Python (Intérprete Oficial)**: Se recomienda instalar la última versión desde [python.org](https://www.python.org/).
- **CPython**: Implementación oficial de Python, la más utilizada y mantenida por la comunidad.
- **Anaconda**: Distribución de Python que incluye herramientas especializadas en ciencia de datos y aprendizaje automático.
- **PyPy**: Alternativa optimizada a CPython que mejora el rendimiento en ciertas aplicaciones.

### Gestor de Paquetes
- **pip**: Herramienta estándar para instalar y gestionar paquetes de Python desde el repositorio PyPI.
- **venv**: Módulo integrado en Python que permite crear entornos virtuales para gestionar dependencias de manera aislada.

Ejemplo de creación de un entorno virtual:
```bash
$ python -m venv mi_entorno
$ source mi_entorno/bin/activate  # En Windows: mi_entorno\Scripts\activate
```
---
### 3. Control de Versiones

El control de versiones es esencial para gestionar cambios en el código fuente y colaborar en proyectos.

- **Git**: Sistema de control de versiones distribuido.
- **GitHub/GitLab/Bitbucket**: Plataformas en la nube para alojar repositorios Git y facilitar la colaboración.

Ejemplo de comandos básicos en Git:
```bash
# Configurar Git
$ git config --global user.name "Tu Nombre"
$ git config --global user.email "tu@email.com"

# Inicializar un repositorio
$ git init

# Agregar y confirmar cambios
$ git add .
$ git commit -m "Primer commit"
```
Si deseas profundizar sobre el control de versiones, te recomendamos uno de los mejores tutoriales creados por **MourDEV by Brais Moure**:

[Curso de GIT y GITHUB desde CERO para PRINCIPIANTES](https://youtu.be/3GymExBkKjE)

---
### 4. Herramientas de Depuración

La depuración es clave para identificar y corregir errores en el código. Algunas herramientas útiles son:

- **print()**: Instrucción básica para imprimir valores y verificar ejecución.
- **pdb**: Depurador interactivo de Python.
- **Visual Studio Code Debugger**: Integrado en VS Code para depurar código Python de forma gráfica.

Ejemplo de uso de `pdb`:
```python
import pdb

def sumar(a, b):
    pdb.set_trace()  # Inicia el depurador
    return a + b

sumar(3, 5)
```


## Conclusión

Las herramientas básicas de programación permiten mejorar la eficiencia y organización del código. Desde editores e IDEs hasta sistemas de control de versiones y depuradores, todas cumplen un rol fundamental en el desarrollo de software.

### Reflexiones Finales

- ¿Cuál de estas herramientas consideras más útil para tu aprendizaje?
- ¿Crees que existen otras herramientas que podrían facilitar tu flujo de trabajo?

Dominar estas herramientas te permitirá optimizar tu proceso de desarrollo y mejorar tu experiencia como programador. ¡Sigue explorando y practicando! 🚀

