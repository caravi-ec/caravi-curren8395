# Landing page profesional — Curren 8395

Versión de diseño centrada visualmente en el nombre **CURREN** y en el modelo **8395**. Precio de venta de trabajo: **$54,99**. No muestra un precio anterior tachado porque no se ha verificado un precio histórico real.

La página es estática. No procesa pagos ni crea pedidos automáticamente en Dropi. El cliente contacta por WhatsApp y el vendedor confirma y registra el pedido en Dropi.

## 1. Añadir las fotografías

Copia las imágenes que guardaste del proveedor en la carpeta `images` y nómbralas exactamente así:

- `reloj-8395-azul.jpg`
- `reloj-8395-negro-verde.jpg`
- `reloj-8395-negro-beige.jpg`
- `reloj-8395-negro-dorado.jpg`
- `reloj-8395-plata-negro.jpg`

Si tus fotos son PNG o WEBP, puedes conservar esa extensión pero debes cambiar la ruta del archivo correspondiente en `PRODUCT.variants` en `index.html`. Asegúrate de que cada imagen corresponda al color indicado. La carpeta `images` empieza vacía porque no se han incluido las fotos de tu computadora.

## 2. Cambiar la tienda y WhatsApp

En `index.html`, busca `const PRODUCT = {` cerca del final del archivo:

- Cambia `storeName: "TU TIENDA"` por el nombre de tu tienda.
- Cambia `whatsappNumber: "593XXXXXXXXX"` por tu número real de Ecuador en formato internacional, solo dígitos y con código 593.
- El precio está configurado como `$54,99` en varios textos visibles. Si lo cambias, actualiza las instancias de ese precio para que toda la página coincida.

## 3. Qué comunica la página

- CURREN y el modelo 8395 son protagonistas visuales.
- Precio: $54,99, sin precio anterior ficticio.
- Selector de cinco colores que cambia la imagen principal.
- Botones de WhatsApp que incluyen el color seleccionado en el mensaje.
- Pago contraentrega sujeto a cobertura y condiciones del servicio.
- Consulta de costo de envío y garantía, sin prometer envío gratuito ni una garantía al cliente final hasta confirmarlo.

## 4. Uso de marca

La página usa la palabra CURREN para identificar el producto y declara que es una tienda independiente; no se presenta como sitio oficial ni como distribuidor autorizado. No añadas un logotipo oficial ni afirmes una relación comercial oficial si no cuentas con permiso o autorización. Usa fotos del proveedor que tengas permiso para publicar.

## 5. Antes de publicar

- Verifica que cada variante y fotografía sean correctas.
- Confirma stock y precio del proveedor en Dropi.
- Confirma el costo y plazo de entrega por ciudad.
- Confirma las condiciones de la garantía aplicables al comprador final.
- Confirma qué costos se aplican a pedidos rechazados/no entregados.
- Sustituye el nombre de tienda y el número de WhatsApp.
- Abre el archivo en el navegador y prueba todas las variantes y botones.

## 6. Publicar en GitHub Pages

1. Crea un repositorio de GitHub y sube `index.html` más la carpeta `images` con tus cinco fotos.
2. En `Settings → Pages`, configura `Deploy from a branch`, rama `main` y carpeta `/(root)`.
3. Abre la URL que GitHub Pages proporciona.
4. Comprueba la página en teléfono y computadora.

## 7. Números del proyecto

Con precio $54,99, proveedor $35 y envío $7, queda un margen preliminar de $12,99 antes de publicidad, devoluciones, tarifas adicionales e impuestos. Si la publicidad costara $5 por pedido entregado, quedarían $7,99 antes de los demás conceptos. Es solo un escenario de cálculo, no una ganancia garantizada.
