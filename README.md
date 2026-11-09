# Historial de precios de motocicletas

Dashboard público: https://jorgesqyamaha-ux.github.io/benchmarking-motos-mercado/

- `index.html`: la página del dashboard (pestañas por categoría, modelo vs. competencia y cambios del mes).
- `historial.js`: historial fijo del Excel, enero 2017 a octubre 2026.
- `mensual.js` y `cilindradas.js`: se regeneran cada mes a partir de `datos/`.
- `datos/precios_mensuales.csv`: desde noviembre 2026, precio de lista, bono y precio final con promoción (MXN) de los sitios oficiales de cada marca.
- `datos/cilindradas.csv`: catálogo de modelos (marca, grupo, categoría, modelo, cc).
- `datos/modelos_2026-10.csv`: modelos con precio en octubre 2026, para que la búsqueda mensual no pierda marcas.

Se actualiza automáticamente el día 3 de cada mes.
