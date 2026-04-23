# Informe de Laboratorio No. 01: Robótica Industrial

**Universidad:** Universidad Nacional de Colombia

**Asignatura:** Robótica 2026-I

**Fecha de entrega:** 24/04/2024

**Estudiantes:** David Santiago Pirateque Suarez, Jose Daniel Suarez Vasques y David Felipe Cardenas Cubides 


---

## 1. Descripción detallada de la solución planteada

Para comenzar el laboratorio, se realizó la calibración del workobject y de la herramienta a utilizar. En ambos casos, esta calibración se realizo tanto de forma digital (con el modelo 3D de cada objeto) como de forma manual (usando la herramienta ya impresa en 3D y el workobject físico). Para esta práctica, el workobject consistió en una caja con una lámina sobre la cual el marcador pudiera escribir.

Una vez hecho esto, se realizó la programación de trayectorias desde el software de RobotStudio. Se comenzó definiendo la posición inicial, también conocida en RAPID como target_home. Luego, se procedió con el diseño del pastel, basándose principalmente en el workobject digital, ya que este se diseñó con las formas que se esperaban dibujar utilizando los comandos de movimiento MoveL, MoveJ y MoveC.

Con las trayectorias planteadas en la simulación, se pasó a las pruebas físicas con el manipulador industrial IRB 140. Ahí se probaron ambas calibraciones de la herramienta y se optó por la [___]. Durante la ejecución, se observó que el marcador estaba bajando más de lo necesario; por lo tanto, se elevó el workobject en la simulación para corregir este problema.

Por último, se configuraron las entradas y salidas del controlador IRC5 para la activación de la banda transportadora y de los pilotos indicadores, así como para la lectura de las entradas digitales correspondientes a los pulsadores del tablero. Con esto, se finalizó la configuración de la rutina principal donde taambien se le asigno la posicion de mantenimiento.

## 2. Diseño de la herramienta detallado

[Describe en este espacio:
* Cómo diseñaron en CAD la herramienta para fijar el marcador al flanche.
* Cuál fue la técnica de calibración que usaron.
* Compara y analiza las diferencias entre el tooldata creado en el robot real versus el importado en RobotStudio.]

## 3. Diagrama de flujo de acciones del robot

el diagrama de flujo del modulo 1 del RAPID  usado durante la practica:

![Diagrama de flujo del robot](Diagrama.png)


## 4. Plano de planta de la ubicación de cada uno de los elementos

*(Asegúrate de guardar la imagen de tu plano en la misma carpeta que este archivo y cambia el nombre abajo)*
![Plano de planta del laboratorio](ruta_al_plano_de_planta.png)

## 5. Descripción de las funciones utilizadas

[Lista y explica brevemente qué funciones de programación usaste. Por ejemplo:
* **MoveL / MoveJ:** [Tu explicación de para qué las usaste]
* **SetDO / Reset:** [Tu explicación]
* **IF / FOR / WHILE:** [Tu explicación]
* **WaitTime / TPWrite:** [Tu explicación]]

## 6. Código en RAPID del módulo utilizado

[A continuación se presenta el código desarrollado para la práctica:]

```rapid
! Reemplaza esto con tu código real.
! Recuerda incluir la lógica completa de las trayectorias, 
! las entradas/salidas y los workobjects.

MODULE Module1
    ! Tus variables y constantes aquí
    
    PROC main()
        ! Tu rutina principal aquí
    ENDPROC
ENDMODULE
