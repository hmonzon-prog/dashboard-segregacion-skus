# Dashboard Segregación de SKUs

Dashboard web que muestra el estado de segregación de SKUs conectándose a Google Sheets.

## Características

- Tarjetas resumen: Total SKUs, Segregados, Pendientes, Anulados
- Gráfico doughnut de estado
- Gráfico de barras por tipo de ubicación (Piso, Balda Grande, Balda Chica)
- Tabla resumen por tipo de ubicación
- Tabla detalle de todos los SKUs
- Auto-refresh cada 60 segundos

## Datos

Se conecta a Google Sheets y muestra:
- **Artículo**: Código SKU
- **Descripción**: Nombre del producto
- **Ubicación**: Ubicación actual
- **Tipo Loc**: Piso, Balda Grande, Balda Chica, Anulada
- **Stock Físico**: Cantidad en inventario
- **Destino**: Ubicación destino (si está segregado)
- **QTY SKU**: Cantidad segregada

## Uso

1. Abrir `index.html` en un navegador
2. Los datos se cargan automáticamente desde Google Sheets
3. Se actualiza cada 60 segundos

## GitHub Pages

El dashboard está disponible en: `https://hmonzon-prog.github.io/dashboard-segregacion/`
