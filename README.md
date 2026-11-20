# París en 4 días

App web móvil para un viaje a París del sábado 28 de noviembre al martes 1 de diciembre de 2026.

- **Plan**: itinerario día a día con horas, precios, consejos y cómo llegar de una parada a la siguiente. Cada parada se marca como hecha.
- **Mapa**: mapa esquemático de París que funciona sin conexión, con las paradas de cada día y enlaces a Google Maps para la navegación paso a paso.
- **Transporte**: calculadora del billete o pase más barato, traslados desde CDG, Orly, Beauvais o estación, y cómo comprar y validar.
- **Guía**: precios y días de cierre, presupuesto, comida, frases en francés, seguridad y plan de lluvia.
- **Listas**: reservas, transporte, documentos y maleta.

## Uso

Es un único archivo, `index.html`, sin dependencias ni compilación. Ábrelo en el navegador o sírvelo con cualquier servidor estático:

```bash
python3 -m http.server 8000
```

Alojado en HTTPS (por ejemplo, GitHub Pages) se puede instalar en la pantalla de inicio del móvil y funciona sin conexión gracias a `manifest.webmanifest` y `sw.js`.

Las marcas se guardan en el propio dispositivo (`localStorage`).

## Datos

Tarifas de Île-de-France Mobilités y precios de monumentos de 2026, comprobados el 20 de noviembre de 2026. Los horarios, las obras y las huelgas cambian: conviene confirmarlos en las webs oficiales antes de salir.
