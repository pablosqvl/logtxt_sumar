# Script para procesar errores de facturación
---
[![GitHub](https://badges.aleen42.com/src/github.svg)](https://github.com/pablosqvl/logtxt_sumar)

El código realiza lo siguiente:
1.   Carga archivos TXT y LOG desde una carpeta.
2.   Procesa los archivos TXT y extrae información de errores del archivo LOG.
3.   Limpia y une la información con descripciones de códigos desde un archivo del nomenclador.
4.   Asigna nombres de los efectores.
5.   Concatena los resultados en un DataFrame y lo exporta como un archivo excel con la fecha del día.

Antes de empezar:
1.   Descargar el [Nomenclador Vigente](https://sistemasmsp.misiones.gob.ar/nacer/modulos/reportes/nomencladores/nomencladores_vigentes.php) y renombrarlo "Nomenclador_Vigente.xls".
2.   Descargar los archivos txt y logs y guardarlos en una carpeta.

[Colab](https://colab.research.google.com/drive/1qcIv1Ajv7AtshCrUdE1xg6Pk2shxe37t?usp=sharing)
