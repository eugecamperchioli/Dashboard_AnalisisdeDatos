# Dashboard_AnalisisdeDatos
 proyecto del primer modulo del programa - Dashboard & Analisis de Datos

#  ANALISIS DE VENTAS DE UNA DISTRIBUIDORA A CANALES DE SUPERMERCADO :bar_chart: 

## 1. Descripcion:
Este proyecto realiza un analisis exploratorio de las ventas de una distribuidora en America Latina. El objetivo es identidicar tendencias, patrones y comportamientos basadas en datos historicos usando tecnicas de modelado
estadistico.

## 2. Estructura del proyecto:
```bash
|------  DATOS
   |---- BD_distribuidora.cvs # Datos originales
|------  EXCEL
   |---- Proyecto1_dashboard.xlsx # Excel con datos originales
|------  README # Descripcion del proyecto
```

## 3. Descripcion de columnas del cojunto de datos
El conjunto de datos contiene informacion sobre las ventas por tipo de producto, categoria, cliente y periodo de tiempo de una empresa de consumo masivo en America latina.

- Producto Descripcion: nombre de los SKU's vendidos por la empresa.
- Categoria: clasficiacion de los productos por categorìa de venta.
- Calibre: presentacion/medidas de los productos.
- Marca: marca del producto proveida por cliente.
- Marca Real: limpieza y recategorizacion de las marcas.
- Cliente Codigo: identificador unico para cada cliente.
- Cliente Nombre: nombre del cliente.
- Ventas Totales GS: ventas totales en moneda guaranies
- Cantidad: cantidad de ventas totales
- Ventas Totales EUR: ventas totales en moneda euros.
- Ventas Unitarias EUR: ventas unitarias en moneda euros.
- Nro Documento: identificador para cada transaccion.
- Vendedor Descripcion: nombre del vendedor.
- Fecha: fecha de la compra 
- Mes: mes de la compra 
- Año: año de la compra
- Semestre: semestre de la compra

## 4. Resultados y conclusiones:
- El promedio de crecimiento de las ventas YoY es del 28%.
- Los clientes Catedral, Harrison y Horacio crecieron por encima del mercado 2024 vs 2023.
- el cliente Muñoz representa el 50% de la facturacion, se podria trabajar con los demas clientes para aumentar su cuota.
- 10 categorias identificadas hacen el 70% de la facturacion, si el mercado se encuentra saturado se podrian desarrollar mejor otras categorias. 
- Catedral y Harrison no cumplen con el ranking de ventas promedio por marca, por lo que habria posibilidad de trabajar en esos clientes.
- identificamos un aumento en las ventas en el ultimo trimestre del año y en el mes de abril. 

## 5. Proximos pasos
- cruzar información con la salida de caja de los clientes para evaluar si el comportamiento es el mismo
- explorar factores externos como nuevos lanzamientos, campañas de marketing o fechas especiales de promocion
