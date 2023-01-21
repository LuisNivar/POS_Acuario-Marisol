> **Note**
> Este repositorio no contiene el código, ya que ya no tengo los derechos sobre él. Solo estoy mostrando su funcionalidad con fines de presentación, con el debido permiso del cliente.

# POS ACUARIO MARISOL
Diseñé, desarrollé e implementé un Point of Sales (PoS, Punto de ventas) para un establecimiento pequeño, de venta de peces, peceras, alimentos y accesorios alusivos a estos.

## Tecnologías  
Microsoft SQL Server, .NET Framework y C# 

## Desafio
Agilizar el proceso de ventas, control de inventario y facturación del negocio. Al tratarse de mercancía viva, hay que tomar en cuenta la muerte de los peces para el control de inventario, el vencimiento de alimentos y medicación. Idear la manera de identificar los peces de los diferentes proveedores, el cambio de precios en la mercancía al pasar el tiempo y demás consideraciones del contexto. Una vez estudiado el caso, se dividió el sistema en los siguiente módulos.

* Home (Dashboard para el resumen de ventas)
* Clientes (mini CRM, Customer Relationship Manager)
  * Listado de clientes (CRUD + Micro Dashboard de ventas)
  * Buscador (Peces + color + categoría)
 * Proveedores (CRUD + Label Manager)
 * Inventario (CURD + Visor de imagenes)
 * Ventas (Car selling + Item Grid _(con fotos)_)
 * Facturación
  * Facturas
  * Resumen del día (venta neta, utilidad, perdidas, gastos, descuentos + CRUD de perdidas)
  
## Resultados
Al implementar el sistema, el negocio pudo hacer un análisis de los productos demandados, las cantidades y marcas de alimentos, y tipos de peces que realmente solicitan los clientes, así como la entrega facturas impresas. Gracias al mini CRM (del modulo de clientes), se pudo incursionar en las ventas por encargo; todo esto supuso una media de aumento del 110% en las ventas netas, y una disminución del 250% en la muerte de peces (por tener un mejor conocimiento en la gestión de inventario, los mejores proveedores de especies en particular y las cantidades mantenibles en los acuarios).

## Screenshoots
![image](https://user-images.githubusercontent.com/45906349/213887501-f4dab507-bc6e-4cfb-955e-6b62031bf3cd.png)

![image](https://user-images.githubusercontent.com/45906349/213887503-e38b08d0-1f3f-4987-bf03-63c81ef51b97.png)

![image](https://user-images.githubusercontent.com/45906349/213887577-5e1080d7-b500-454e-a576-2461f381f1c3.png)

![image](https://user-images.githubusercontent.com/45906349/213887653-2f07bb3e-3113-4c08-9405-24af217970ea.png)

![image](https://user-images.githubusercontent.com/45906349/213887663-05d958ae-9ba6-4640-bf21-07b3c770327d.png)

### Gestión de etiquetas 
![image](https://user-images.githubusercontent.com/45906349/213887790-f6b45cb0-9b5c-4ea5-8a29-b3ec960d3e91.png)
