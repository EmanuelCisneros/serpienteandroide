Juego de la serpiente simple, hecho con Python utilizando Kivy y su librería gráfica, transformado en APK con buildozer. 

Los comandos son:

# Una vez estando en la carpeta del proyecto que desea transformar a APK, creará el archivo buildozer.spec, donde se configuran las opciones generales del juego (en mí caso ya está creado).
$buildozer init 

#Para crear la carpeta ./bin donde se creará la aplicación.
$~buildozer android debug 

# Directamente generá la APK para el celular.
$~buildozer android debug deploy 
