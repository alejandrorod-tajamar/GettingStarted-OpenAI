# Getting started with Open AI

Para probar este proyecto, estos son los pasos a seguir:

1. Con una terminal de `Git Bash`, **clona** el repositorio:
   
   ```bash
   git clone https://github.com/alejandrorod-tajamar/GettingStarted-OpenAI.git
   ```
   
2. Abre una terminal de `Command Prompt`.
   
3. Navega al **directorio del proyecto**:
   
   ```cmd
   cd GettingStarted-OpenAI
   ```

4. Crea un **entorno virtual**:

   ```cmd
   python -m venv nombre_del_entorno
   ```

5. Activa el entorno virtual:

   ```cmd
   .\nombre_del_entorno\Scripts\activate
   ```

6. Instala en el entorno virtual cualquier **dependencia** que muestre el error `module not found`:

   ```cmd
   pip install nombre_del_paquete
   ```

7. Configurar las **variables de entorno**:

   En la terminal, y una vez activado el entorno virtual, establece como variables de entorno tu Endpoint y tu clave de API de OpenAI:

   ```cmd
   set AZURE_OPENAI_API_KEY=tu_clave_api
   set AZURE_OPENAI_ENDPOINT=tu_endpoint
   ```

   Crea un archivo `.env` en el directorio raíz del proyecto con el siguiente contenido, reemplazando con tu Endpoint y tu clave de API:

   ```.env
   AZURE_OPENAI_API_KEY=tu_clave_api
   AZURE_OPENAI_ENDPOINT=tu_endpoint
   ```

9. En los archivos `quickstart.py` y `01_OpenAI_getting_started.ipynb`, sustituye el valor de `model` por el nombre de tus modelos, para poder utilizarlos cuando sea necesario.

10. Ejecuta el script `quickstart.py`:

    ```cmd
    python quickstart.py
    ```

11. **Interacción con el asistente**: Sigue las instrucciones en `01_OpenAI_getting_started.ipynb` para interactuar con el asistente virtual.

Para obtener más información sobre cómo utilizar la API de OpenAI, puedes consultar la [documentación oficial](https://platform.openai.com/docs/quickstart).

Además, este [video tutorial](https://www.youtube.com/watch?v=Zb5Nylziu6E) puede ser útil para comprender cómo comenzar con la API de OpenAI
