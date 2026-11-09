# Packs De Tiza: propuesta v3 (página de puertas)
Datos de la web consultados el 09/11/2026. Etiquetas: **[verificado]** está en la web · **[propuesta]** idea nuestra · **[pendiente]** falta confirmarlo.

## a) Qué está bien del PDF de ChatGPT
- Composición mínima por proyecto, herramientas en un solo bloque, un único «Añadir todo al carrito» y el configurador en segundo plano.
- Los precios de las 6 herramientas (21,78 €) **[verificado]**.
- Pide no inventar rendimientos ni ahorros y no prometer «todo incluido».
- Para WooCommerce, guardar pack, tamaño y origen (compra rápida o configurador).

## b) Qué mejoraría
- El mínimo de puertas (Primer 250 + Essential 750) coincide con el configurador: 37,40 € **[verificado]**. Los mínimos de muebles (Essential 250) y de cocinas (1 bote) no coinciden: la web usa 1 bote y 2 botes **[pendiente: confirmar con Gema]**.
- Los demás mínimos (Matte Wall, Strong, masilla) no tienen precio ni producto comprobados **[pendiente]**.
- «Problemas del configurador» y «la mejora tras agosto» no traen datos que los respalden **[pendiente]**.

## c) Qué eliminaría (inventado en las imágenes)
- Los precios 32,90 €, 89,90 € y 169,90 €, el total de 38,80 € y el de 111,25 € «con herramientas» puesto con 1 puerta. Los reales son 37,40 €, 111,25 € y 185,10 €.
- El acabado «Brillo suave»: en la web solo hay mate y satinado.
- Los logos «De Tiza®» y «Pintura a la tiza» y los botes dibujados.
- Las promesas «pintura profesional» y «productos compatibles y probados».

## Cambios en la maqueta v3 **[propuesta]**
- Decisión de Talega sobre las herramientas: las 6 se muestran como lista informativa con un solo botón, «Añadir todas las herramientas (+21,78 €)», que se puede quitar. Para elegirlas sueltas está «Crea tu propio pack», que lleva al configurador. Las casillas y «Seleccionar todas» se eliminan.
- Dibujo de puertas en cada tamaño.
- Bajo el total, botón «¿Dudas? Pregunta a nuestro asistente» al chat de la web, sin enlace directo a WhatsApp, y bloque de confianza con datos reales.
- Portada más baja en ordenador, para ver el selector sin bajar.

## d) Para que compre sin dudas
1. Primero el antes y después real y una sola pregunta: «¿cuántas puertas?».
2. Lo que incluye, con los envases reales y su precio.
3. El color elegido en el bote; mate y satinado cuestan igual **[verificado]**.
4. Herramientas en un solo botón (+21,78 € **[verificado]**). Si quiere elegirlas sueltas, usa el configurador **[propuesta]**.
5. El total siempre visible y el envío gratis desde 30 € **[verificado]**.
6. La ayuda a mano: «¿Dudas? Pregunta a nuestro asistente», que abre el chat de la web (Oct8ne, «Chat IA DeTiza») y decide si deriva a WhatsApp **[propuesta]**. Además, muestras y devoluciones en 60 días **[verificado]**.

## e) Registrar el pack en WooCommerce, sin plugins de pago
El plugin propio ya añade los packs al carrito (`detiza_puertas_add_pack_to_cart`) **[verificado]**. Juanjo **[propuesta]**:
1. Envía junto al pack su nombre, tamaño, color y origen.
2. Lo guarda en cada producto del carrito (`woocommerce_add_cart_item_data`).
3. Lo copia al pedido (`woocommerce_checkout_create_order_line_item`). Así se ve, se filtra y se exporta.

Falta saber si el plugin ya lo guarda **[pendiente]**.

## f) Pendientes
- Superficie de pintura por puerta y rendimiento del Primer.
- Contradicción entre la ayuda (1, 2 y 3 botes) y el configurador (3, 5 y 9).
- Nombres de los packs, los 6 colores y si hay descuento.
- Packs de azulejos, suelos y encimeras.
- Color de la puerta de Talega.

## Variante de color (pack-puertas-v3-color.html) **[propuesta]**
- La franja de la foto y del selector toma un tono suave del color elegido. Las muestras son redondas, como la tapa de un bote vista desde arriba, con el nombre real debajo.
- Los bloques alternan blanco, crema, salvia y rosa empolvado.
- Los colores son **aproximados**: la web no publica códigos de color, así que los he sacado de la tarjeta pintada de cada foto de producto. Pergamino #E7DCC8, Wevet #FBF6F7, Lino #E5D8C7, Salón de Té #F4EAE1, Verde Oxford #6F7358 y Azul Antiguo #BACCD1. Salvia: tinte de Verde Macilla (#C6C3B4). Rosa: tinte de Rosa Nude (#F6DAD6). Faltan los códigos oficiales **[pendiente]**.

## Ajuste 9-nov · Selector de color por tonalidades (versión con tonos)
- Arriba, los 6 favoritos para puertas (botes grandes): Blanco Pergamino, Blanco Wevet, Lino, Salón de Té, Verde Oxford y Azul Antiguo.
- Debajo, una galería con todas las fotos de la ficha del color elegido. Fotos sacadas de las fichas y del configurador de la web: Pergamino 2, Wevet 1, Lino 3 (foto de ficha y 2 portadas de vídeo), Salón de Té 1, Verde Oxford 3, Azul Antiguo 3.
- «Toda la carta Essential»: pestañas con las 10 tonalidades reales de la web, en su orden (Blanco 8, Gris 10, Beige 8, Marrón 4, Amarillo 5, Verde 19, Azul 19, Rosa y Malva 17, Rojo y Naranja 13, Negro 3). Hay 90 colores en total. Un color puede aparecer en varias tonalidades, igual que en la web (Lino sale en Beige, Blanco y Gris).
- Cada color de la carta tiene nombre y una muestra pequeña. Al elegirlo se ve su foto principal de la ficha. Los favoritos llevan ★.
- La muestra pequeña es aproximada: el color se ha sacado de la foto de cada color, no de un código oficial. **[pendiente]** Si De Tiza tiene los códigos HEX, se cambian.
