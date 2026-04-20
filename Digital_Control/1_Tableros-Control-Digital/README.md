# Informacion Tableros

Este repositorio reúne recursos para trabajar con tableros y PLC en la asignatura de Control Digital. Incluye:

- Guías y ejemplos para hardware CONTROLLINO y ESP32 PLC.
- Material para interfaces HMI Stone y Coolmay.
- Prácticas organizadas por nivel (Práctica 1, 2 y 3), con código y archivos de interfaz.

## Estructura del repositorio

- [README.md](README.md)
- [Manual de Prácticas Tableros - Control Digital.pdf](Manual%20de%20Pr%C3%A1cticas%20Tableros%20-%20Control%20Digital.pdf)

### Controllino Mega

- [Controllino Mega/](Controllino%20Mega/): Programas ejemplo, datasheet, pinout y diagrama de bloques. 
- [Programas ejemplo/](Controllino%20Mega/Programas%20ejemplo/): Programas ejemplo
    - [Encender_leds/](Controllino%20Mega/Programas%20ejemplo/Encender_leds/)

### ESP32 PLC

- [ESP32 PLC/](ESP32%20PLC/): Driver de instalación, datasheet y manual de usuario.

### HMI Stone

- [HMI Stone/](HMI%20Stone/)
- [Ejemplos/](HMI%20Stone/Ejemplos/): Ejemplos básicos de interfaces diseñadas en Stone Designer GUI Software.
    - [Ejemplo1/](HMI%20Stone/Ejemplos/Ejemplo1/)
    - [Ejemplo2/](HMI%20Stone/Ejemplos/Ejemplo2/)
    - [Ejemplo3/](HMI%20Stone/Ejemplos/Ejemplo3/)
- [Infografía/](HMI%20Stone/Infograf%C3%ADa/): Recursos para manejo del HMI. 
    - [Cargar interfaz en el HMI.pdf](HMI%20Stone/Infograf%C3%ADa/Cargar%20interfaz%20en%20el%20HMI.pdf)
    - [Datasheet-STWC50WT-01.pdf](HMI%20Stone/Infograf%C3%ADa/Datasheet-STWC50WT-01.pdf)
    - [Formato de repuestas del HMI #JSON Instruction.pdf](HMI%20Stone/Infograf%C3%ADa/Formato%20de%20repuestas%20del%20HMI%20%23JSON%20Instruction.pdf)
    - [Manual de usuario de Stone Designer.pdf](HMI%20Stone/Infograf%C3%ADa/Manual%20de%20usuario%20de%20Stone%20Designer.pdf)
    - [Test code with PC.png](HMI%20Stone/Infograf%C3%ADa/Test%20code%20with%20PC.png)
- [Instaladores/](HMI%20Stone/Instaladores/): Solicitar el software Ston Designer GUI Software al fabricante en su página oficial.

## Prácticas de tableros basados en Arduino.

La carpeta [Prácticas/](Pr%C3%A1cticas/) concentra el trabajo de laboratorio. Cada práctica se organiza por plataforma HMI o tipo de ejercicio.

### Práctica 1

- [Practica1/](Pr%C3%A1cticas/Practica1/)
  - [Practica1_Botones/](Pr%C3%A1cticas/Practica1/Practica1_Botones/)
  - [Practica1_Salidas/](Pr%C3%A1cticas/Practica1/Practica1_Salidas/)

En esta práctica se trabaja la lógica base de entradas (botones) y salidas del tablero.

### Práctica 2

- [Practica2/](Pr%C3%A1cticas/Practica2/)
  - [Practica2_Coolmay/](Pr%C3%A1cticas/Practica2/Practica2_Coolmay/)
  - [Practica2_Stone/](Pr%C3%A1cticas/Practica2/Practica2_Stone/)

Se integra el control con interfaz HMI, usando el HMI Coolmay como también el HMI Stone. 

### Práctica 3

- [Practica3/](Pr%C3%A1cticas/Practica3/)
    - [Practica3_Coolmay/](Pr%C3%A1cticas/Practica3/Practica3_Coolmay/)
    - [Practica3_Stone/](Pr%C3%A1cticas/Practica3/Practica3_Stone/)

Configuración para muestreo del EPC y acción de control. Se integra la visualización de las señales de control en el HMI (Coolmay o Stone).

