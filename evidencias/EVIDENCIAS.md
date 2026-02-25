La proteccion que se ha configurado es la proteccion de la rama "main" que es la rama principal o master, asi lo entiendo yo del repositorio donde estamos trabajando

Porque es importante o recomendable proteger la rama main?, porque en un entorno laboral varias personas pueden estar trabajando con un mismo repositorio este proceso forma parte de las buenas practicas de CI / CD.

Cada persona o colaborador trabaja en su propia rama, de esta forma se evitan erorres o conflictos o que alguien suba algun codigo que rompa el proyecto o sobreescriba la actividad de otro compañero. 

Los cambios los revisa posiblemente un coordinador antes de pasarlos a la rama "main" mediante un Pull Request, el cual verificara que todo este en orden y correcto.

Estos son uno de los principios de las buenas practicas del CI / CD

Como protegemos la rama main?

Para proteger la rama main, hay que ir al repositorio desde github y seleccionar la opcion "setting" y luego en el menu seleccionar "Branches"
aqui seleccionamos agregar una regla basica y el sistema nos pregunta que "Branch" queremos proteger en este caso escribimos "main" y con cuales reglas, el sistema tiene varias
Se selecciona "Require a pull request before merging" y "require approvals" y se le da al boton Create, el sistema nos pide autenticarnos para validar los cambios y ya esta creada nuestra regla.