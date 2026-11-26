Entega de la Práctica 
1. ¿Qué diferencia hay entre preparar un archivo y confirmarlo? 
-Prepaar un archivo es seleccionarlo para avisar a Git de que  queremos incluirlo en el proxímos paquete de cambios. 
confirmarlo significa que guardamos ese cambio de forma definitiva en el historial, añadiendo un mensaje que lo explica

2. ¿Cuándo puedes usar Descartar cambios y qué riesgo tiene? 
Solo se pueden utilizar cuando hemos modificado archivos pero todavia no han guardado esos cambios con un commit,
el riesgo es una acción irreversible una vez que descartamos los cambios, el código anterior se borra por completo.

3. ¿Qué pasa con tu trabajo cuando cambias de una rama a otra?
El contenido del editor de VS Code cambia de forma automática para mostar exactamente el estado que tenía el proyecto en la rama seleccionada, si te cambias de una rama a otra con cambios sin guardar, tu trabajo anterior, desaparece temporalmente de tu vista

1. ¿Por qué no hubo conflicto al fusionar rama-a pero sí al fusionar rama-b?
   No hubo conflicto porque los cambios se hicieron en archivos o líneas distintas 

2. ¿Para qué sirve crear una rama de experimento, aunque luego se borre? 
   Para probar ideas o corregir errores en un entorno aislado sin arriesgar el código principal

3. Si descubres hoy un error cometido hace cinco commits, ¿qué haces para arreglarlo? 
   Haces un nuevo commit aplicando  la correción. 