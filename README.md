# georreferenciacion_clientes
Código para georreferenciar un grupo de clientes y asignarlos a distintos distribuidores

PARTE 1: Los clientes potenciales

Se recurre a un listado de contactos que dejaron sus datos en diferentes medios existentes, entre ellos su dirección, a partir de la cual definiremos el distribuidor que deberá contactarse con ellos.

PARTE 2: Definición de la red de cada distribuidor

Los distribuidores ya tienen redes de clientes a los que están atendiendo, para asignar a un nuevo cliente se utiliza la mediana de las coordenadas de los clientes ya existentes. Eso definirá el "centroide" de la red de clientes de cada distribuidor.

PARTE 3: asignación

Las coordenadas de cada cliente seran comparadas con las del centroide la red de cada distribuidor, luego se eligirán los tres más cercadnos y entre ellos el que mejor desempeño haya tenido.

PARTE 4: control y visualización

Se define un mapa que permite visualizar y comparar la asignación de dos distribuidores. 
