# Informacion Tableros

Repositorio de recursos para la guia de practicas de la asignatura de Control Digital.

Este contenido esta pensado para:

- Centralizar material tecnico de los tableros usados en laboratorio.
- Compartir codigo fuente y archivos de apoyo por practica.
- Facilitar la migracion de enlaces desde Google Drive hacia GitHub.

## Que contiene este repositorio

- Controllino Mega: documentacion tecnica y programas ejemplo.
- ESP32 PLC: documentacion tecnica, datasheets y recursos de configuracion.
- HMI Stone: ejemplos, infografias y archivos de soporte para diseno de interfaces.
- Practicas: codigo y recursos organizados por practica.

## Practicas incluidas en la guia

Segun el documento principal de LaTeX (main.tex), la guia actualmente incluye:

1. Practica 1: Manejo de entradas y salidas digitales del Controllino Mega.
2. Practica 2: Manejo basico de HMI.
3. Practica 3: Control de motor DC.

## Contenido excluido para publicacion en GitHub

Para reducir el peso del repositorio, se excluyeron temporalmente:

- Instaladores pesados de HMI Stone.
- Carpeta de videos de HMI Stone (no utilizada en la guia actual).

El material removido se ubico en:

- ../Archivos Removidos/

### Tabla de control de removidos (temporal)

| Elemento removido | Ubicacion de respaldo | Motivo |
|---|---|---|
| HMI Stone/Instaladores/Stone Desginer-3.0.12.dmg | ../Archivos Removidos/HMI Stone/Instaladores/Stone Desginer-3.0.12.dmg | Archivo pesado |
| HMI Stone/Instaladores/Stone Designer Setup 3.0.12.exe | ../Archivos Removidos/HMI Stone/Instaladores/Stone Designer Setup 3.0.12.exe | Archivo pesado |
| HMI Stone/Instaladores/stone-designer-2.0.70.zip | ../Archivos Removidos/HMI Stone/Instaladores/stone-designer-2.0.70.zip | Archivo pesado |
| HMI Stone/Video tutoriales Stone Designer GUI/ (carpeta) | ../Archivos Removidos/HMI Stone/Video tutoriales Stone Designer GUI/ | Contenido no utilizado en la guia |

Nota: esta tabla es temporal y puede eliminarse cuando termine la migracion.

## Donde actualizar enlaces en LaTeX (Drive -> GitHub)

El archivo main.tex no contiene hipervinculos directos; solo incluye capitulos.
Los enlaces que debes actualizar estan en los siguientes archivos:

| Archivo .tex | Linea | Tipo de enlace actual | Recomendacion |
|---|---:|---|---|
| 2-componentes_tablero.tex | 19 | Carpeta Drive (informacion general) | Reemplazar por carpeta equivalente en GitHub |
| 2-componentes_tablero.tex | 77 | Carpeta Drive (infografia Controllino) | Reemplazar por ruta en GitHub |
| 2-componentes_tablero.tex | 119 | Carpeta Drive (infografia ESP32 PLC) | Reemplazar por ruta en GitHub |
| 2-componentes_tablero.tex | 121 | Archivo Drive (guia ESP32 PLC) | Reemplazar por archivo en GitHub |
| 2-componentes_tablero.tex | 159 | Carpeta Drive (infografia HMI Stone) | Reemplazar por ruta en GitHub |
| 2-componentes_tablero.tex | 161 | Carpeta Drive (instaladores) | Actualizar o eliminar si ya no se distribuyen |
| 2-componentes_tablero.tex | 163 | Archivo Drive (guia de carga HMI) | Reemplazar por archivo en GitHub |
| 2-componentes_tablero.tex | 165 | Archivo Drive (guia de usuario HMI) | Reemplazar por archivo en GitHub |
| 2-componentes_tablero.tex | 167 | Carpeta Drive (infografia fabricante) | Reemplazar por ruta en GitHub |
| 4-practica1.tex | 57 | Carpeta Drive (codigo practica) | Reemplazar por carpeta en GitHub |
| 6-practica3.tex | 62 | Carpeta Drive (codigo practica) | Reemplazar por carpeta en GitHub |
| 6-practica3.tex | 63 | Carpeta Drive (firmware HMI Stone) | Reemplazar por carpeta en GitHub |
| 6-practica3.tex | 64 | Carpeta Drive (firmware HMI Coolmay) | Reemplazar por carpeta en GitHub |
| 6-practica3.tex | 94 | Carpeta Drive (instaladores Stone) | Actualizar o eliminar si ya no se distribuyen |
| 7-practica4.tex | 78 | Carpeta Drive (codigo practica) | Reemplazar por carpeta en GitHub |

## Fuentes originales

- Controllino: https://www.controllino.com/
- Industrial Shields: https://www.industrialshields.com/
- HMI Stone: https://www.stoneitech.com/
