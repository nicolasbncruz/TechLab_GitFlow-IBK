# BIENVENIDOS AL TECH LAB DE GIT FLOW    

## Primera Parte
1. Hacer grupos de 3 personas
2. Asignar roles, así:
   * 2 Developers  
   * 1 Release manager
3. Fork del repositorio
   * https://github.com/CarlosNapaR/TechLab_GitFlow-IBK
4. Clonar el repositorio copiado.
5. Validar que existan ramas Main y Dev.
6. Validar que estén bloqueadas o que no permitan subir cambios directamente.
7. Developer 1 crea rama "feature_1".
8. Crear archivo "alumnos.txt" e ingresar su nombre, apellido y equipo/mesa al que pertenece.
9. Realizar comandos necesarios para subir la rama temporal a repositorio remoto.
10. Developer 2 clona la rama feature_1 y agrega su nombre, apellido y grupo en el archivo alumnos.txt
11. Developer 2 confirma cambios al repositorio remoto (Solucionar conflictos).
12. Developer 1 realiza Pull Request a la rama Dev.
13. Release Manager valida que esten los nombres de los developers, acepta el MR y valida que la rama se elimine automáticamente.
14. Release Manager genera rama Release.
15. Release Manager detecta que falta el nombre de un integrante del equipo, por lo que genera un bug en la rama release.
16. Clonar rama release.
17. Generar rama bug y agregar el nombre del release manager con equipo/mesa a la que pertenece en el archivo "alumnos.txt"
18. Confirmar la rama bug en repositorio remoto y hacer Pull Request a la rama release. 
19. Release Manager acepta *Merge Request* si sus datos son correctos.
20. Release manager realiza *Merge Request* a rama Main.
21. Release manager genera tag en la rama main con la estretegía de versionamiento semantico, aumentando el digito de Cambio Mayor.

## Segunda parte

### 1. Realizar una mejora

Como equipo nos auto-organizamos y generamos algun dato adicional en los datos suministrados en el archivo alumnos.txt

Tener en cuenta:

* Realizar cambios en ramas temporales, prohibido subir cambios directamente a ramas de larga duración (*Dev/Main*)
* Contemplar flujo *Git Flow*.
* Al momento de subir el cambio a *Main*, validar cual digito de versionamiento semántico (*X.Y.Z*) se debe aumentar.

### 2. Realizar un Feature nuevo

Auto-organizarse e incluir un nuevo archivo con algun texto a elección para subir.

Tener en cuenta:

* Realizar cambios en ramas temporales, prohibido subir cambios directamente a ramas de larga duración (*Dev/Main*)
* Contemplar flujo *Git Flow*.
* Al momento de subir el cambio a *Main*, validar cual digito de versionamiento semántico (*X.Y.Z*) se debe aumentar.

### 3. Solucionar un Hotfix

Validar algun cambio pequeño que se deba hacer en rama *Main*, simulando una incidencia productiva.

Tener en cuenta:

* Realizar cambios en ramas temporales, prohibido subir cambios directamente a ramas de larga duración (*Dev/Main*)
* Contemplar flujo *Git Flow*.
* Identificar de que rama padre se generara la rama Hotfix.
* Al momento de subir el cambio a *Main*, validar cual digito de versionamiento semántico (*X.Y.Z*) se debe aumentar.

### 4. Socialización

Nos reuniremos todos los equipos, explicaremos nuestros ejercicios y comentaremos:

* ¿Qué se nos complicó más?
* ¿Qué dudas surgieron?
* ¿Que problemas se presentaron y comó los solucionaron?

### Nota: 
Escoger un representante por grupo.
