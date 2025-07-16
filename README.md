# Demo de Checkout Embebido de Clip

Este proyecto es una demostración de cómo integrar el **Checkout Embebido de Clip** directamente en una página HTML. Permite mostrar una membresía o producto digital y realizar el pago sin redireccionar al usuario a otro sitio.

## ¿Qué incluye este demo?

- Página web responsiva con diseño limpio.
- Producto: Membresía Premium anual.
- Botón de pago usando el SDK de Checkout Embebido de Clip.
- Estilos modernos con HTML y CSS puro.
- Ideal como base para suscripciones, membresías o ventas digitales.

## 💳 Integración con Clip Checkout Embebido

Este demo utiliza el SDK oficial de Clip, cargado desde:

```html
<script 
  id="checkoutClipPlugin" 
  payment_request_id="feca4174-e784-436e-8e8a-e334121f44d7" 
  type="module" 
  src="https://sdk.clip.mx/js/v1/checkout.js">
</script>
```

### ¿Qué es `payment_request_id`?

Es el identificador de una solicitud de pago generada previamente desde tu backend (API REST) o desde el dashboard de Clip. Este ID vincula el botón con el pago que el usuario realizará.

---

## 📄 Estructura del Proyecto

- `index.html`: Contiene todo el código de frontend, incluyendo el botón Clip.
- `README.md`: Documentación completa del proyecto.

---

## Instrucciones de uso

1. Clona este repositorio o descarga el `.zip`.
2. Abre `index.html` en tu navegador para ver el demo.
3. Sustituye el `payment_request_id` por uno válido de tu cuenta Clip.
4. Sube a tu servidor o usa GitHub Pages para publicarlo.

---

## Publicar con GitHub Pages (opcional)

1. Sube los archivos a un repositorio nuevo.
2. Entra a **Settings > Pages**.
3. Selecciona rama `main` y ruta `/ (root)`.
4. Tu demo estará disponible en:

```
https://TU_USUARIO.github.io/TU_REPOSITORIO/
```

---

## Advertencia

Este demo utiliza una cuenta de prueba y los pagos son rechazados automáticamente. No se entregará ningún producto.

---

## Autor

Basado en la documentación oficial de Clip.

---

## Recursos útiles

- [Clip Developer Portal](https://developer.clip.mx)
- [Checkout Embebido - Guía oficial](https://developer.clip.mx/reference/integrar-checkout)

---

## Licencia

Este proyecto es libre para uso educativo, con fines demostrativos o pruebas internas.
