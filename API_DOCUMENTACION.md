# 📘 API: Gestión de Productos

**Base URL:** `http://localhost:8000/api`

---

## Endpoints Disponibles

### ➕ GET /productos
- **Descripción:** Obtiene todos los productos.
- **Respuesta:**
```json
[
  {
    "id": 1,
    "nombre": "Producto A",
    "descripcion": "Descripción A",
    "precio": "10.00"
  }
]
```

---

### ➕ POST /productos
- **Descripción:** Crea un nuevo producto.
- **Body:**
```json
{
  "nombre": "Producto B",
  "descripcion": "Descripción B",
  "precio": 25.99
}
```

---

### 📝 GET /productos/{id}
- **Descripción:** Obtiene un producto específico por ID.

---

### 🔁 PUT /productos/{id}
- **Descripción:** Actualiza un producto existente.
- **Body:** igual que POST.

---

### ❌ DELETE /productos/{id}
- **Descripción:** Elimina un producto por ID.

---

## 🛡 Seguridad

Actualmente no se requiere autenticación.  
(Puede integrarse Laravel Sanctum o Passport para agregar autenticación.)

---

## 🧱 Tecnología

- **Framework:** Laravel 10
- **Base de datos:** MySQL
- **Formato de respuesta:** JSON
