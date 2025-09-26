# Practica2
##                                                              Gary Brayam Villca Machaca
## Parte1 de la practica
1. **¿Que es una rama (branch)en git y para qque se utiliza?**

Una rama en git en como una linea paralela de trabajo dentro de un proyecto, sirve para probar cosas nuevas, hacer cambios o añadir funciones sin afectar el codigo principal mayormente el branch main o master.

2. **Explica con tus palabras que significa hacer un marge**

Es como adjuntar los caminos, si tiene una rama donde trabajaste en algo nuevo y quieres que esos cambios esten en la rama principal haces un marge.

3. **¿Que es un conflicto de fusion (merege conflict) y como se puede resolver?**

Un conflicto de fusion pasa cuando git no sabe que cambios elegir porque dos personas "o ramas" modificaron la misma parte del archivo la manera distinta.
- Para solucionarlo uno mismo tiene abrir el archivo, decidir que parte del codigo quedarse o unir ambas y guardar la version final, despues se confirma ese areglo con un commit.

4. **Diferencias entre fork y clone en Github**

- *Fork:* Es como hacer una copia del proyecto en tu propia cuenta de Github, sirve de mucho cuando quieres proponer cambios en un proyecto ajeno.
- *Clone:* Es descargar el proyecto de Github a tu computadora para poder trabajar en el locarmente.

5. **¿Que es un pull requets y para que se usa en proyectos colaborativos?**

Es una forma de decir "Hola hice cambios en mi copia del proyecto, ¿pueden revisarlos y si estan bien los unen al proyecto principal?" Es usado en trabajos de equipo yaque permite que otros revisen, comenten y aprueben lo que hiciste antes de ponerlo al codigo oficial.

6. **Investiga y explica 3 buenas practicas para colaborar en equipo usando Github**

- *Trabajar en ramas separadas:* no tocar directamente el main, sino crear una rama para cada tarea o función. Así se evitan problemas y se organiza mejor el trabajo.

- *Commits claros y frecuentes:* escribir mensajes de commit entendibles como “Arreglo de login” o “Agregado botón de contacto”, no solo “cambio” o “probando”. Esto ayuda a todos a entender la historia del proyecto.

- *Revisar con pull requests:* antes de unir cambios al proyecto principal, abrir un PR para que los compañeros revisen, den feedback y se aseguren de que no se rompe nada. Eso mejora la calidad del código y fomenta el trabajo en equipo.