# ESTGAR Studio · Cotizador v18

Sistema interno/PWA para ESTGARSTUDIO SpA.

## Incluye
- Dashboard responsive para escritorio, tablet y móvil.
- Cotizaciones, clientes, historial y tarifas editables.
- Boleta/factura como documento de presentación interno, con IVA configurable.
- Impresión detallada tamaño Carta y PDF compartible por WhatsApp.
- Centro documental dentro de la misma aplicación.
- Contratos de prestación de servicios vinculados a cotizaciones.
- Campos editables para fechas, plazos, alcance, entregables, revisiones, condiciones especiales, forma de pago y cláusulas.
- Cálculo automático de subtotal, descuento, IVA, total, anticipo y saldo.
- Contratos guardados localmente para editar, imprimir o eliminar.
- Logo original de ESTGAR incorporado a los documentos.

## Marco contractual
El modelo de contrato fue redactado como plantilla editable considerando el marco chileno aplicable a contratación de servicios, protección del consumidor, documentos/firma electrónica y propiedad intelectual. No reemplaza revisión jurídica del caso concreto.

## Datos
Los datos y documentos se almacenan localmente en el navegador mediante localStorage. No se envían a un servidor.


### Guardado reforzado
La V18 verifica que la cotización exista realmente en el almacenamiento local después de guardarla y muestra el motivo si el navegador bloquea el almacenamiento.
