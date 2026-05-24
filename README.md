# Trading Journal — Dashboard

Sistema completo de trading journal para futuros (ES, MES, NQ, MNQ).

## Archivos

| Archivo | Descripción |
|---------|-------------|
| `dashboard-unified.html` | Dashboard principal — abrir en navegador |
| `mobile.html` | App móvil PWA — guardar en Android/iOS |
| `TradingJournal_v16.gs` | Apps Script para Google Sheets (backend) |
| `ImportarNinja.gs` | Importador de trades desde NinjaTrader |

## Configuración

1. En Google Sheets: Extensions → Apps Script → pegar `TradingJournal_v16.gs`
2. Deploy → New deployment → Web app → Anyone → Deploy
3. Copiar la URL del deployment
4. En el dashboard: ⚙ Configuración → pegar la URL → Guardar

## Hoja de cálculo

Crear una hoja llamada `HistorialReal` con las columnas necesarias.
El sistema crea automáticamente la hoja `Config`.
