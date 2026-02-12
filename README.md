Ejercicios SQL con Base de Datos Sakila (MySQL)
Este proyecto contiene una serie de consultas SQL realizadas sobre la base de datos de ejemplo Sakila en MySQL.

Sakila es una base de datos diseñada para simular una tienda de alquiler de películas, permitiendo practicar consultas SQL relacionadas con:

Selección de datos

Filtrado con condiciones

Búsquedas con texto

Agregaciones

Uso de JOIN entre tablas

Agrupación de resultados
Tablas principales:

film → información sobre películas

actor → datos de actores

customer → clientes

rental → alquileres

category → categorías de películas

film_actor → relación películas-actores

Ejercicios realizados
✅ 1. Selección de títulos sin duplicados

Obtiene los títulos únicos de las películas.

✅ 2. Películas con clasificación PG-13

Filtra películas según su clasificación.

✅ 3. Búsqueda por palabra clave en descripción

Busca películas cuya descripción contenga la palabra "amazing".

✅ 4. Películas con duración mayor a 120 minutos

Filtra por longitud de película.

✅ 5. Listado completo de actores

Muestra nombre y apellido de todos los actores.

✅ 6. Actores con apellido "Gibson"

Filtra actores mediante búsqueda parcial en el apellido.

✅ 7. Actores con ID entre 10 y 20

Uso del operador BETWEEN.

✅ 8. Películas que no sean R ni PG-13

Uso de NOT IN para excluir valores.

✅ 9. Número de películas por clasificación

Uso de funciones de agregación (COUNT) y agrupación (GROUP BY).

✅ 10. Número total de alquileres por cliente

Uso de JOIN entre tablas customer y rental.

✅ 11. Número total de alquileres por categoría

JOIN múltiples:

category

film_category

inventory

rental

✅ 12. Promedio de duración por clasificación

Uso de función agregada AVG().

✅ 13. Actores que participan en la película "Indian Love"

JOIN entre:

actor

film_actor

film

✅ 14. Películas con "dog" o "cat" en la descripción

Uso de LIKE con patrones.

✅ 15. Películas lanzadas entre 2005 y 2010

Uso de operador BETWEEN para rangos.

film_category → relación películas-categorías

inventory → copias disponibles para alquiler

Tecnologías utilizadas

MySQL

Base de datos Sakila

SQL estándar

Objetivos del ejercicio

Practicar consultas SELECT

Aprender filtros con WHERE

Uso de operadores LIKE, BETWEEN y NOT IN

Comprender relaciones entre tablas mediante JOIN

Aplicar funciones de agregación y agrupación



🎬 API de Películas - Dataset & DataFrame - Consultas en Mysql
📌 Descripción

Este proyecto contiene un dataset de 100 películas expuesto a través de una API y representado como un DataFrame estructurado.

La información incluye datos básicos como título, año, duración, género, clasificación para adultos, utilizando MySQL y conectarlo desde Python mediante mysql-connector-python.

Incluye:

Creación de base de datos

Definición de tabla

Inserción de datos

Consultas básicas

Integración con DataFrame (Pandas)



