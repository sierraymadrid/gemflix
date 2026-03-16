# API Endpoints — Gemflix

## Objetivo
Documentar los endpoints principales de TMDB que usará Gemflix para obtener películas y detalles.

## Endpoints principales

## Endpoints principales

| Endpoint | Uso en Gemflix | Método | Parámetros clave | Respuesta esperada |
|---|---|---|---|---|
| `/trending/all/day` | Mostrar tendencias en la portada | GET | `api_key`, `language` | Lista de contenidos en tendencia |
| `/movie/popular` | Mostrar catálogo principal de películas | GET | `api_key`, `language`, `page` | Lista paginada de películas populares |
| `/search/movie` | Buscar películas por texto | GET | `api_key`, `language`, `query`, `page` | Resultados de búsqueda |
| `/movie/{id}` | Ver detalle de una película concreta | GET | `api_key`, `language`, `movie_id` | Información completa de una película |

## Notas iniciales
- La API devuelve datos en JSON.
- Será necesario usar una API key de TMDB.
- Más adelante añadiremos ejemplos de respuesta y riesgos.