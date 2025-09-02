PROYECTO SISTEMA GESTION DE PAGOS Y NOTAS DE ESTUDIANTE (GESTION JB)

REQUISITOS SECCION DE CODIFICACION Y DISENO DE LOGICA:
	
	1. MODULO FORMULARIO PARA LOGIN (ADMINISTRADOR Y SUB ADMINISTRADOR)
		a. El administrador tiene todos los permisos de ingresar, modificar, actualizar, eliminar respaldos y consultas.
		b. El sub administrador solo tiene permisos de consultar e ingresar datos.
		c. Cada usuario tiene un nombre y contrasena predeterminado, el cambio de cualquiera de estas dos la maneja el administrador.

	2. MODULO DE INGRESO DE DATOS (INGRESO DATOS)
		a. Formulario de ingreso de datos de los estudiantes, la cual son los siguientes campos:
			i. Nombre completo
			ii. Institucion donde estudia
			iii. Grado que esta cursando
			iv. Telefono
			v. Pago de inscripccion
			vi. Pago de meses (enero a octubre), si el estudiante decide quedarse otro mes (noviembre) mas se habilita la casilla.
			vii. Pago de examenes (1,2,3 y 4)
			viii. Pago de papeleria
	
	3. MODULO INGRESO DATOS (INGRESO NOTAS)
		a. Formulario donde se ingresan las notas que deben de contener lo siguiente:
			i. Busqueda del nombre del estudiante para modificar o agregar la nota y a la vez obtener el nombre, grado.
			ii. Si el estudiante ya se realizo el examen aparece la nota de lo contrario aparecera el valor de cero.
	
	4. MODULO DE CONSULTAS (CONSULTAR LOS PAGOS Y NOTAS)
		a. Una ventana o pestana dedicada a mostrar los datos consultados atravez del nombre (si se proporciona una clave utilizar clave)
		b. Modulo consulta Meses
			i. Mostrar todos los datos de los estudiantes
			ii. Mostrar una tabla con los meses solventes (si el mes no se ha cancelado despues de los primeros 5 dias del mes mostrar la casilla en rojo de
			    lo contrario no mostrar ningun color)
			iii. Si hasta la fecha el estudiante tiene todos los meses cancelados y papeleria, mostrar una barra de estatus donde se mencione que esta
			     solvente, de lo contrario mostrar que no esta solvente.
		c. Modulo consulta notas
			i. Cuando el estudiante tiene canceladas los examenes se muestran las notas, si la nota es mayor a 60 esta aprobado de lo contrario mostrar reprobado.
