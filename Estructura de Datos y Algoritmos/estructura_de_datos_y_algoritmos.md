#**Estructura de Datos y Algoritmos**

EDA es una asignatura obligatoria del segundo curso en la que se estudian an�lisis de algoritmos y eficiencia, algoritmos iterativos y recursivos, divide y vencer�s, vuelta atr�s, TADs, diccionarios y �rboles.
Se programar� en C++.
El entorno de desarrollo que vamos a utilizar es Code::Blocks (http://www.codeblocks.org/).


##**Code::Blocks**
###**1. Descripci�n del programa**
Code::Blocks es un IDE de c�digo abierto y libre compatible con sistemas Linux, Mac y Windows, en la que se puede desarrollar c�digo en C, C++ y Fortran.

###**2. Requisitos hardware**
Tener una RAM con 512 MB libres tras el arranque del SO. 

###**3. Gu�a de instalaci�n en GNU/Linux**
- Instalar Code::Blocks desde la terminal con el comando �sudo apt-get install codeblocks�.
- Iniciar Code::blocks. Tiene un sistema de autodetecci�n de los compiladores que tiene el sistema instalados. Seleccione un compilador de C++. Si no tiene ning�n compilador de C++, instale el compilador GCC con el comando: �sudo apt-get install g++�.

###**4. Estructura del programa**
Code::Blocks tiene la misma vista tanto para el modo desarrollo como en el modo de depuraci�n.
![Main](https://github.com/LibreLabUCM/LiberarFdI/blob/master/Estructura%20de%20Datos%20y%20Algoritmos/images/Main.png?raw=true)

###**5. Manual de usuario**
- Crear un nuevo proyecto:
  Ir a la pesta�a �File > New > Project��. 
![Crear proyecto 0](https://github.com/LibreLabUCM/LiberarFdI/blob/master/Estructura%20de%20Datos%20y%20Algoritmos/images/CrearProyecto/CrearProyecto0.png?raw=true)


-- Seleccionamos �Empty project�:
![Crear proyecto 1](https://github.com/LibreLabUCM/LiberarFdI/blob/master/Estructura%20de%20Datos%20y%20Algoritmos/images/CrearProyecto/CrearProyecto1.png?raw=true)

-- Pulsar �Next�:
![Crear proyecto 2](https://github.com/LibreLabUCM/LiberarFdI/blob/master/Estructura%20de%20Datos%20y%20Algoritmos/images/CrearProyecto/CrearProyecto2.png?raw=true)

-- Poner nombre al proyecto, fijar d�nde estar� guardado y pulsar �Next�:
![Crear proyecto 3](https://github.com/LibreLabUCM/LiberarFdI/blob/master/Estructura%20de%20Datos%20y%20Algoritmos/images/CrearProyecto/CrearProyecto3.png?raw=true)

-- Pulsar �Finish�:
![Crear proyecto 4](https://github.com/LibreLabUCM/LiberarFdI/blob/master/Estructura%20de%20Datos%20y%20Algoritmos/images/CrearProyecto/CrearProyecto4.png?raw=true)

-- En la pesta�a �Workspace� aparece el proyecto creado:
![Crear proyecto 5](https://github.com/LibreLabUCM/LiberarFdI/blob/master/Estructura%20de%20Datos%20y%20Algoritmos/images/CrearProyecto/CrearProyecto5.png?raw=true)

- A�adir un fichero nuevo a un proyecto:
-- Con el proyecto abierto, ir a la pesta�a �File > New > Empty file�.
![A�adir Fichero nuevo 0](https://github.com/LibreLabUCM/LiberarFdI/blob/master/Estructura%20de%20Datos%20y%20Algoritmos/images/A�adirFicheroNuevo/A�adirFicheroNuevo0.png?raw=true)

-- El programa nos sugerir� a�adir el fichero nuevo al proyecto:
![A�adir fichero nuevo 1](https://github.com/LibreLabUCM/LiberarFdI/blob/master/Estructura%20de%20Datos%20y%20Algoritmos/images/A�adirFicheroNuevo/A�adirFicheroNuevo1.png?raw=true)

-- Poner nombre al fichero y pulsar �Guardar�.
![A�adir fichero nuevo 2](https://github.com/LibreLabUCM/LiberarFdI/blob/master/Estructura%20de%20Datos%20y%20Algoritmos/images/A�adirFicheroNuevo/A�adirFicheroNuevo2.png?raw=true)

- A�adir un fichero existente al proyecto:
-- Hacer click derecho en el nombre del proyecto abierto en la pesta�a �Projects� y seleccionar �Add files...�:
![A�adir fichero existente 0](https://github.com/LibreLabUCM/LiberarFdI/blob/master/Estructura%20de%20Datos%20y%20Algoritmos/images/A%C3%B1adirFicheroExistente/ficheroExistente0.png?raw=true)

-- Buscar el fichero que desea a�adir, seleccionarlo y pulsar �Abrir�.
![A�adir fichero existente 1](https://github.com/LibreLabUCM/LiberarFdI/blob/master/Estructura%20de%20Datos%20y%20Algoritmos/images/A%C3%B1adirFicheroExistente/ficheroExistente1.png?raw=true)

- Compilar y ejecutar un proyecto:
-- Para compilar el proyecto, hacer click en la pesta�a �Build� y pulsar �Build� y posteriormente pulsar �Run� en la misma pesta�a para ejecutarlo: 
![Compilar ejecutar 0](https://github.com/LibreLabUCM/LiberarFdI/blob/master/Estructura%20de%20Datos%20y%20Algoritmos/images/CompilacionEjecucion/CompilacionEjecucion0.png?raw=true)

-- Pulsar �Build and Run� en la pesta�a �Build� si se desea compilar y ejecutar el proyecto en un solo paso: 
![Compilar ejecutar 1](https://github.com/LibreLabUCM/LiberarFdI/blob/master/Estructura%20de%20Datos%20y%20Algoritmos/images/CompilacionEjecucion/CompilacionEjecucion1.png?raw=true)

- Depuraci�n de un proyecto:
-- Si desea a�adir puntos de interrupci�n, vaya a la l�nea en la que desee poner uno y haga doble click a la derecha del n�mero de l�nea.  O pulse click derecho y selecciones �Add breakpoint�:
![Breakpoint 0](https://github.com/LibreLabUCM/LiberarFdI/blob/master/Estructura%20de%20Datos%20y%20Algoritmos/images/Breakpoint/breakpoint0.png?raw=true)
![Breakpoint 1](https://github.com/LibreLabUCM/LiberarFdI/blob/master/Estructura%20de%20Datos%20y%20Algoritmos/images/Breakpoint/breakpoint1.png?raw=true)

-- Pulsar la pesta�a �Debug� y seleccionar �Start�:
![Debug 0](https://github.com/LibreLabUCM/LiberarFdI/blob/master/Estructura%20de%20Datos%20y%20Algoritmos/images/Debug/debug0.png?raw=true)

-- Se activar� el modo de depuraci�n:
![Debug 1](https://github.com/LibreLabUCM/LiberarFdI/blob/master/Estructura%20de%20Datos%20y%20Algoritmos/images/Debug/debug1.png?raw=true)

-- Utilizar la barra de botones para realizar la depuraci�n:
![Debug 2](https://github.com/LibreLabUCM/LiberarFdI/blob/master/Estructura%20de%20Datos%20y%20Algoritmos/images/Debug/debug4.png?raw=true)

-- Para detener la depuraci�n pulsar el bot�n �Stop debugger� de la barra de botones de depuraci�n: 
![Debug 3](https://github.com/LibreLabUCM/LiberarFdI/blob/master/Estructura%20de%20Datos%20y%20Algoritmos/images/Debug/stopdebug.png?raw=true)


###**6. Anexos:**
- Manual de usuario oficial de Code::Blocks (disponible en ingl�s, alem�n y franc�s): http://www.codeblocks.org/user-manual
- Ficha docente de la asignatura Estructura de Datos y Algoritmos del curso 2016/2017: http://www.fdi.ucm.es/Pub/ImpresoFichaDocente.aspx?Id=916