1. **Nombres y apellidos:** Justo Antonio Garrido Herrador

2. **Fecha:** entrega 19-1-2021

3. **Laboratorios / Demos**: 
   - **Laboratorio Módulo 8**: Fichero de Instrucciones: Instructions\Labs\AZ-204_08_lab_ak.md.
   
4. **Resumen de los Ejercicios:**
* **Objetivos Lab 08**: Se entrega este laboratorio a modo de examen.

     * En Azure: crear Web App, mediante contenedor Docker:

       ![](https://github.com/jagarridoh/CFTIC610-AZ204-Azure-Dev-Tareas/blob/main/Tarea%202/Lab%2008%20Capturas/Lab%208%20Azure%20multi-tier%20-%20Ex%201%20Docker%20-%20Task%202%20-%20Step%2007.8.png?raw=true)

     * El contendor se genera a partir de imagen predefinida en Docker Hub:

       ![](https://github.com/jagarridoh/CFTIC610-AZ204-Azure-Dev-Tareas/blob/main/Tarea%202/Lab%2008%20Capturas/Lab%208%20Azure%20multi-tier%20-%20Ex%201%20Docker%20-%20Task%202%20-%20Step%2008.4.png?raw=true)

     * La web API queda de la siguiente manera:

       ![](https://github.com/jagarridoh/CFTIC610-AZ204-Azure-Dev-Tareas/blob/main/Tarea%202/Lab%2008%20Capturas/Lab%208%20Azure%20multi-tier%20-%20Ex%201%20Docker%20-%20Task%202%20-%20Step%2009.png?raw=true)

     * Se despliega correctamente:

       ![](https://github.com/jagarridoh/CFTIC610-AZ204-Azure-Dev-Tareas/blob/main/Tarea%202/Lab%2008%20Capturas/Lab%208%20Azure%20multi-tier%20-%20Ex%201%20Docker%20-%20Task%202%20-%20Step%2010.png?raw=true)

     * Testeamos la aplicacion recien creada:

       ![](https://github.com/jagarridoh/CFTIC610-AZ204-Azure-Dev-Tareas/blob/main/Tarea%202/Lab%2008%20Capturas/Lab%208%20Azure%20multi-tier%20-%20Ex%201%20Docker%20-%20Task%203%20-%20Step%2004.png?raw=true)

     * LLamamos a una API a modo de prueba del contenedor:

       ![](https://github.com/jagarridoh/CFTIC610-AZ204-Azure-Dev-Tareas/blob/main/Tarea%202/Lab%2008%20Capturas/Lab%208%20Azure%20multi-tier%20-%20Ex%201%20Docker%20-%20Task%203%20-%20Step%2005.png?raw=true)

     * Crear API proxy tier mediante Azure API Management:

       * ![](https://raw.githubusercontent.com/jagarridoh/CFTIC610-AZ204-Azure-Dev-Tareas/main/Tarea%202/Lab%2008%20Capturas/Lab%208%20Azure%20multi-tier%20-%20Ex%202%20proxy%20API%20Management%20-%20Task%201%20-%20Step%2007.png)

     * La creamos:

       ![](https://raw.githubusercontent.com/jagarridoh/CFTIC610-AZ204-Azure-Dev-Tareas/main/Tarea%202/Lab%2008%20Capturas/Lab%208%20Azure%20multi-tier%20-%20Ex%202%20proxy%20API%20Management%20-%20Task%201%20-%20Step%2008.png)

     * Definir nueva API dentro de API Mnagement Service:

       ![](https://raw.githubusercontent.com/jagarridoh/CFTIC610-AZ204-Azure-Dev-Tareas/main/Tarea%202/Lab%2008%20Capturas/Lab%208%20Azure%20multi-tier%20-%20Ex%202%20proxy%20API%20Management%20-%20Task%202%20-%20Step%2004.png)

     * Create a blank API:

       ![](https://raw.githubusercontent.com/jagarridoh/CFTIC610-AZ204-Azure-Dev-Tareas/main/Tarea%202/Lab%2008%20Capturas/Lab%208%20Azure%20multi-tier%20-%20Ex%202%20proxy%20API%20Management%20-%20Task%202%20-%20Step%2006.4.png)

     * API created:

       ![](https://raw.githubusercontent.com/jagarridoh/CFTIC610-AZ204-Azure-Dev-Tareas/main/Tarea%202/Lab%2008%20Capturas/Lab%208%20Azure%20multi-tier%20-%20Ex%202%20proxy%20API%20Management%20-%20Task%202%20-%20Step%2006.5.png)

     * Adding operation: 

       ![](https://raw.githubusercontent.com/jagarridoh/CFTIC610-AZ204-Azure-Dev-Tareas/main/Tarea%202/Lab%2008%20Capturas/Lab%208%20Azure%20multi-tier%20-%20Ex%202%20proxy%20API%20Management%20-%20Task%202%20-%20Step%2008.4.png)

     * Setting headers:

       ![](https://raw.githubusercontent.com/jagarridoh/CFTIC610-AZ204-Azure-Dev-Tareas/main/Tarea%202/Lab%2008%20Capturas/Lab%208%20Azure%20multi-tier%20-%20Ex%202%20proxy%20API%20Management%20-%20Task%202%20-%20Step%2012.3.png)

     * Defining Backend (servicio al que enviar peticiones):

       ![](https://raw.githubusercontent.com/jagarridoh/CFTIC610-AZ204-Azure-Dev-Tareas/main/Tarea%202/Lab%2008%20Capturas/Lab%208%20Azure%20multi-tier%20-%20Ex%202%20proxy%20API%20Management%20-%20Task%202%20-%20Step%2015.2.png)

     * Ver los resultados de llamada a la API:

       ![](https://raw.githubusercontent.com/jagarridoh/CFTIC610-AZ204-Azure-Dev-Tareas/main/Tarea%202/Lab%2008%20Capturas/Lab%208%20Azure%20multi-tier%20-%20Ex%202%20proxy%20API%20Management%20-%20Task%202%20-%20Step%2019.png)

     * Tratar la respuesta de la API:

       ![](https://raw.githubusercontent.com/jagarridoh/CFTIC610-AZ204-Azure-Dev-Tareas/main/Tarea%202/Lab%2008%20Capturas/Lab%208%20Azure%20multi-tier%20-%20Ex%202%20proxy%20API%20Management%20-%20Task%203%20-%20Step%2002.4.png)

     * Resultados de la peticion API:

       ![](https://raw.githubusercontent.com/jagarridoh/CFTIC610-AZ204-Azure-Dev-Tareas/main/Tarea%202/Lab%2008%20Capturas/Lab%208%20Azure%20multi-tier%20-%20Ex%202%20proxy%20API%20Management%20-%20Task%203%20-%20Step%2006.png)

     * Asignar política para manipular la respuesta y que sea convertida a JSON:

       ![](https://raw.githubusercontent.com/jagarridoh/CFTIC610-AZ204-Azure-Dev-Tareas/main/Tarea%202/Lab%2008%20Capturas/Lab%208%20Azure%20multi-tier%20-%20Ex%202%20proxy%20API%20Management%20-%20Task%203%20-%20Step%2011.png)

     * Probamos y vemos la respuesta que ahora es JSON y no XML:

       ![](https://raw.githubusercontent.com/jagarridoh/CFTIC610-AZ204-Azure-Dev-Tareas/main/Tarea%202/Lab%2008%20Capturas/Lab%208%20Azure%20multi-tier%20-%20Ex%202%20proxy%20API%20Management%20-%20Task%203%20-%20Step%2016.png)

     * Información en Trace / Outbound:

       ![](https://raw.githubusercontent.com/jagarridoh/CFTIC610-AZ204-Azure-Dev-Tareas/main/Tarea%202/Lab%2008%20Capturas/Lab%208%20Azure%20multi-tier%20-%20Ex%202%20proxy%20API%20Management%20-%20Task%203%20-%20Step%2017.png)

        
* **Pasos Lab 08**:  Configuración y pruebas Azure. 

5. **Dificultad o problemas presentados y como se resolvieron:** ninguna en especial.
6. **Detalles de la entrega**: 
* **Evidencias capturas de pantalla en carpetas**: *** Capturas**. ( ruta: ...\\CFTIC610-AZ204-Azure-Dev-Tareas\Tarea 2\\* Capturas).

