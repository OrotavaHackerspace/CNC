<img width="180" src="https://www.shapeoko.com/images/shapeoko_logo.svg" align="right" />

# CNC Orotava Hackerspace
> Herramientas y utilidades para las CNC del local

Repositorio creado con el objetivo de almacenar todas las herramientas utilizadas en el Orotava Hackerspace para el manejo de las máquinas de control númerico. Además hemos elaborado una wiki con las diferentes modificaciones realizadas sobre la maquinaria y tutoriales sobre estas.

Nuestra CNC:
<p align="center">
  <img width="450" src="https://github.com/OrotavaHackerspace/CNC/blob/master/Touch%20Plate/Images/IMG_20180303_111648_392.jpg?raw=true">
</p>

Fresadora utilizada:
<p align="center">
  <img width="450" src="https://github.com/OrotavaHackerspace/CNC/blob/master/Touch%20Plate/Images/IMG_20180303_111559_054.jpg?raw=true">
</p>

Especificaciones:

- Área de corte (XL): 33"(83,82 cm)(X), 16"(40,64 cm)(Y), 3"(7,62 cm)(Z)
- Peso: 100 lbs (45 kg)
- Firmware: GRBL
- Sistema operativo para el software de Carbide: OS X 10.8 o superior, Windows 7, 8, 8.1, 10
- Motores paso a paso: NEMA 23

## Herramientas utilizadas

En esta sección incluiremos todas las herramientas utilizadas para el diseño, la generación de GCodes y el control de la CNC. Dichas herramientas son las siguientes:

- [LinuxCNC](http://linuxcnc.org/) - Sistema operativo para el control de máquinas CNC.
- [Atom.io](https://atom.io/) -  Editor de código.
- [Python 2.7](https://www.python.org/download/releases/2.7/) - Lenguaje de programación utilizado para el funcionamiento del control de la máquina.
- [FreeCAD](https://www.freecadweb.org/?lang=es_ES) - FreeCAD es un modelador 3D paramétrico.
- [Inkscape](https://inkscape.org/es/) - Inkscape es un editor de gráficos vectoriales de código abierto.
- [KiCAD](http://kicad-pcb.org/) - Suite de diseño de PCBs.
- [pcb2Gcode](https://github.com/pcb2gcode/pcb2gcode) - Generador de Gcode para CNC partiendo de un fichero Gerber.
- [pcb2GcodeGUI](https://github.com/pcb2gcode/pcb2gcodeGUI) - Interfaz gráfica para el generador de Gcode para CNC partiendo de un fichero Gerber.
- [PyCAM](https://github.com/pib/pycam/wiki) - Generador de GCode partiendo de ficheros STL.
- [Aspire 8](http://www.vectric.com/products/aspire/whats-new/V8/WhatsNew.html) - Generador/Diseñador de Gcode partiendo de varios formatos.
- [bCNC](https://github.com/vlachoudis/bCNC) - Programa para el control de la CNC desde un PC.
- [Universal Gcode Sender](https://github.com/winder/Universal-G-Code-Sender) - Programa para enviar Gcodes a la CNC.

## Hardware

La placa controladora de la CNC es la siguiente:

<p align="center">
  <img width="450" src="https://github.com/OrotavaHackerspace/CNC/blob/master/Touch%20Plate/Images/IMG_20180303_111458_470.jpg?raw=true">
</p>

<p align="center">
  <img width="450" src="https://github.com/OrotavaHackerspace/CNC/blob/master/Touch%20Plate/Images/IMG_20180303_111530_303.jpg?raw=true">
</p>

La placa se corresponde con la versión 2.4d de Carbide.

## Entradas a la Wiki

- [Touch Probe](https://github.com/OrotavaHackerspace/CNC/wiki/Colocaci%C3%B3n-de-%22Touch-probe%22-en-Shapeoko-3-XL) - Instalación de un "touch probe" para la calibración del origen en el eje Z.

## Referencias

- [Wiki de Shapeoko](https://www.shapeoko.com/wiki/) - Wiki de las CNC Shapeoko.
