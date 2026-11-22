# Comprar VPS: ¿cuánto cuesta al mes, qué plan necesitas y cuánto sube al renovar? (tabla de planes y comparativa de contratos)

Hay tres cifras que deciden una compra de VPS y casi nunca están en la primera pantalla: el precio de renovación, el plazo mínimo de contrato y el límite real de tráfico. Con esos tres datos se descartan la mayoría de las compras malas antes de pagar.

En AVA Hosting el VPS más barato con stock disponible cuesta **5 €/mes** (1 vCPU, 2 GB de RAM, 25 GB NVMe, tráfico ilimitado) y el salto a 4 GB son **10 €/mes**. Los dos son precios mensuales y la ficha no publica permanencia mínima. Abajo tienes los siete planes con su configuración exacta, qué cambia entre uno y otro, y una comparativa de contratos con IONOS, OVHcloud, Locaweb y Hostinger usando precios que esas webs muestran públicamente.

> **Selección rápida**
> Para una web, una API pequeña, un panel de automatización o un entorno de pruebas, el plan que cubre a la mayoría es **VPS One: 5 €/mes, 1 vCPU, 2 GB de RAM y 25 GB NVMe**, con backup semanal, protección DDoS y acceso root. Si vas a meter base de datos, tienda o varios contenedores, sube a **VPS Basic: 10 €/mes, 2 vCPU, 4 GB y 50 GB NVMe**.
>
> 👉 [Ver los planes VPS de AVA Hosting y sus precios actuales](https://my.ava.hosting/aff.php?aff=15562)

## Los siete planes VPS de AVA Hosting, con precio y ciclo de facturación

Todos comparten procesador Intel Xeon E5, disco NVMe, protección DDoS, root completo, panel de control, SLA de 99,9% y soporte 24/7. Lo que cambia es CPU, RAM, disco y velocidad de puerto. Los importes aparecen en la tienda como "starting from", así que el total del checkout puede subir si añades opciones.

| Plan | vCPU · RAM · disco | Precio | Facturación | Enlace |
| --- | --- | --- | --- | --- |
| VPS Nano | 1 vCPU · 512 MB · 20 GB NVMe | 11 € | Anual | [ Ver precio](https://my.ava.hosting/aff.php?aff=15562) |
| VPS One | 1 vCPU · 2 GB · 25 GB NVMe | 5 €/mes | Mensual | [ Ver precio](https://my.ava.hosting/aff.php?aff=15562) |
| VPS Basic | 2 vCPU · 4 GB · 50 GB NVMe | 10 €/mes | Mensual | [ Ver precio](https://my.ava.hosting/aff.php?aff=15562) |
| VPS Lucky ✪ | 2 vCPU · 6 GB · 70 GB NVMe | 15 €/mes | Mensual | [ Ver precio](https://my.ava.hosting/aff.php?aff=15562) |
| VPS Power ☆ | 4 vCPU · 8 GB · 90 GB NVMe | 20 €/mes | Mensual | [ Ver precio](https://my.ava.hosting/aff.php?aff=15562) |
| VPS Extra ☆ | 6 vCPU · 12 GB · 120 GB NVMe | 30 €/mes | Mensual | [ Ver precio](https://my.ava.hosting/aff.php?aff=15562) |
| VPS Ultra ☆ | 8 vCPU · 16 GB · 160 GB NVMe | 40 €/mes | Mensual | [ Ver precio](https://my.ava.hosting/aff.php?aff=15562) |

El VPS Nano es la excepción en todo: se factura al año, su puerto es de 100 Mbps en lugar de 1 Gbps, tiene el **puerto 25 cerrado** (no podrás enviar correo desde él) y hoy aparece como agotado, con 0 unidades disponibles. El resto son mensuales y con puerto de 1 Gbps.

## Qué dicen los números de la lista

El precio sube en línea recta con la RAM: 2,5 € por cada GB en todos los tramos. Son 5 € por 2 GB, 10 € por 4 GB, 15 € por 6 GB, 20 € por 8 GB, 30 € por 12 GB y 40 € por 16 GB. No hay descuento por volumen ni tramo que salga más barato por GB, y eso tiene una consecuencia práctica: **comprar el plan grande "por si acaso" no te ahorra nada**. Empieza por el que cubre tu uso de hoy y sube después.

El disco se comporta al contrario. La relación entre gigas de almacenamiento y euro baja según subes de plan: 5 GB por euro en VPS One, 4,5 en VPS Power y 4 en VPS Ultra. Si tu cuello de botella es el espacio y no la memoria, los planes pequeños rinden más por euro.

VPS Lucky rompe la progresión de núcleos: mantiene los 2 vCPU del Basic y añade 2 GB de RAM y 20 GB de disco por 5 € más. Para cargas que tiran de memoria antes que de procesador (Postgres, Java, Node con varios procesos), es el tramo con mejor relación de la lista.

VPS Nano solo tiene sentido para un servicio mínimo: un DNS autoritativo, una VPN personal, un monitor de disponibilidad. Menos de 1 €/mes con 512 MB de RAM es difícil de igualar, siempre que no necesites enviar correo ni más de 100 Mbps.

## Antes de comprar un VPS: el precio de renovación

La ficha de AVA Hosting no publica el precio de renovación, igual que no publica la ubicación del centro de datos ni el plazo mínimo. Pregunta las tres cosas por el chat de soporte antes de pagar; son cinco minutos y evitan la sorpresa del segundo año.

El patrón contrario, el de las webs que sí lo publican, sirve para ver cuánto puede doler. Locaweb (Brasil, precios en reales) vende su VPS de 4 GB a 32,90 R$/mes contratando 24 meses y lo renueva a **63,92 R$/mes**, prácticamente el doble; el de 1 GB pasa de 15,90 a 23,92 R$/mes. Hostinger, también en reales y en el mercado brasileño, anuncia el primer tramo por 719,76 R$ los 24 meses (unos 29,99 R$/mes) y una renovación de **59,99 R$/mes**.

Trasládalo a euros: un plan de 5 €/mes que renueve a 9 €/mes cuesta 60 € el primer año y 108 € el segundo. Dos años de ese VPS salen más caros que dos años de uno de 7 €/mes sin subida.

👉 [Comprobar el precio y las condiciones actuales de AVA Hosting](https://my.ava.hosting/aff.php?aff=15562)

## Plazo mínimo y cómo se sale del contrato

IONOS ofrece dos opciones: contrato de 1 mes, cancelable mes a mes, o de 12 meses, que no se puede dejar antes de cumplir el año y luego pasa a mensual. Locaweb y Hostinger condicionan sus precios bajos a un pago único de 24 meses por adelantado. En OVHcloud puedes subir de plan con un clic, pero solo dentro del mismo centro de datos; bajar de plan exige contratar el nuevo, migrar los datos y dar de baja el anterior.

AVA factura mes a mes en todos los planes menos el Nano, que es anual. La ficha no indica permanencia, así que confirma que el plan mensual se cancela a final de mes sin penalización.

## "Tráfico ilimitado" no significa lo mismo en todas partes

IONOS anuncia tráfico ilimitado con un ancho de banda de hasta 1 Gbit/s. AVA Hosting también marca tráfico ilimitado y puerto de 1 Gbps (100 Mbps en el Nano), sin cuota mensual a la vista. OVHcloud, en cambio, aplica cuotas explícitas en su región Asia-Pacífico: 500 GB al mes para VPS-1, 1 TB para VPS-2 y VPS-3, 3 TB para VPS-4, y a partir de ahí la banda cae a 10 Mbps.

Cuando un proveedor escribe "ilimitado", mira la velocidad del puerto y pregunta si hay cláusula de uso razonable. Un puerto de 100 Mbps sostenido mueve unos 32 TB al mes; uno de 1 Gbps, diez veces más. Ese número es el que de verdad limita.

## Panel, IP y copias de seguridad: la factura paralela

AVA incluye panel de control y backup semanal sin coste adicional según la ficha, aunque no especifica qué panel ni cuántas direcciones IPv4 trae cada plan. Si tu proyecto depende de Plesk o cPanel, confírmalo antes de pagar: la insignia "Control Panel" no dice cuál.

La diferencia de frecuencia de copias importa. Un backup semanal puede hacerte perder hasta siete días de pedidos, comentarios o registros. OVHcloud incluye copia automática diaria en su gama nueva, y esa es la referencia que deberías exigir si vas a montar una tienda.

En IONOS, el panel se paga aparte: Plesk Obsidian cuesta **5 €/mes (IVA excl.)** desde el 1 de octubre en todos los VPS, y exige un mínimo de 20 GB de disco en Linux y 32 GB en Windows, así que su VPS Linux XS no lo admite. Una IPv4 adicional son 5 € al mes, y el backup en la nube de Acronis arranca en 0,05 €/GB/mes. En las Local Zone de OVHcloud directamente no hay Windows, Plesk, cPanel ni Docker, y tampoco IP adicional ni Load Balancer.

👉 [Ver qué incluye cada plan VPS de AVA Hosting](https://my.ava.hosting/aff.php?aff=15562)

## Dónde está el servidor (y por qué importa si facturas en la UE)

La página de precios de AVA no indica la ubicación del centro de datos, y es un dato que cambia la decisión si manejas datos personales de clientes europeos o si tu público está en España y la latencia te importa.

Como referencia: IONOS permite elegir centro de datos en España, Alemania, Reino Unido o Estados Unidos, con certificación ISO 27001 y posibilidad de firmar un contrato de encargado del tratamiento conforme al RGPD. OVHcloud sostiene que un VPS alojado en Italia o en otro país de la UE queda fuera del ámbito del CLOUD Act estadounidense. Si necesitas residencia de datos en Europa, pide por escrito el país del centro de datos antes de contratar.

## Comparativa de contratos

| Proveedor | Moneda y mercado | Plazo mínimo | A favor (verificado) | A vigilar (verificado) |
| --- | --- | --- | --- | --- |
| AVA Hosting | EUR | Mensual (Nano anual) | Backup semanal, DDoS y panel incluidos; SLA 99,9%; puerto 1 Gbps | No publica ubicación ni renovación; Nano agotado y con puerto 25 cerrado |
| IONOS | EUR, España | 1 o 12 meses | Centro de datos en España, 99,99%, tráfico ilimitado hasta 1 Gbit/s, contrato RGPD | Plesk 5 €/mes (IVA excl.) y mínimo de 20 GB; IPv4 extra 5 €; backup 0,05 €/GB/mes |
| OVHcloud | EUR, UE | No indicado | Backup automático diario incluido, NVMe, subida de plan en un clic | En Local Zone no hay Windows, Plesk, cPanel ni Docker; sin IP adicional ni Load Balancer |
| Locaweb | BRL, Brasil | 24 meses | Precios con impuestos incluidos, IP propia, una snapshot gratis | Renovación cerca del doble del precio promocional |
| Hostinger | BRL, Brasil | 24 meses | KVM, Docker, firewall, cPanel/Plesk/CyberPanel/DirectAdmin | El precio bajo exige pago de 24 meses; la renovación se publica aparte |

Las columnas de moneda no se pueden mezclar: los reales brasileños responden a otro mercado y a otra carga fiscal.

## Preguntas que aparecen justo antes de pagar

### ¿Los 5 €/mes se mantienen al renovar?

La ficha de AVA no lo dice. Pídelo por el chat y guarda la respuesta. Si no hay compromiso por escrito, asume que puede subir y calcula el coste a dos años, no a uno.

### ¿Hay reembolso o prueba gratuita?

La página de VPS no publica política de devolución. Pregunta el plazo exacto antes de pagar y elige un método que te deje reclamar si algo sale mal en las primeras horas.

### ¿Puedo cambiar de plan más adelante?

AVA no lo detalla. En OVHcloud la subida es inmediata y sin migrar datos, pero solo dentro del mismo centro de datos; bajar de plan obliga a contratar otro, mover todo y dar de baja el viejo. Pregunta si en AVA el cambio de plan conserva el disco.

### ¿Cuánta RAM necesito de verdad?

2 GB bastan para una web estática, una API pequeña o un panel de automatización con pocos flujos. Con WordPress, MySQL y panel encima, apunta a 4 GB. Varios contenedores Docker, una base de datos y n8n en la misma máquina piden 8 GB o más.

## Qué plan elegir según tu caso

- Pruebas, VPN, DNS o un bot pequeño → **VPS One, 5 €/mes**. El Nano solo si vuelve el stock, no necesitas correo saliente y te conformas con 512 MB.
- Una web con WordPress, base de datos y dos o tres contenedores → **VPS Basic, 10 €/mes**.
- Postgres, Java o Node donde la memoria es el límite → **VPS Lucky, 15 €/mes**.
- Tienda online o varios proyectos en la misma máquina → **VPS Power, 20 €/mes**, y sube a Extra si el disco de 90 GB se queda corto.
- **VPS Ultra** únicamente si de verdad vas a usar 16 GB y 8 vCPU desde el primer día.

No necesita un VPS dedicado quien va a servir una web con pocas visitas, ni quien no quiere administrar un sistema operativo: en ese caso un hosting compartido o uno gestionado sale más barato en tiempo.

Como el precio escala de forma lineal, no hay premio por comprar grande de antemano. Elige el plan más pequeño que aguante tu uso de hoy y sube cuando el consumo de RAM o disco lo pida.

👉 [Empezar con el plan VPS de AVA Hosting que se ajuste a tu caso](https://my.ava.hosting/aff.php?aff=15562)

Dos comprobaciones antes de teclear la tarjeta: en qué moneda y con qué impuestos se cobra en el checkout, y cuál es el precio de renovación junto al plazo mínimo. Con eso sabes lo que pagas hoy y lo que pagarás dentro de doce meses.
