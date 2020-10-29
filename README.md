# ASPNetCore_&_EFC_DBFirst
Base de datos existentes DBFirst

## Enfoque Database First
```
Este enfoque se usa cuando la base de datos esta lista, luego Entity Framework completara su deber y creara las entidades.
Si ya tiene una base de datos diseñada y no desea hacer un esfuerzo adicional, puede seguir este enfoque.
Puede modificar la base de datos manualmente y actualizar el modelo desde la base de datos.
Por lo tanto, podemos decir que Entity Framework puede crear sus clases de modelo basadas en tablas y columnas de la base de datos relacional.
```

## Creación de la base de datos dbproductos, la relación es de Uno a Muchos:
- `1 Categoría puede tener Mucho Productos`
![Relacion Uno a Muchos](Relacion_CategoriaProductos.png)

## Instalacion Entity Framework Core
Instalacion del paquete `Microsoft.EntityFrameworkCore.SqlServer`
![Entity Framework Core](Entity%20Framework%20Core.jpg)

Instalacion del paquete `Microsoft.EntityFrameworkCore.Tools`
![Microsoft.EntityFrameworkCore.Tools](Microsoft.EntityFrameworkCore.Tools.jpg)

Desde la carpeta dependencias se ven los 2 paquetes instalados.
![Paquetes](Paquetes.jpg)
