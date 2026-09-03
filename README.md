# XAUUSD Trading Journal

App web (PWA instalable) para registrar tus operativas de XAUUSD y ver cómo vas cada mes.
Funciona en el celular y sin conexión. Los datos se guardan en tu dispositivo.

## Funciones

- **Calendario** tipo heatmap: cada día en verde (ganancia), rojo (pérdida) o neutro.
- **Varias operativas por día**, cada una con: monto, resultado en **R**, dirección
  (compra/venta), **sesión** (Londres/New York), si **seguiste el plan**, y notas.
- **Estadísticas del mes:** P&L, win rate, profit factor, expectativa, drawdown,
  rachas, R promedio, adherencia al plan y desempeño **por sesión**.
- **Curva de equity** y distribución diaria.
- **Metas y límites:** meta mensual con barra de progreso y aviso de pérdida máxima.
- **Copia de seguridad:** exportar/importar **JSON** y exportar **CSV**.
- **Offline:** service worker que cachea la app para usarla sin internet.

## Importante sobre tus datos

Se guardan en el navegador de este dispositivo (`localStorage`). **Exporta un respaldo
JSON con frecuencia** (Ajustes → Copia de seguridad) y guárdalo en tu nube: si cambias de
teléfono o borras los datos del navegador, se perderían.

## Uso

Abre `index.html` (o la URL de GitHub Pages). Toca un día para registrar operativas.
