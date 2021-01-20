1. **Nombres y apellidos:** Justo Antonio Garrido Herrador

2. **Fecha:** entrega 19-1-2021

3. **Laboratorios / Demos**: 
   - **Demo Módulo 11**: Instrucciones: están en el MOC.
   - **Laboratorio Módulo 11**: Fichero de Instrucciones: Instructions\Labs\AZ-204_11_lab.md.
   - **Demo Módulo 12**: Instrucciones: están en el MOC. 
   - **Laboratorio Módulo 12**: Fichero de Instrucciones: Instructions\Labs\AZ-204_12_lab.md.
   - **Demo Módulo 13**: Instrucciones: están en el MOC. 
   - **Laboratorio Módulo 13**: Fichero de Instrucciones: ver: https://github.com/BillyClassTime/Monitoring-services-deployed-to-Azure.
   
4. **Resumen de los Ejercicios:**
* **Objetivos Demo/Lab 11**: 
     * Creación de Storage Account para conectarse desde proyecto de consola MessageProcessor en local. 
     * Utilización de Azure.Storage.Queues desde local hacia el Storage Account anterior. Acceso a los mensajes de la Queue: lectura de mensajes, escritura, borrado.
     * En la Demo 11 se envió y recibió mensajes de Azure Service Bus desde proyecto de consola en local. 
* **Pasos Demo/Lab 11**:  Configuración Azure y desarrollo local .NET Core. 
* **Objetivos Demo/Lab 12**:
     * Creación de instancia App Insights en Azure.
     * Creación de aplicación web en local para aplicarle Insights y telemetría.
     * Visualización de telemetría en Azure.
     * Test mediante Polly.
     * Utilización de Scale-out en aplicaciones.
* **Pasos Demo/Lab 12**:  Configuración Azure y desarrollo local .NET Core. 
* **Objetivos Demo/Lab 13**:
     * Implementación en Azure de Redis.
     * Utilización de Redis desde proyecto local.
     * Implementación de CDN en Azure y utilización en proyecto web contenerizado en Azure.
* **Pasos Demo/Lab 13**:  Configuración Azure y desarrollo local .NET Core. 

5. **Dificultad o problemas presentados y como se resolvieron:** 

   * Los que vimos en clase.

   * Dificultad para utilizar la subscripción caducada y la nueva.  

     * Se resolvió siguiendo la indicación de Billy:	

       $Context = Get-AzSubscription -SubscriptionId "96d8...68d"   
       Set-AzContext $Context   
6. **Detalles de la entrega**: 
* **Evidencias capturas de pantalla en carpetas**: **Capturas**. ( ruta: ...\\CFTIC610-AZ204-Azure-Dev-Tareas\Tarea 3\\* Capturas).
* **Proyectos modificados** : ver carpetas **Proyectos**. ( ruta: ...\CFTIC610-AZ204-Azure-Dev-Tareas\Tarea 3\\* Proyectos).

