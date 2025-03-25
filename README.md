# PPS-Unidad3Actividad1-MansurSY
Actividad 1 de la Unidad 3 de Puesta en Producción Segura. Creación de entornos de pruebas. 

Tenemos como objetivo:

> [Crear entorno de máquinas vulnerables](#Entorno-de-maquinas-vulnerables)

> [Crear un entorno de pruebas de vulnerabilidades](#Entorno-de-pruebas)

---
## Entorno de maquinas vulnerables

Hemos visto como, entre la información de fuentes abiertas que tenemos a nuestro alcance, hay proyectos creados con máquinas deliberadamente vulnerables para que podamos entrenar con ellas.

Entre las muchas que hay podemos encontrar los siguientes proyectos: 

1. [DAMN VULNERABLE WEB APPLICATION \(DVWA\)](https://github.com/digininja/DVWA/blob/master/README.es.md) 
2. [Buggy Web APPlication \(BWAPP\)](http://www.itsecgames.com/) 
3. [OWASP Multillidae II](https://owasp.org/www-project-mutillidae-ii/)

Para ello tan sólo tenemos que realizar los siguientes pasos:
1. Crea una carpeta con nombre entorno-vulnerables-tunombre
2. Coloca dentro de ella el archivo [docker-compose.yml](./entornoMaquinasInseguras/docker-compose.yml) que tienes en la carpeta entornoMaquinasInseguras de este repositorio: 
3. Levanta el escenario multicontedor con `docker-compose up -d`
