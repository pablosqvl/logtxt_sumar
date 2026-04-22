# Script para procesar errores de facturación
---
[![GitHub](https://badges.aleen42.com/src/github.svg)](https://github.com/pablosqvl/logtxt_sumar)

Este script en Python fue diseñado para ejecutarse en **Google Colab** y automatizar el procesamiento de archivos de datos con extensión **`.TXT`**, sus archivos de errores asociados **`_LOG.TXT`**, y un archivo de **nomenclador vigente** en formato Excel.

El objetivo del proceso es:

- permitir la **carga manual** de los archivos desde la computadora del usuario;
- identificar, a partir de los archivos LOG, cuáles son los registros observados con error;
- recuperar esos registros desde el archivo TXT original;
- enriquecerlos con la **descripción del código** usando el nomenclador;
- agregar el **nombre del efector** a partir del código;
- consolidar todos los resultados en un único archivo **Excel `.xlsx`** descargable.

Antes de empezar:
1.   Descargar el [Nomenclador Vigente](https://sistemasmsp.misiones.gob.ar/nacer/modulos/reportes/nomencladores/nomencladores_vigentes.php) y renombrarlo "Nomenclador_Vigente.xls".
2.   Descargar los archivos txt y logs y guardarlos en una carpeta.

Pablo Esquivel
