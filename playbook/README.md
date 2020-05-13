 # Playbook Respuesta a Incidentes

## Fuzzing de inteligencia artificial (AIF)

![Company Logo](https://raw.githubusercontent.com/vadymmarkov/Fakery/master/Images/logo.png)

## ¿Qué es AIF?

Fuzzing es una técnica de pruebas de software, a menudo automatizado o semiautomatizado, que implica proporcionar datos inválidos, inesperados o aleatorios a las entradas de un programa de ordenador.

Mientras que AIF (Artificial Intelligence Fuzzing) provee la capacidad de realizar un aprendizaje autónomo permitiendo descubrir vulnerabilidades en periodos mucho más acotados.

## Preparación

### Contactos encargados

1. Juan Perez
2. María Gonzalez

### Comprobación de sistemas y redes

Se deberá realizar la comprobación de los firewalls, servicio de logs, base de datos y estado de los servidores de las últimas 48 horas.

En paralelo se deberá verificar el estado de los elementos mencionados anteriormente en contraste con el inventario.

Las conclusiones y análisis se deberán dejar registrados ya sean como incidencias en caso de existir referenciando al sistema o red involucrado, o bien registro de comprobación sin cambios.

## Identificación

Para identificar se deberá utilizar herramientas de análisis:

1. Forninet
2. Cloud Monitoring
   1. Logs de servidores
   2. Logs de red VPC
   3. CPU/Bytes entrantes y salientes
3. Power Fuzzing

## Contención

Dado el caso de identificar el origen se procederá a deshabilitar en un periodo máximo de 24 horas el servicio, endpoint o archivo afectado. En el caso que no se logre realizar un parche en el periodo máximo se extenderá solo autorizado por los contactos asignados.

## Remedio

Se tendrán 24 horas para realizar un hotfix o parche al recurso afectado, el cual posteriormente deberá ser testeado automáticamente por Power Fuzzing.

## Recuperación

Luego de realizar exitosamente el parche y validado por Power Fuzzing se deberá pasar a la etapa de producción. Dejando registro en el versionamiento sobre el parche.

## Repercursiones

Se deberá redactar un informe con la información de la vulnerabilidad detectada por método fuzzing contemplando la siguiente información:

1. Recursos involucrados
2. Categoría
3. Importancia [Alto, Medio, Bajo]
4. Tipo de recurso
5. Efectos
6. Coste
   1. Tiempo fuera
   2. Tiempo de parche
   3. Valuación monetaria

## Aprendizaje

Se deberá realizar fuertes testing a los recursos que utilicen recursos similares al/los afectados.

Al finalizar se deberá crear un informe sobre las posibles vulnerabilidades siguiendo los pasos desde el punto 1 de este documento.



## Copyrights

Se concede permiso para copiar, distribuir, y/o modificar este documento bajo los términos de la Licencia de Documentación Libre GNU, en su versión 1.3, o cualquiera de las versiones publicadas de manera posterior por la Free Software Foundation; sin Secciones invariantes (invariant sections), sin Textos de Portada (front-cover texts), y sin Textos de Contratapa (back-cover texts). Una copia de esta licencia se incluye en la sección &quot;Licencia de documentación libre GNU&quot;.

**Creada por Sebastian Vargas**