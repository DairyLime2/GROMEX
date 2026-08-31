# CC GROMEX · Sistema integral

Sistema web local para automatizar cotizaciones, cálculo de materiales, control de inventario y seguimiento de producción de block.

## Uso

Abre `index.html` en un navegador moderno. Los cambios se guardan automáticamente en el almacenamiento local del navegador.

## Módulos incluidos

- Resumen operativo con ventas, inventario, alertas y producción semanal.
- Cotizador multiproducto con descuentos, IVA, vigencia y cálculo de insumos.
- Totales de cotización visibles con IVA y sin IVA.
- Consulta, edición, duplicado, impresión/PDF y seguimiento por estados.
- Directorio de clientes con historial de cotizaciones y ventas.
- Directorio de proveedores con contactos, condiciones y materiales suministrados.
- Catálogo editable de productos, materiales, precios y fórmulas de fabricación.
- Inventario valorizado con mínimos, alertas, entradas y salidas.
- Historial de entradas y salidas con filtro por material y rango de fechas.
- Resumen de movimientos y saldo neto del periodo seleccionado.
- Órdenes de producción con validación y consumo automático de materiales.
- Reportes por periodo y exportación de cotizaciones y movimientos a CSV.
- Administración de empresa, usuarios, roles y respaldo JSON.
- Diseño adaptable para escritorio, tableta y teléfono.

## Nota técnica

Esta primera versión funciona sin servidor ni base de datos. Para uso multiusuario o acceso desde varias computadoras, el siguiente paso es conectarla a un backend con autenticación y una base de datos central.
