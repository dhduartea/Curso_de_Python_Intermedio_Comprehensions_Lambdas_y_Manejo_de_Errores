# Comando usados
En este archivo se encuentran los comandos usados en la línea de comandos(Windows).

## Antes de empezar
- Creación de ambiente virtual(venv).

    `python3 -m venv nombre_venv`

- Activación del ambiente.

    `.\venv\Scripts\activate`

- Desactivar ambiente.

    `deactivate`

- Creación de un alias en powershell con el nombre "avenv" para activar el ambiente de forma más simple.

    `Set-Alias  -Name avenv  -Value .\venv\Scripts\activate`

- Si se tiene algún requerimiento de otro ambiente se instala de esta forma.

    `pip install -r requirements.txt `


## Ejecución al finalizar el proyecto 

- Guardar requerimientos en un archivo

    `pip freeze > requirements.txt`
