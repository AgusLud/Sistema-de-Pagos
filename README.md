# Sistema-de-Pagos
# 💳 Sistema de Pagos Online  
El objetivo es simular un sistema de cobros online y registrar cada transacción en un archivo Excel. 

 Descripción del Proyecto
Este sistema permite registrar pagos realizados por distintas empresas y guardar automáticamente cada venta en un archivo **Excel (.xlsx)** generado desde el mismo navegador usando JavaScript y la librería **SheetJS**.

Está desarrollado con:
- **HTML**
- **CSS**
- **JavaScript**
- **SheetJS (xlsx.min.js)**

No requiere base de datos ni servidor, ya que toda la lógica se ejecuta desde el frontend.

Funcionalidades

 Registrar Pago
El usuario completa un formulario con:
- Empresa
- Monto
- Fecha
- Método de pago
- Código de transacción

Al confirmar, el sistema:
1. Guarda el registro en memoria.
2. Genera/actualiza un archivo Excel con todas las ventas.
3. Descarga el archivo **VentasRegistradas.xlsx** automáticamente.

---

## 📁 Estructura del Proyecto
