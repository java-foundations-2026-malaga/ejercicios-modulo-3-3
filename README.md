# JFo 3-3 - Datos textuales

Esta carpeta contiene 15 actividades autocorregibles del modulo 3.

## Actividades

01. Corrige comillas incorrectas
02. Corrige un char con varios caracteres
03. Corrige una concatenacion rota
04. Corrige secuencias de escape
05. Corrige diferencia entre print y println
06. Crea un saludo personalizado
07. Crea una etiqueta de producto
08. Crea una frase concatenada
09. Imprime texto con comillas
10. Imprime una ruta de archivo
11. Generador de tarjeta de presentacion
12. Creador de dialogo sencillo
13. Constructor de nombre de usuario
14. Ticket textual de compra
15. Plantilla de historia corta

Cada subcarpeta `actividadNN` es un proyecto Maven independiente con tests JUnit 5 y workflow de GitHub Actions.

## Cómo entregar las actividades

La rama `main` está protegida: contiene los enunciados originales y no se puede modificar.
Cada alumno trabaja en **su propia rama**, con su nombre.

1. Clona el repositorio:
   `git clone https://github.com/java-foundations-2026-malaga/REPOSITORIO.git`
2. Crea tu rama con tu nombre y apellido, en minúsculas y sin tildes ni espacios (por ejemplo `juan-perez`):
   `git checkout -b juan-perez`
   (En Eclipse: botón derecho sobre el proyecto > `Team > Switch To > New Branch...`).
3. Importa en Eclipse la carpeta `actividadNN` que vayas a hacer (`File > Import... > Maven > Existing Maven Projects`), resuélvela y comprueba los tests con `Run As > JUnit Test`.
4. Haz commit y sube **tu rama**:
   `git add .` → `git commit -m "Actividad NN"` → `git push -u origin juan-perez`
   (En Eclipse: `Git Staging` > `Commit and Push...`).
5. En la pestaña **Actions** del repositorio verás el resultado de la autocorrección de cada actividad que hayas modificado: ✅ aprobada o ❌ con los errores.

Si al hacer push te aparece un error sobre `main`, es que estás en la rama equivocada: cambia a tu rama con `git checkout juan-perez`.
