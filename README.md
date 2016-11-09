Juego de la serpiente simple, hecho con Python utilizando Kivy y su librería gráfica, transformado en APK con buildozer. 

Los comandos son:

# Una vez estando en la carpeta del proyecto que desea transformar a APK, creará la carpeta buildozer.espec, donde se configurarán las opciones generales del juego (en mí caso ya está creada).
$buildozer init 

#Para crear la carpeta ./bin donde se creará la aplicación.
$~buildozer android debug 

# Directamente generá la APK para el celular.
$~buildozer android debug deploy 
