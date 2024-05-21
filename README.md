# ProyectoFinal_PasajerosAereosMDE
# **MINTIC – TALENTO TECH | ANALISIS Y VISUALIZACIÓN DE DATOS**
# **PROYECTO FINAL**

Pasajeros aereos salida y llegada del aeropuerto de Medellín

### 1. Introducción

En este README se presenta las evidencias sobre el ejercicio de aplicación de métodos de recolección y limpieza de datos entre dos Dataset´s.

### 2. Recolección y limpieza de datos

Se realizó la búsqueda de dos diferentes Datasets en la página de Datos Abiertos, se descargó la información de “Salida mensual de pasajeros desde el aeropuerto con destino internacional de Medellín” y “Llegada mensual pasajeros aeropuerto de origen internacional de Medellín”

##### 2.1 Dataset No. 1 – Salida mensual de pasajeros desde el aeropuerto con destino internacional de Medellín

![image](https://github.com/avillamil92/ProyectoFinal_PasajerosAereosMDE/assets/169549526/de2bf982-5ba0-42e8-9114-432935a13a1d)
![image](https://github.com/avillamil92/ProyectoFinal_PasajerosAereosMDE/assets/169549526/3fb4e4e6-b13d-4ae0-b832-c45b04eef66b)

Este dataset es de tipo CSV, y tiene las siguientes características:
*	Filas: 7060
*	Columnas: 5

###### 2.1.1 Normalización de datos Dataset No. 1

Se realiza el cargue del archivo salida_mensual_pasajeros_aeropuerto_destino_internacional en OpenRefine y se realiza la limpieza de datos teniendo en cuenta lo siguiente:
*	sal_codigo -> se aplica el Facet de tipo “texto”
*	sal_destinoint -> se aplica el Facet de tipo “texto”

![image](https://github.com/avillamil92/ProyectoFinal_PasajerosAereosMDE/assets/169549526/27c5d1c9-40ac-4fc9-a8d1-79a967e7aa50)

Se realiza el cluster por el campo “sal_destinoint” y se agrupan los diferentes clusters encontrados.

![image](https://github.com/avillamil92/ProyectoFinal_PasajerosAereosMDE/assets/169549526/46a78e16-1dd1-4d94-8eb0-dacbb90eff88)

Se exporta a un nuevo archivo en formato *.xls.
llegada-mensual-pasajeros-aeropuerto-de-origen-internacional-csv

##### 2.2 Dataset No. 2 – Llegada mensual pasajeros aeropuerto de origen internacional de Medellín

![image](https://github.com/avillamil92/ProyectoFinal_PasajerosAereosMDE/assets/169549526/3a828c59-a760-4c67-bcbd-468a882fd714)
![image](https://github.com/avillamil92/ProyectoFinal_PasajerosAereosMDE/assets/169549526/3f882f7d-1ad3-4dca-8a86-15a650653ca6)

Este dataset tiene las siguientes características:
*	Filas: 6457
*	Columnas: 5

###### 2.1.1 Normalización de datos Dataset No. 2

Se realiza el cargue del archivo llegada_mensual_pasajeros_aeropuerto_de_origen_internacional en OpenRefine y se realiza la limpieza de datos teniendo en cuenta lo siguiente:
*	lle_origenpax -> se aplica el Facet de tipo “texto”

![image](https://github.com/avillamil92/ProyectoFinal_PasajerosAereosMDE/assets/169549526/c893a25f-ef2e-4d81-82c0-206458d6455a)

Se realiza el cluster por el campo “lle_origenpax” y se agrupan los diferentes clusters encontrados.

![image](https://github.com/avillamil92/ProyectoFinal_PasajerosAereosMDE/assets/169549526/dc6c4d16-4b73-46a2-b584-847294d5fc11)

Se exporta a un nuevo archivo en formato *.xls 
salida-mensual-pasajeros-aeropuerto-destino-internacional-csv








