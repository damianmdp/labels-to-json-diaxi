# labels-to-json-diaxi
Conversión de json con anotaciones desde [LabelStudio](https://labelstud.io/) a archivo json con estructura requerida para el Desafío IA por la Identidad.

##  Instrucciones 
1. Generar la etiqueta
2. Ingresar la transcripción en el campo "Meta". NOTA: En las fotografías tendrían que ingresar un texto que después borren a mano del json final. 
3. Para el caso de noticias múltiples, crear la relación desde el Título a cada una de las partes de la nota.
4. Exportar el JSON completo.
5. Levantarlo con el script de la notebook.

## Running 

1. Crear virtualenv usando python3 (follow https://virtualenvwrapper.readthedocs.io/en/latest/install.html)

        virtualenv <name_env>

2. Activar el virtualenv

        source <name_env>/bin/activate

3. Instalar python requirements

        pip install -r requirements.txt

4. Ejecutar en la terminal 

        jupyter notebook

5. Correr la notebook

        label-studio-annotations-to-json-desafio.ipynb