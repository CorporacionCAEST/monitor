# CAEST Oracle Health Monitor

Pequeño dashboard web (HTML + CSS + JavaScript) para monitorear en tiempo real el estado del endpoint de salud de Oracle y mostrar un historial de consultas, sin necesidad de refrescar el navegador.

## ¿Qué hace?

- Consulta periódicamente el endpoint de health check de Oracle.
- Muestra la **respuesta actual** en formato JSON con **colores (syntax highlighting)**.
- Muestra un **historial** (últimos 20 registros) con:
  - Hora de la consulta
  - Código HTTP
  - Latencia (ms)
  - Preview de la respuesta
- Permite escoger el **intervalo de consulta** desde un `<select>` (1s, 5s, 10s, 30s, 1m).
- Permite **limpiar el historial** con un botón.
- Footer con **año dinámico**.

## Endpoint monitoreado

Por defecto el monitor consulta:

- `https://servicios.corporacioncaest.com/caest/global/v1/health/oracle`

> Si necesitás cambiarlo, editá la constante `URL` en el `<script>`.

## Cómo usar (local)

1. Cloná el repo o descargá el archivo.
2. Asegurate de tener un archivo `index.html`.
3. Abrilo en el navegador (doble click) o servilo con un servidor local.

Opcional (servidor local rápido con Python):

---

## 🔒 Autor
**Desarrollado por:**  
Nelson Gamboa García  
Ingeniero en Sistemas – [@nelgamb](https://github.com/nelgamb)

---

### 📆 Fecha de implementación
**08 de Enero del 2026**
