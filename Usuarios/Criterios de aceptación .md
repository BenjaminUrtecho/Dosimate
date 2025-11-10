-	Dado que el usuario accede al sistema,
Cuando selecciona “Agregar medicamento” y completa nombre, dosis, frecuencia y duración,
Entonces el medicamento se guarda correctamente en su perfil.


-	Dado que el usuario desea modificar un medicamento,
Cuando edita los campos y guarda los cambios,
Entonces el historial se actualiza con la nueva información.


-	Dado que el usuario desea eliminar un medicamento,
Cuando lo selecciona y confirma la eliminación,
Entonces el medicamento desaparece del historial.


-	Dado que el usuario accede a la app,
Cuando navega por la interfaz,
Entonces todos los botones tienen texto claro, tamaño adecuado y contraste suficiente


-	Dado que el usuario tiene medicamentos registrados con horario,
Cuando llega la hora programada,
Entonces el sistema envía una notificación sonora y visual.


-	Dado que el usuario no confirma la toma en 10 minutos,
Cuando se cumple ese tiempo,
Entonces el sistema envía una segunda alerta.


-	Dado que el usuario confirma la toma,
Cuando presiona “Confirmar”,
Entonces el sistema registra la hora y su cumplimiento en el historial.


-	Dado que el usuario accede a la sección “Foro”,
Cuando ingresa su diagnóstico,
Entonces el sistema muestra perfiles con tratamiento similar.
