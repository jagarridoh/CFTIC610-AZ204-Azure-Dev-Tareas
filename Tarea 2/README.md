1. **Nombres y apellidos:** Justo Antonio Garrido Herrador

2. **Fecha:** entrega 18-1-2021

3. **Laboratorios / Demos**: 
   - **Demo Módulo 6**: Instrucciones: están en el MOC.
   - **Laboratorio Módulo 6**: Fichero de Instrucciones: Instructions\Labs\AZ-204_06_lab.md.
   - **Demo Módulo 7**: Instrucciones: están en el MOC. Esta demo la realicé, pero no conservo capturas ni los recursos generados en Azure. Tampoco se generó ningún proyecto en local.
   - **Laboratorio Módulo 7**: Fichero de Instrucciones: Instructions\Labs\AZ-204_07_lab_ak.md.
   - **Laboratorio Módulo 8**: Fichero de Instrucciones: Instructions\Labs\AZ-204_08_lab_ak.md.
   
4. **Resumen de los Ejercicios:**
* **Objetivos Demo/Lab 06**: 
     * Registrar una nueva aplicación en Azure Active Directory. 
     * Autenticación interactiva mediante MSAL.NET: creación de proyecto .NET Core de consola que se autentica contra Azure, utiliza Microsoft.Identity.Client, guardando Client Id y Tenant Id, utiliza PublicClientApplicationBuilder y AcquireTokenInteractive para autenticación. Autenticación en local desde navegador abierto por el proyecto de consola, otorgar permisos a la aplicación para acceder a Azure en nombre del usuario, que obtiene el Token.
     * Recuperación información de perfil mediante Microsoft Graph SDK: modificación del proyecto local .NET Core de consola: uso de Microsoft.Graph y Microsoft.Graph.Auth, llamada desde GraphServiceClient a Azure para obtener información del perfil del usuario.
* **Pasos Demo/Lab 06**:  Configuración Azure y desarrollo local .NET Core. 
* **Objetivos Demo/Lab 07**: 
     * Crear Key Vault y de un secreto (password).
     * Crear Storage Account para ser accedida mediante Connection String.
     * Crear Azure Key Vault, política de acceso a Key Vault, dando permiso GET.
     * Crear Azure Function App, con identidad asignada por sistema, creando secreto que será la Connection String anterior. Este secreto será identificado/accedido por URL. Crear configuración para almacenar la URL anterior.
     * Creación de proyecto en local de tipo Functions project, crear función activada por HTTP, creación de C# de la función con método Run con atributo [HttpTrigger("GET")], atributo [FunctionName(...)], recuperación de configuración (creada arriba). Build y Start de la función en local y test en local mediante comando CLI: httprepl, instalación y utilización de este comando (es tipo CLI), verificación del acceso GET realizado por httprepl en local.
     * Despliegue de la función a Azure. Test de la función mediante la utilidad de Azure "Developer" > Code + Test".
     * Creación de datos JSON en contenedor Blob privado. Acceso desde la Function App: añadir NuGet Azure.Storage.Blobs, uso de BlobClient, FileStreamResult, DownloadAsync, redespliegue en Azure Functions. Test en Azure: Developer, Code + Test.
* **Pasos Demo/Lab 07**:  Configuración Azure y desarrollo local .NET Core. 
* **Objetivos Lab 08**: 
     * En Azure: crear Web App, contenedor Docker a partir de imagen predefinida en Docker Hub.
     * Crear API proxy tier mediante Azure API Management. Definirle nueva API. Creación de operaciones contra el conedor Docker. Añadido de cabecera HTTP en respuesta. 
* **Pasos Lab 08**:  Configuración y pruebas Azure. 
* **Objetivos Lab 09**: 
     * Creación de recurso Azure: API Management (respetando características para que se cree rapidamente), guardado de ficheros JSON en un storage account.
     * Utilización de Logic Apps y creación de su workflow en Logic Apps Designer, crear trigger (petición HTTP GET), crear acción de listado de ficheros en Azure Storage, crear acción de tratar lista de items (el listado de ficheros), crear el último paso de acción de respuesta HTTP.
     * Uso del API Management como proxy para acceder a la Logic App. Utilizar este API Management para testear la Logic App.
* **Pasos Lab 09**:  Configuraciones y pruebas Azure. 
* **Objetivos Lab 10**: 
     * Revisar registro de proveedores.
     * Crear Event Grid Topic, despliegue de Azure Event Grid hacia web app (en Docker usando contenedor de ejemplo de Microsoft Learning). Crear Event Grid Subscription, subscripcion web hook, credenciales.
     * Publicar eventos desde proyecto local .NET usando Microsoft.Azure.EventGrid, conectandose a Event Grid, con eventos de registro de personas.
     * Ejecución y ver efecto del Event Grid y como aparecen en la web de destino.
* **Pasos Lab 10**: Configuraciones y pruebas Azure. Proyecto C# local.

5. **Dificultad o problemas presentados y como se resolvieron:** 
   * Los que vimos en clase.
   * Dificultad para utilizar la subscripción caducada y la nueva. Fue debido a no haber realizado "az login" en powershell. Una vez realizado el login, el parámentro "--subscription [nuevaSubsc]" en las órdenes az  fue reconocido y funcionó bien. (Sin descartar que algún cierre de sesión en navegador también hubiera ayudado). 
   * Instalar httprepl (https://www.nuget.org/packages/Microsoft.dotnet-httprepl).
* En Lab 6: No encontré Authentication / Default client type. Interpreté que en su lugar había que utilizar "Allow public client flows".
  
6. **Detalles de la entrega**: 
* **Evidencias capturas de pantalla en carpetas**: *** Capturas**. ( ruta: ...\\CFTIC610-AZ204-Azure-Dev-Tareas\Tarea 2\\* Capturas).
* **Proyectos modificados** : ver carpetas "*** Proyectos**". ( ruta: ...\CFTIC610-AZ204-Azure-Dev-Tareas\Tarea 2\\* Proyectos).

