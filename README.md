# factpy-json
Ejemplo de json para FACTPY V1

# Campos
| Campo                     | Descripción                                                                                                            |
|---------------------------|------------------------------------------------------------------------------------------------------------------------|
| Fecha                     | Fecha de emisión del documento en formato AAAA-MM-DD.                                                                   |
| Fecha/hora                | Fecha y hora de emisión del documento en formato AAAA-MM-DDTHH:mm:ss (ejemplo: 2023-05-12T16:30:00).                    |
| cdcAsociado               | En caso de ser una nota de crédito, el número del documento al que corresponde. En caso contrario, este campo está vacío.|
| Punto                     | Punto de expedición del documento.                                                                                     |
| Numero                    | Número de documento.                                                                                                   |
| Moneda                    | Moneda utilizada en la transacción según la tabla del manual técnico del Sifen.                                        |
| tipoDocumento             | Tipo de documento. 1: factura, 5: nota de crédito.                                                                      |
| tipoEmision               | Tipo de emisión. 1: normal, 2: contingencia.                                                                            |
| tipoTransaccion           | Tipo de transacción según la tabla del manual técnico del Sifen.                                                       |
| Receiptid                 | ID interno del sistema cliente.                                                                                        |
| Ruc                       | RUC del cliente.                                                                                                       |
| Nombre                    | Nombre del cliente.                                                                                                    |
| Cpais                     | País del cliente. Solo se acepta PYG.                                                                                   |
| codigoSeguridadAleatorio  | Código de seguridad aleatorio de 9 dígitos no repetido por punto.                                                       |
| Items                     | Detalles de los productos o servicios incluidos en la factura o nota de crédito.                                       |
| Descripcion               | Descripción del producto o servicio.                                                                                   |
| Codigo                    | Código del producto o servicio.                                                                                         |
| tipoIva                   | Tipo de IVA del producto o servicio.                                                                                    |
| UnidadMedida              | Unidad de medida del producto o servicio.                                                                               |
| ivaTasa                   | Tasa de IVA aplicada al producto o servicio.                                                                            |
| ivaAfecta                 | Indica si el producto o servicio está sujeto a IVA. 1: sí, 0: no.                                                      |
| Cantidad                  | Cantidad de unidades del producto o servicio.                                                                           |
| PrecioUnitario            | Precio unitario del producto o servicio.                                                                                |
| PrecioTotal               | Precio total del producto o servicio (cantidad x precio unitario).                                                     |
| BaseGravItem              | Base gravable del producto o servicio.                                                                                  |
| LiqIvaItem                | Valor del IVA calculado sobre el producto o servicio.                                                                   |
| tipoPago                  | Tipo de pago según la tabla del manual técnico del Sifen.                                                               |
| Monto                     | Monto total de la transacción.                                                                                          |
| totalPago                 | Monto total de la transacción.                                                                                          |
| totalRedondeo             | Valor del redondeo de la transacción.                                                                                   |
| País                      | País de la transacción. Solo se acepta PYG.                                                                              |

