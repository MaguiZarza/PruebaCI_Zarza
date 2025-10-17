# Mejora Continua y CI/CD  

## Objetivo:
La actividad tiene como propósito aplicar los conceptos de **integración continua (CI)** y **entrega continua (CD)** utilizando **GitHub Actions**, con el fin de automatizar el proceso de prueba y validación de código cada vez que se realizan cambios en el repositorio.  

---

## Descripción:  
Durante la actividad se crea un **flujo de trabajo (pipeline)** automatizado que ejecuta pruebas unitarias en un proyecto de **Python**.  

Este pipeline se activa automáticamente cuando se suben cambios al repositorio, permitiendo comprobar si el código sigue funcionando correctamente sin necesidad de ejecutar las pruebas manualmente.  

El flujo incluye:  
- Instalación del entorno de Python  
- Carga del código desde el repositorio  
- Ejecución de pruebas con **pytest**  

Si las pruebas pasan correctamente, el pipeline finaliza con éxito; en caso contrario, muestra los errores y marca la ejecución como fallida.  

Además, se analiza cómo la **mejora continua** se aplica dentro de este contexto: al introducir un error en el código, el sistema detecta automáticamente la falla, demostrando la utilidad de las herramientas de CI/CD para garantizar la calidad del software y evitar que errores lleguen a producción.  

---

## Conclusión:  
La práctica permite comprender el funcionamiento de los **pipelines de integración continua** y cómo **GitHub Actions** puede automatizar tareas críticas del desarrollo.  

A través de esta simulación, se refuerza la importancia de la **automatización, el testeo constante y la detección temprana de errores** como parte fundamental del ciclo de **mejora continua** en proyectos de software.  

---

*Actividad realizada en la materia **Metodología de Sistemas II** – Prof. Rosalía Insaurralde*
