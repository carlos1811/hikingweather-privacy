# Politica de privacidad — Hiking Weather

Ultima actualizacion: 12 de septiembre de 2026.

Hiking Weather es una aplicacion de meteorologia para actividades outdoor en Catalunya. Esta politica describe que datos se usan y con quien se comparten.

## Datos que trata la app

- **Ubicacion aproximada o precisa** (si activas GPS): se usa solo en primer plano para mostrar el tiempo, el mapa y avisos del municipio. No se envia a nuestros servidores (la app no tiene backend propio) y no se usa para publicidad.
- **Claves API de AEMET** (opcional, las introduces tu): se guardan en el dispositivo y se envian solo a AEMET OpenData si eliges ese proveedor.
- **Rutas GPX** (si importas un archivo): se leen en el dispositivo para evaluar la prevision sobre el track. No se suben a un servidor nuestro.
- **Ajustes** (proveedor, intervalo de refresco, modo actividad): se guardan en el dispositivo.

## Con quien se comparte

La app consulta servicios de terceros para mostrarte el tiempo y el mapa:

- Open-Meteo (prediccion ECMWF y calidad del aire)
- AEMET OpenData (si pegas tu API key y eliges AEMET)
- Institut Cartografic i Geologic de Catalunya (mapa base / ortofoto)
- ArcGIS / Agents Rurals (capas de Plan Alfa)
- Geocoder de Android (buscar municipio)

Esas peticiones incluyen coordenadas o el nombre del municipio. Cada servicio aplica su propia politica.

## Lo que no hacemos

- No creamos cuenta de usuario.
- No mostramos anuncios.
- No vendemos datos.
- No accedemos a la ubicacion en segundo plano.

## Conservacion

Los datos se quedan en el telefono. Puedes borrar la app para eliminarlos. Las copias de seguridad del sistema de Android estan desactivadas en esta app (`allowBackup=false`).

## Contacto

Para preguntas sobre privacidad, abre un issue en este repositorio:
https://github.com/carlos1811/hikingweather-privacy
