# Proyecto Básico en Django

Este proyecto tiene como objetivo levantar un proyecto Django básico para visualizar la página de bienvenida de Django. Este es el primer paso para familiarizarse con el framework.

---

## Índice

1. [Requisitos Previos](#1-requisitos-previos)
2. [Configuración del Entorno](#2-configuración-del-entorno)
3. [Creación del Proyecto](#3-creación-del-proyecto)
4. [Iniciar el Servidor de Desarrollo](#4-iniciar-el-servidor-de-desarrollo)
5. [Probar la Página Inicial](#5-probar-la-página-inicial)

---

## 1. Requisitos Previos

Antes de comenzar, asegúrate de tener:

- **Python 3.8 o superior** instalado en tu máquina.
- **pip** (el gestor de paquetes de Python) instalado.
- Un editor de texto (opcional, pero recomendado: [Visual Studio Code](https://code.visualstudio.com/)).

---

## 2. Configuración del Entorno

### Crear un Entorno Virtual

1. Abre tu terminal o línea de comandos.
2. Crea un entorno virtual:
   ```bash
   python -m venv venv
   ```
3. Activa el entorno virtual:
   - En Windows:
     ```bash
     venv\Scripts\activate
     ```
   - En macOS/Linux:
     ```bash
     source venv/bin/activate
     ```

### Instalar Django

Con el entorno virtual activado, instala Django:
```bash
pip install django
```

---

## 3. Creación del Proyecto

1. Crea un nuevo proyecto Django llamado `my_project`:
   ```bash
   django-admin startproject my_project
   ```
2. Navega a la carpeta del proyecto:
   ```bash
   cd my_project
   ```

---

## 4. Iniciar el Servidor de Desarrollo

Con el proyecto creado, inicia el servidor de desarrollo ejecutando:
```bash
python manage.py runserver
```

---

## 5. Probar la Página Inicial

1. Abre tu navegador web.
2. Ve a la URL que aparece en tu terminal, generalmente:
   ```
   http://127.0.0.1:8000/
   ```
3. Deberías ver la página de bienvenida de Django, que incluye el texto: **"The install worked successfully! Congratulations!"**

---

## Conclusión

¡Felicidades! Has levantado tu primer proyecto Django y accedido a la página de bienvenida. Este es el primer paso para desarrollar aplicaciones más avanzadas con Django. A partir de aquí, puedes comenzar a agregar aplicaciones, modelos, vistas y más.

---
