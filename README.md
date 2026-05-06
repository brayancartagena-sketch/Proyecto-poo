# Proyecto-poo
Sistema de Gestión para Tienda de ropa





🛍️ Tienda de Ropa (POO en Java)
Este mini proyecto aplica todos los temas principales de Programación Orientada a Objetos (POO) en Java.
El objetivo es modelar una tienda de ropa con productos, empleados y métodos de pago, aplicando principios SOLID y buenas prácticas.








📌 Conceptos aplicados
✔ Modelado con clases y objetos → Producto, Persona, Empleado, Tienda
✔ Encapsulamiento → uso de private, protected, getters y setters
✔ Constructores → por defecto y parametrizados en clases como Producto
✔ Abstracción → clase abstracta Persona con método abstracto mostrarRol()
✔ Herencia → Empleado hereda de Persona y se especializa en Administrador y Vendedor
✔ Polimorfismo












Sobrescritura con @Override en métodos como mostrarRol()
Sobrecarga en constructores
✔ Interfaces →
Descontable: calcula descuentos en productos
MetodoPago: permite implementar distintos métodos de pago
✔ Colecciones → ArrayList<Producto> en Tienda
✔ Principios SOLID
SRP (Responsabilidad Única): cada clase tiene un propósito claro (Producto, Empleado, PagoEfectivo, etc.)
OCP (Abierto/Cerrado): fácil agregar nuevos métodos de pago o tipos de empleados sin modificar el código existente
