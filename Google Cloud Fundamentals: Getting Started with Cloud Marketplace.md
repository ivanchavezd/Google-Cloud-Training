EN: Google Cloud Fundamentals: Getting Started with Cloud Marketplace
ES: Conceptos básicos de Google Cloud: Cómo comenzar a usar Cloud Marketplace

Tarea 1. Accede a la consola de Google Cloud
En cada lab, recibirá un proyecto de Google Cloud y un conjunto de recursos nuevos por tiempo limitado y sin costo adicional.

Accede a Qwiklabs desde una ventana de incógnito.

Ten en cuenta el tiempo de acceso del lab (por ejemplo, 1:15:00) y asegúrate de finalizarlo en el plazo asignado.
No existe una función de pausa. Si lo necesita, puede reiniciar el lab, pero deberá hacerlo desde el comienzo.

Cuando esté listo, haga clic en Comenzar lab.

Anote las credenciales del lab (el nombre de usuario y la contraseña). Las usarás para acceder a la consola de Google Cloud.

Haga clic en Abrir Google Console.

Haga clic en Usar otra cuenta, copie las credenciales para este lab y péguelas en el mensaje emergente que aparece.
Si usa otras credenciales, se generarán errores o incurrirá en cargos.

Acepta las condiciones y omite la página de recursos de recuperación.

Nota: No hagas clic en Finalizar lab, a menos que lo hayas terminado o desees reiniciarlo. Esta acción borrará tu trabajo y quitará el proyecto.
Tarea 2. Usa Cloud Marketplace para implementar una pila LAMP
En la consola de Google Cloud, ve al menú de navegación (Ícono del menú de navegación) y haz clic en Marketplace.

En la barra de búsqueda, escribe LAMP y, luego, presiona INTRO.

En los resultados de la búsqueda, haz clic en Bitnami package for LAMP.

Si eliges otra pila LAMP, como la oferta de implementación en un clic de Google, las instrucciones del lab no funcionarán como se espera.

En la página de LAMP, haz clic en COMENZAR.

En la página Acuerdos marca la casilla de Términos y acuerdos y haz clic en ACEPTAR.

En la ventana emergente que indica que se aceptaron correctamente las condiciones, haz clic en IMPLEMENTAR.

Si es la primera vez que usas Compute Engine, deberás inicializar la API de Compute Engine para poder continuar.

En Zona, selecciona la zona de implementación en ZONE.

En Tipo de máquina, selecciona E2 como la Serie y e2-medium como el Tipo de máquina.

Deja la configuración restante con sus valores predeterminados.

Haz clic en Implementar.

Si aparece el mensaje Bienvenido a Deployment Manager, haz clic en Cerrar para descartarlo.

Nota: Es posible que aparezcan advertencias mientras se lleva a cabo la implementación. Puedes ignorarlas en este lab.
El estado de la implementación aparece en la ventana de la consola: Se está implementando lampstack-1. Una vez que se complete la implementación de la infraestructura, el estado cambiará a Se implementó lampstack-1.

Una vez que se instale el software, se mostrará un resumen de los detalles de la instancia, incluida la dirección del sitio.

Tarea 3. Verifica tu implementación
Cuando se complete el proceso de implementación, haz clic en el vínculo Dirección del sitio ubicado en el panel derecho. Si el sitio web no responde, espera 30 segundos y vuelve a intentarlo. Si ves una notificación de redireccionamiento, haz clic en ese vínculo para ver tu sitio nuevo.

También puedes hacer clic en Visit the site en la sección Comienza a usar Bitnami package for LAMP de la página. Una pestaña nueva del navegador muestra un mensaje de felicitaciones. En esta página se confirma que, como parte de la pila LAMP, se está ejecutando el servidor HTTP de Apache.

Nota: Si no puedes ver la página web en el navegador de tu laptop empresarial: Si es posible, sal de todas las VPN o redes empresariales y vuelve a intentarlo. Ingresa la dirección IP en otro dispositivo, como una tablet o incluso un teléfono.
