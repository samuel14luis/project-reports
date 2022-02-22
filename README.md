# Proyecto: Reportes de avance de proyecto ágil

## Contenido
1. [Información General](#general-info)
2. [Tecnologias](#tecnologias)
3. [Instalacion](#instalacion)
4. [Accesos](#accesos)
5. [Uso](#uso)

## General Info
***
Reporte en Power BI para ver el avance de proyecto ágil y detalle de tareas. 
### Screenshot
![Image text](./images/captura01-dashboard.png)

## Tecnologias
***
Lista de tecnologías utilizadas en el proyecto:
* [Power BI](https://example.com): Version 2.102.683.0 64-bit (febrero de 2022) 
* [Microsoft Excel 2021](https://example.com): Version 2108 (16.0.14332.20204) 64 bits

## Instalacion
***
Clonar el repositorio con los siguientes comandos. (No requiere instalación) 
```
$ git clone https://github.com/samuel14luis/project-reports.git
$ cd ../path/to/the/file
```
Nota: Para un funcionamiento adecuado utilizar ```Excel 2012 en adelante``` y ```Power Bi 2.1 en adelante```

## Accesos
***
Contraseña del VBA Project: humtherland2021

![imagen](https://user-images.githubusercontent.com/25417920/155059223-2f118a90-f608-4974-a43c-35d66462548c.png)

Contraseñas: 

  ACCESO_TEAM: acceso@nivel01 - ```Mostrar tabla Tareas y Registro de tareas```
  
  ACCESO_MANAGER: acceso@nivel05 - ```Mostrar todas las tablas```
  
![imagen](https://user-images.githubusercontent.com/25417920/155059638-666a7c9c-e794-4898-ab96-ec4215a943b7.png)

## Uso
***
MODO MANAGER: Planificar y dar mantenimiento a las tablas en Excel.

### Diagrama de relaciones
![imagen](https://user-images.githubusercontent.com/25417920/155060841-9f82adc8-b0f4-4a7c-98bb-0b9a0d1903f5.png)

TABLAS A LAS QUE ACCEDE
* [TB_PROYECTOS]
* [TB_EPICAS]
* [TB_FEATURES]
* [TB_USERSTORIES]
* [TB_SPRINT]
* [TB_AREAS]
* [TB_PERSONAS]
* [TB_EQUIPO]
* [TB_TAREAS]


MODO TEAM: Cada miembro del equipo debe revisar sus tareas y actualizar el estado en el Registro de tareas.
### Estados de tarea
![imagen](https://user-images.githubusercontent.com/25417920/155060985-1434e141-6cc8-4081-ae26-c95aa8212745.png)

TABLAS A LAS QUE ACCEDE
* [TB_TAREAS] SOLO VER
* [TB_REGISTROS] ACTUALIZAR
