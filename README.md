# PR-Eclipse-02-EjemploLibreria
## Añadir y usar una librería externa en Eclipse.


***REFLEXIÓN FINAL:***

---

1. **¿Qué pasaría si exporto el proyecto a un .zip y se lo paso a un amigo o me lo llevo al ordenador de casa? ¿Funcionaría? Razona la respuesta.**<br/><br/>
Al hacerse un .zip a la carpeta entera de "EjemploLibreria", todos los archivos se mantienen, por lo tanto si es posible pasarle el proyecto a un amigo o al ordenador de tu casa.<br/>

2. **¿Qué pasaría si eliminas el archivo .jar de la carpeta lib? (puedes moverla a otro directorio para probarlo) ¿Qué ha pasado y por qué?**<br/><br/>
Al eliminarse el .jar, al correr el programa, salta un error y no se puede terminar de ejecutar el programa. Esto ocurre ya que la referencia no esta bien, por lo tanto no es capaz de leerlo y por eso salta ese error.<br/>

3. **Y si agrego la librería con Add External JARs.... ¿Observas alguna diferencia en la configuración del Build Path? ¿Crees que si lo exporto a .zip y se lo paso a un compañero le funcionaría?**<br/><br/>
Al agregarlo con Add External JARs, coloca la ruta absoluta, mientras que con Add JARs coloca la ruta relativa, tomando de base lo que ya existe en el proyecto "EjemploLibreria". En este caso, no funcionaría pasarlo a un compañero.

4. **¿Por qué no es recomendable usar Add External JARs… en proyectos que vas a compartir?**<br/><br/>
Ya que si las librerias no se encuentran dentro del proyecto, no se exportarían y sería imposible ejecutarlo, y aunque las librerías se encontrasen dentro no funcionaría en otros equipos por la ruta absoluta.<br/>
