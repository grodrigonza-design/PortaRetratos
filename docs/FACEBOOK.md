# Conectar las fotos de Facebook

La tablet descarga cada hora las fotos que **una persona** sube a su Facebook. La conexión se hace con un código, igual que en los televisores inteligentes: la persona nunca escribe su contraseña en la tablet.

*English summary at the end.*

## Antes de empezar

- La configuración la hace **una persona con computadora** (usted), una sola vez. Toma unos 15 minutos.
- Facebook solo deja leer fotos a apps revisadas por Meta. Por eso **cada quien crea su propia app** y la deja en **modo desarrollo**: así funciona sin revisión para las personas que usted agregue (hasta 50).
- El permiso dura **unos 60 días**. Una semana antes de que venza, la tablet muestra un código nuevo y la persona solo lo vuelve a escribir.

## 1. Crear la app en Meta

1. En una computadora, entre a **[developers.facebook.com](https://developers.facebook.com)** con **su** Facebook → **Comenzar**. La primera vez pide registrarse como desarrollador y a veces verificar el teléfono.
2. **Mis apps → Crear app.**
   - Nombre: *PortaRetratos* (o el que quiera).
   - Caso de uso: **"Autenticar y solicitar datos a usuarios con el inicio de sesión con Facebook"**.
   - Si pregunta por un portfolio comercial: **"Todavía no quiero conectar un portfolio"**.
   - Siguiente → Crear app.

## 2. Activar el inicio de sesión con código y el permiso de fotos

Dentro de la app: **Casos de uso → "Autenticar y solicitar datos…" → Personalizar**.

1. **Configurar:** busque **"Inicio de sesión desde dispositivos"** (*Login from Devices*) → **Sí** → **Guardar cambios**. Todo lo demás de esa pantalla déjelo como está: no hace falta llenar URIs ni dominios.
2. **Permisos y funciones:** busque **`user_photos`** → **Agregar**.

**No publique la app.** Debe quedar en **modo desarrollo**.

## 3. Copiar los dos datos

- **Configuración de la app → Básica → Identificador de la app** (App ID: solo números).
- **Configuración de la app → Avanzada → Seguridad → Token de cliente** (Client Token).

En la página del portarretratos (en el celular): pestaña **Facebook** → péguelos → **Guardar**.

> Si en "Básica" pide política de privacidad o ícono, ignórelo: solo hace falta para publicar.

## 4. Agregar a la persona como Evaluador

Usted, como administrador, ya puede conectarse; sirve para probar. Para la cuenta de otra persona:

1. **Roles de la app → Roles → Agregar personas → Evaluadores** → escriba su usuario de Facebook o su número de perfil → Agregar.
   - Para saberlo: en su perfil de Facebook → ⋯ → **Copiar enlace del perfil** (`facebook.com/usuario` o `profile.php?id=NÚMERO`).
2. La persona, **desde el navegador** de su celular (no desde la app de Facebook), entra a **[developers.facebook.com/requests](https://developers.facebook.com/requests)** y **acepta**. Si le pide registrarse como desarrolladora, acepte: es un trámite de una vez.
3. **Si le dice "No tienes solicitudes pendientes":** suele pasar cuando la invitación se envió antes de que ella terminara de registrarse. Quite la invitación (🗑) y vuelva a agregarla; después recargue la página de solicitudes.
4. En Roles, su estado deja de decir **"Pendiente"**.

Si al poner el código sale **"La app no está activa"**, es porque falta este paso.

## 5. Conectar

1. Pestaña **Facebook → Conectar / renovar.** Aparece un código en el celular y en la pantalla de la tablet. Vence en ~7 minutos; si vence, saque otro.
2. **En el celular de la persona:** abra **facebook.com/device**, escriba el código y acepte.
3. En 1 o 2 minutos dirá **"✔ Conectado como …"** y empezarán a llegar sus fotos.

Si antes estaba conectada otra cuenta, sus fotos se borran solas de la tablet.

## Consejos

- **Solo las fotos "buenas":** si la persona comparte memes o imágenes con frases, cree en Facebook un álbum (por ejemplo "Portarretratos") y escriba ese nombre en **Álbum**. Solo saldrán las fotos de ese álbum.
- **Quitar una foto:** desde la pestaña **Fotos** con ✕. No vuelve a descargarse.
- **"Buscar fotos ahora":** no espera la revisión de cada hora.
- **Si la persona quita el permiso** desde Facebook, la tablet lo detecta y vuelve a mostrar el código.

## Limitaciones

- Meta cambia sus reglas seguido; algo de esto podría dejar de funcionar.
- Solo trae fotos **subidas por la persona**, no aquellas en las que la etiquetaron.
- Las fotos se descargan del tamaño adecuado para la pantalla, no en máxima resolución.

---

## English summary

1. At developers.facebook.com create an app with the use case *"Authenticate and request data from users with Facebook Login"*. Keep it in **Development mode**.
2. Use case → Customize → **Settings:** enable **Login from Devices**. **Permissions:** add **`user_photos`**.
3. Copy the **App ID** (Settings → Basic) and **Client Token** (Settings → Advanced → Security) into the **Facebook** tab of the frame's web page.
4. App Roles → add the person as **Tester**; they accept at developers.facebook.com/requests (from a browser).
5. Press **Connect**: the person enters the code shown on the tablet at **facebook.com/device**. Access lasts ~60 days; the tablet shows a new code a week before it expires.
