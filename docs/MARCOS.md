# Cómo hacer los marcos con ChatGPT (u otra IA)

## Reglas (lo importante)

1. **Horizontal.** Pida formato horizontal panorámico (16:9). Si ChatGPT no puede, el
   horizontal normal (3:2, 1536×1024) también sirve: la app lo ajusta a la pantalla.
2. **Centro verde puro.** El hueco del centro debe ser un rectángulo de **verde puro
   (#00FF00), plano**, sin sombras ni texturas. La app lo vuelve transparente sola.
   (No pida "fondo transparente": ChatGPT a veces dibuja cuadritos grises falsos.)
3. **Hueco grande.** El borde decorativo debe ocupar solo un 8–12 % de cada lado,
   para que el hueco sea grande y las fotos se vean bien.
4. **Sin letras.** ChatGPT se equivoca escribiendo en español y el texto taparía las
   fotos. La app escribe el mensaje ("¡Feliz cumpleaños, Ana!", "¡Feliz Navidad!").
5. **Guárdelo como PNG** con el nombre exacto de la tabla (ej. `navidad.png`) y súbalo
   desde la pestaña **Marcos** de la página del celular.

## Prompt base

Copie esto y cambie solo la parte de **[TEMA]**:

> Crea un marco decorativo para un portarretratos digital, formato horizontal
> panorámico 16:9. El centro debe ser un rectángulo grande con esquinas redondeadas,
> relleno de color verde puro #00FF00, totalmente plano, sin sombras, sin degradados
> y sin nada encima. El borde decorativo ocupa solo los bordes de la imagen (alrededor
> del 10 % de cada lado) y no invade el rectángulo verde. Tema del borde: **[TEMA]**.
> Estilo ilustrado, alegre, colores vivos, alta calidad. No incluyas ningún texto,
> letras ni números.

Para que todos combinen, hágalos en la misma conversación y después del primero diga:
*"Ahora otro con el mismo estilo y las mismas medidas, tema: [TEMA]"*.

Si el centro no sale verde liso (sale con dibujos encima o con sombra), pida:
*"El rectángulo central debe ser verde #00FF00 completamente liso, sin nada encima."*

## Lista de marcos (≈ 33)

### Cumpleaños (la app agrega el nombre)
| Archivo | [TEMA] |
|---|---|
| `cumple.png` ✅ incluido | globos, confeti y un pastel de cumpleaños, colores de fiesta |
| `cumple-abuelos.png` | cumpleaños elegante y cálido: rosas y flores en tonos crema, dorado y vino, velas, encaje |
| `cumple-tios.png` | fiesta para adultos: globos metálicos, confeti, serpentinas, tonos turquesa, fucsia y dorado |
| `cumple-primos.png` / `cumple-nino.png` | fiesta infantil: globos de colores, piñata, dulces, estrellas, regalos |

Para usar un marco de grupo con alguien: `cumple 03/05 = Abuela | cumple-abuelos`.
Si ese marco no existe todavía, se usa `cumple.png`.

### Fechas especiales
| Archivo | Fecha | [TEMA] |
|---|---|---|
| `anio-nuevo.png` | 1 ene | fuegos artificiales dorados, copas de champán, serpentinas |
| `san-valentin.png` | 14 feb | corazones rojos y rosados, rosas, sobres de amor |
| `semana-santa.png` | Semana Santa | palmas, lirios blancos, tonos morado y dorado, ambiente sereno |
| `juan-santamaria.png` | 11 abr | colores de la bandera de Costa Rica, antorcha encendida, laureles |
| `dia-trabajador.png` | 1 may | herramientas, granos de café, campo costarricense |
| `dia-padre.png` ✅ incluido | 3er domingo jun | corbatas, herramientas, tonos azules |
| `guanacaste.png` | 25 jul | árbol de guanacaste, sabana, carreta típica, sombrero de sabanero |
| `virgen-angeles.png` | 2 ago | flores blancas y celestes, angelitos, velas, tonos dorados |
| `dia-madre.png` ✅ incluido | 15 ago | rosas y flores en tonos pastel, corazones suaves |
| `persona-negra.png` | 31 ago | cultura afrocaribeña de Limón: palmeras, tambores, patrones coloridos |
| `dia-nino.png` | 9 sep | juguetes, globos, cometas, colores primarios |
| `independencia.png` | 15 sep | faroles de colores, bandera de Costa Rica, antorcha de la independencia |
| `halloween.png` ✅ incluido | 31 oct | calabazas sonrientes, murciélagos, dulces, estilo infantil no aterrador |
| `abolicion-ejercito.png` | 1 dic | palomas de la paz, ramas de olivo, bandera de Costa Rica |
| `navidad.png` ✅ incluido | 24–25 dic y todo diciembre | pinos, flor de pascua, luces y regalos |
| `navidad2.png` | se turna con navidad | pesebre sencillo, estrellas, velas, tonos dorados |
| `fin-de-anio.png` | 31 dic | reloj a medianoche, fuegos artificiales, uvas, serpentinas |

### Temporada
| Archivo | Cuándo | [TEMA] |
|---|---|---|
| `mes-patrio.png` | 1–15 sep | faroles, banderitas de Costa Rica, flores azul, blanco y rojo |

### Un marco por mes
| Archivo | [TEMA] |
|---|---|
| `enero.png` ✅ incluido | verano: playa, sol, palmeras, conchas |
| `febrero.png` | flores rosadas y corazones suaves |
| `marzo.png` | árboles de cortez amarillo en flor, cielo azul |
| `abril.png` | mangos, frutas tropicales, mariposas |
| `mayo.png` | inicio de las lluvias: hojas verdes, gotas, ranitas |
| `junio.png` | selva verde, helechos, colibríes |
| `julio.png` | tucanes, guacamayas, flores tropicales |
| `agosto.png` | orquídeas, flores suaves |
| `septiembre.png` | lluvia, paraguas de colores, arcoíris |
| `octubre.png` | perezosos, ranas de colores, selva |
| `noviembre.png` | viento y cometas (papalotes) en el cielo, hojas |
| (diciembre usa `navidad`) | |

### Por defecto (si no hay nada más)
| Archivo | [TEMA] |
|---|---|
| `normal.png` | marco de madera clásico y elegante |
| `normal2.png` | flores tropicales y hojas |

## Variantes
Puede agregar más marcos del mismo tema numerándolos: `enero2.png`, `navidad3.png`…
La app los va turnando foto por foto.

## ¿Cómo los subo?
Desde la página del portarretratos en el celular: pestaña **Marcos** → escriba el nombre (ej. `navidad`) → **Elegir imagen**.
No hace falta recortarlos: la app los ajusta a la pantalla, vuelve transparente el verde y acomoda el mensaje para no tapar los adornos.

## Marcos incluidos
`cumple`, `navidad`, `halloween`, `enero` (verano/playa), `dia-madre`, `dia-padre`.
