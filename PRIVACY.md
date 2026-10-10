# Politica de privacidad — Hiking Weather

Ultima actualizacion: 10 de octubre de 2026.

Hiking Weather es una aplicacion de meteorologia para actividades outdoor en Espana. Esta politica describe que datos se usan y con quien se comparten.

## Datos que trata la app

- **Ubicacion aproximada o precisa** (si activas GPS): se usa solo en **primer plano** para mostrar el tiempo, el mapa y avisos del punto o municipio. No se envia a nuestros servidores (la app no tiene backend propio) y no se usa para publicidad.
- **Claves API de AEMET** (opcional, las introduces tu): se guardan en el dispositivo y se envian solo a AEMET OpenData si eliges ese proveedor.
- **Rutas GPX** (si importas un archivo): se leen y pueden guardarse en el dispositivo para la prevision sobre el track. Pueden usarse a la vez que el GPS (el pin te sigue; la meteo sigue la ruta). No se suben a un servidor nuestro.
- **Ajustes** (proveedor, intervalo de refresco, modo actividad, muestreo GPX, malla del mapa): se guardan en el dispositivo.

## Con quien se comparte

La app consulta servicios de terceros para mostrarte el tiempo y el mapa. Esas peticiones pueden incluir coordenadas o el nombre del municipio:

- Open-Meteo (prediccion, viento/lluvia actuales, calidad del aire; tambien la malla del mapa)
- AEMET OpenData (si pegas tu API key y eliges AEMET; prevision municipal)
- PNOA del Instituto Geografico Nacional (mapa / ortofoto de Espana)
- Institut Cartografic i Geologic de Catalunya (ortofoto en Catalunya)
- ArcGIS / Agents Rurals (capas de Plan Alfa, solo si el punto esta en Catalunya)
- RSS de Proteccio Civil / Generalitat (avisos relacionados, cuando hay datos)
- Geocoder de Android (buscar o resolver municipio)

Cada servicio aplica su propia politica.

## Lo que no hacemos

- No creamos cuenta de usuario.
- No mostramos anuncios.
- No vendemos datos.
- No accedemos a la ubicacion en segundo plano.
- No enviamos rutas GPX ni claves AEMET a un servidor propio.

## Conservacion

Los datos se quedan en el telefono. Puedes borrar la app para eliminarlos. Las copias de seguridad del sistema de Android estan desactivadas en esta app (`allowBackup=false`).

## Limitacion de responsabilidad

Hiking Weather no genera los datos meteorologicos: los muestra tal como los envian Open-Meteo/ECMWF, AEMET, ICGC, PNOA IGN, Agents Rurals y Proteccio Civil. El nivel de riesgo meteo mostrado en la app es orientativo (calculado a partir de la prevision) y no sustituye avisos oficiales. No se garantiza la exactitud. El uso es bajo tu responsabilidad.

## Contacto

Pagina de esta politica:  
https://carlos1811.github.io/hikingweather-privacy/

Para preguntas sobre privacidad, abre un issue en  
https://github.com/carlos1811/hikingweather-privacy
