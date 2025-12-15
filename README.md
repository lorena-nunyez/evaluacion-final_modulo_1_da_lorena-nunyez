# 🛒 TiendaOnline - Evaluación Final Módulo 1 (Data Analytics)

Este repositorio contiene la solución al ejercicio de evaluación final del **Módulo 1 de Data Analytics**.  
El proyecto consiste en implementar una clase `TiendaOnline` en Python que gestiona un inventario de productos y permite realizar operaciones básicas como agregar, buscar, actualizar, eliminar y calcular el valor total del inventario.

---

🚀 Cómo arrancar el proyecto
1. Clona este repositorio en tu ordenador
2. Abre el archivo Jupyter Notebook (.ipynb) en tu entorno preferido:
3. Ejecuta las celdas paso a paso para probar los métodos de la clase.


📚 Funcionalidades principales
La clase TiendaOnline incluye los siguientes métodos:
    - agregar_producto(nombre, precio, cantidad) → Añade un producto nuevo o actualiza la cantidad si ya existe.
    - ver_inventario() → Muestra todos los productos con nombre, precio y cantidad.
    - buscar_producto(nombre) → Busca un producto por nombre y muestra sus detalles.
    - actualizar_stock(nombre, cantidad) → Modifica la cantidad de un producto existente.
    - eliminar_producto(nombre) → Elimina un producto del inventario.
    - calcular_valor_inventario() → Calcula el valor total del inventario (precio × cantidad).


🧾 EJEMPLO DE USO
🟢 Crear instancia de la tienda
ludópolis = TiendaOnline()
ludópolis.inventario = [
    {'nombre':'Aventureros al tren', 'precio': 45.5, 'cantidad': 5},
    {'nombre':'Genial', 'precio': 35.3, 'cantidad': 2},
    {'nombre':'Tsuro', 'precio': 41, 'cantidad': 3},
    {'nombre':'Fantasma Blitz', 'precio': 24.9, 'cantidad': 8},]
ludópolis.ventas_totales = 0

🟢 Agregar productos
ludópolis.agregar_producto("Camisa", 20, 5)
ludópolis.agregar_producto("Pantalón", 30, 3)
🟢 Ver inventario
ludópolis.ver_inventario()
🟢 Buscar producto
ludópolis.buscar_producto("juego")
🟢 Actualizar stock
ludópolis.actualizar_stock("juego", cantidad)
🟢 Eliminar producto
ludópolis.eliminar_producto("juego")
🟢 Calcular valor total
ludópolis.calcular_valor_inventario()


🎯 Objetivo
Este proyecto sirve como práctica para:
    - Manejo de clases y objetos en Python.
    - Uso de listas y diccionarios.
    - Aplicación de bucles y condicionales.
    - Buenas prácticas de programación y documentación.


📌 Notas
- El repositorio incluye este README para explicar cómo arrancar y probar el proyecto.
- La parte BONUS (gestión de clientes y compras) puede añadirse en futuras versiones.


👩‍💻 Autoría
Proyecto realizado como parte de la Evaluación Final del Módulo 1 de Data Analytics.
