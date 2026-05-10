# 📖 Bookverse API

API REST desarrollada con Django y Django REST Framework para gestionar una biblioteca virtual.

---

## 🚀 Descripción

Este proyecto permite administrar libros y autores mediante una API REST.

* Cada libro está asociado a un autor.
* Se pueden realizar operaciones CRUD completas.
* Incluye búsqueda por título o género.

---

## 🛠️ Tecnologías usadas

* Python
* Django
* Django REST Framework
* SQLite

---

## 🌐 Endpoints disponibles

### 📚 Libros

* GET /api/libros/ → Listar libros
* POST /api/libros/ → Crear libro
* GET /api/libros/{id}/ → Obtener libro
* PUT /api/libros/{id}/ → Actualizar libro
* DELETE /api/libros/{id}/ → Eliminar libro

### ✍️ Autores

* GET /api/autores/ → Listar autores
* POST /api/autores/ → Crear autor
* GET /api/autores/{id}/ → Obtener autor
* PUT /api/autores/{id}/ → Actualizar autor
* DELETE /api/autores/{id}/ → Eliminar autor

---

## 🔍 Búsqueda

Permite buscar libros por título o género:

```
GET /api/libros/?search=novela
```

---

## 🧪 Ejemplo de uso

### Crear Autor

```json
{
  "nombre": "Mario Vargas Llosa",
  "nacionalidad": "Peruano"
}
```

---

### Crear Libro

```json
{
  "titulo": "La ciudad y los perros",
  "anio_publicacion": 1963,
  "genero": "novela",
  "autor": 1
}
```

---


## 👨‍💻 Autor

Gean Pierre Ayala

---
