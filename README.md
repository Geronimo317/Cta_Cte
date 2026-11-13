# Conciliación de cuentas corrientes

Web para revisar las cuentas corrientes de clientes a partir del export Excel de Finnegans.

## Cómo se usa

1. Abrí la web (GitHub Pages) o el archivo `index.html`.
2. Arrastrá uno o varios exports de cuenta corriente de Finnegans.
3. Revisá por cliente: comprobantes impagos con días de atraso, cobranzas sin comprobante y saldo en $ y US$.

Los Excel se procesan en el navegador y no se envían a ningún servidor. No subas exports a este repositorio.

## Cómo concilia

El export no trae las aplicaciones, así que se deducen: primero busca cobranzas/compensaciones que cierren exacto con un comprobante (hasta 4, entre 30 días antes y 90 después) y el resto lo aplica por antigüedad (FIFO). Las anulaciones se emparejan y se excluyen.
