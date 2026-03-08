# Shopify – Mostrar NIF / CIF en facturas (Order Printer)

Documentación de la solución para mostrar el campo personalizado NIF/CIF en las facturas generadas con Shopify Order Printer.


## Problema

Shopify de forma nativa no muestra automáticamente campos personalizados como NIF o CIF en las facturas.  
Aunque el dato existe en el pedido o en los campos del cliente, no aparece en la plantilla de factura.

## Objetivo

Mostrar el NIF / CIF del cliente dentro de la factura generada por Shopify.

## Solución

Se añadió una modificación en la plantilla de la App Order Printer para leer el campo personalizado del pedido y mostrarlo en la sección de datos del cliente.

## Pasos técnicos

1. Crear o identificar el campo personalizado donde se guarda el NIF/CIF.
2. Acceder a la plantilla de factura en **Shopify Order Printer**.
3. Modificar el template Liquid para recuperar el valor del campo.
4. Insertar el campo en la sección de información del cliente en la factura.

## Resultado

La factura generada desde Shopify ahora muestra correctamente el NIF/CIF del cliente.
