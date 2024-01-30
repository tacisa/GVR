# GVR

Ventana 1

Generador de versiones

Proyectos         Opciones

P1                branch
P2                [master]
P3                # create tag
P4                [Añadir dll excepcion]
P5                 _________
...               |SIGUIENTE|

- Inhabilitar check cuando no estemos en master
- Comprobar si hay > 0 commits de diferencia con último tag (Si no se generería la misma vr)
- Formatear json para excepciones
                  
Ventana 2

Commits

Nombre            Descripcion          Usuario            Fecha

Commit 1          adjskhdkajshdahs     jaime-tacisa       30/01/2024
Commit 2          adjskhdfajshdahs     pepe-tacisa        29/01/2024

Dlls nuget

Nombre      Version Solución      Última versión nuget    Dll excepcion

Dll 1        1.0                  V 1.1                    Si
Dll 2        1.4                  V 1.4                    No
Dll 3        3.1                  X 4.0                    No
                                                                            _______
                                                                           |GENERAR|

Pop up -> Se va a generar un empaquetado con las última versiones del nuget. 
          Dll 3        3.1 -> 4.0               
          En caso de querer forzar el uso de una dll con una versión anterior, se ha de indicar como excepcion en la ventana anterior.




        
