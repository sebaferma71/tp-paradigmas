# Trabajo practico de Paradigmas de Programacion con SmallTalk
El estudio cinematográfico CINEMA tiene registrada la información que maneja. Para resolver la situación que plantearemos necesitamos contar con los datos del personal que desempeña tareas varias en forma permanente (información que ya esta cargada) y la de las películas que son producidas en el mismo.
Del personal permanente se conocen los siguientes datos:
-	Número de documento
-	Nombre y apellido
-	Plus (porcentaje sobre el remanente del presupuesto, que cada empleado cobra, una vez terminado el rodaje de una película, y es distinto para cada uno)
-	Sueldo básico (que es el mismo para todos los empleados)
-	Especialidad (rol que cumple en el estudio)

Además de los empleados existen otras personas que integran el staff, estos son los actores y el equipo de dirección.
De cada uno de ellos, ya sea actor o parte del equipo de dirección se conoce: 
-	Número de documento
-	Apellido y nombre 
-	Nacionalidad

Si es actor, además tendrá pactado un cachet (monto que cobrará por su participación en la película), en cambio, si es del al equipo de dirección acordará un porcentaje sobre el presupuesto asignado a la película, a partir del cual se calculará su paga.
De cada película que produce el estudio se almacena la siguiente información:
-	Código
-	Título
-	Staff (personal del estudio, actores y equipo de dirección)
-	Presupuesto asignado
-	Presupuesto remanente

En el momento de instanciar una película solo se cargarán los datos básicos, el personal del estudio que participará del rodaje (validando que forme parte del personal permanente) y el presupuesto asignado.

A medida que se van agregando personas (actores y equipo de dirección) al staff se ira calculando el presupuesto remanente.

Se desea confeccionar el correspondiente diseño del sistema siguiendo los lineamientos de la programación orientada objetos y un programa en Smalltalk que permita a través de un menú realizar las siguientes operaciones:
1.	Instanciar una película.
2.	Agregar una persona al staff.
3.	Calcular el plus que cobrará un empleado determinado, una vez finalizado el rodaje de una película. 
