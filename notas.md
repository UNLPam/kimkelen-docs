# NOTAS


- Se instalo la versión 2.19.6 que en realidad adentro figura como 2.19.5, exitosamente, se muestran los selects de Provincia y Ciudad.

- Se tomo a modo de ejemplo rápido el flavor de pellegrini, sobre esta nueva versión y se mostraron Buenos Aires y Ciudad Autonoma en los selects en cuestión.
  No se sabe aún porque funciona lo de Buenos Aires y Ciudad Autonoma, porque dichos campos estan cruzados en StateId y CityId (no como deberían ir),
  es decir como están en lib/school_beha.../base...

- Se modifico el mismo flavor (pellegrini) en flavor/lib/behaviour/PellegriniSchoolBehaviour.class.php, agregando dos clases nuevas.
  Una es PelleState que hereda de State y otra es PelleCity que hereda de City. La intención es dentro generar 2 "cons" con valores de provincias 
  y ciudad distintas. La modificación fue exitosa y en los selects luego de reinstalar todo el flavor con este archivo modificado, anduvo perfectamente.
  Se probo registrando un usuario y el mismo se guardo exitosamente con estos datos (Santa Fe y La Picada) en la BD.




