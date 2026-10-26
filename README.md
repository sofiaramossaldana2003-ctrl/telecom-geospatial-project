# Análisis geoespacial de internet fijo en Perú

Proyecto de análisis de conexiones de internet fijo a nivel distrital, orientado a explorar la distribución territorial de la conectividad y las brechas digitales con datos del sector de telecomunicaciones.

## Explorar el proyecto

- [Informe del análisis](Análisis_Geoespacial_de_las_Conexiones_de_Internet_Fijo_en_el_Perú_a_Nivel_Distrital.pdf)
- [Video del mapa](Mapa.mp4)
- [Carpeta de datos y diccionario de variables](DATOS/)
- [Carpeta del notebook](notebooks/)

## Estado de los archivos

El repositorio contiene un informe PDF, un video y un diccionario de datos en Excel. El CSV y el archivo `.ipynb` actualmente contienen únicamente un salto de línea; falta subir sus versiones completas para que el análisis pueda reproducirse.

Los resultados y su alcance deben consultarse en el informe. Esta presentación no incorpora cifras que no hayan sido verificadas en sus fuentes.

## Organización actual

| Ubicación | Contenido |
| --- | --- |
| Raíz del repositorio | README, informe PDF y `Mapa.mp4` |
| `DATOS/` | Diccionario de datos en Excel y CSV pendiente de completar |
| `notebooks/` | Archivo del notebook pendiente de completar |

## Herramientas declaradas del proyecto

Python, Pandas, GeoPandas, Folium/Plotly y Google Colab. Las versiones y dependencias deberán documentarse junto con el notebook completo.

## Pendientes para reproducir el análisis

- [ ] Subir el notebook completo y comprobar que abre correctamente.
- [ ] Reponer el CSV o documentar cómo descargar los datos desde su fuente original.
- [ ] Identificar la entidad fuente, el enlace de descarga, los periodos utilizados y la fecha de consulta.
- [ ] Documentar los pasos de limpieza, las llaves geográficas y el cálculo de indicadores.
- [ ] Registrar las dependencias y las instrucciones de ejecución.
- [ ] Añadir una imagen de vista previa del mapa y una explicación de sus principales resultados.

## Alcance

El número de conexiones no equivale directamente al número de personas u hogares conectados. Cualquier indicador de penetración debe especificar su denominador, periodo y fuente antes de interpretarse.
