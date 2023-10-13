.. ImgGrayMailJCWUCR documentation master file, created by
   sphinx-quickstart on Wed Oct 11 18:25:55 2023.
   You can adapt this file completely to your liking, but it should at least
   contain the root `toctree` directive.

ImgGrayMailJCWUCR's
====================

Bienvenidos a la documentación de la biblioteca 

Descripción
***********

Esta bilioteca consiste en un conjunto de módulos que permiten:

- Descargar una imagen desde una URL deseada y visualizarla.
- Guardar la imagen en una dirección deseada de la PC.
- Convertir la imagen descargada en su versión en gris.
- Enviar 2 correos.
   * Uno tipo "QuickMail" informativo.
   * Otro con la imagen modificada como adjunto.

Instalación
***********

Para instalar el paquete de la biblioteca *"ImgGrayMailJCWUCR"*, es necesario seguir los siguientes pasos:

#. Crear la ruta o carpeta donde albergará el "main.py" del programa a ejecutar.
#. Crear el "main.py" genérico con el que ejecutará la biblioteca.
#. Activar/Abrir el *CMD*.
#. Ir a la ruta en la que creo el "main.py" y crear un entorno virtual (se recomienda este se llame *"env"*).

.. code-block:: python
   
   python -m venv env

5. Activar el entorno virtual creado

.. code-block:: python
   
   env\scripts\activate

6. Instalar la biblioteca con la siguiente línea de comando:

.. code-block:: python
   
   pip install -i https://test.pypi.org/simple/ ImgGrayMailJCWUCR==0.0.1


7. Importar la biblioteca en el main (Ver el ejemplo que viene en la siguiente sección).
8. Para utilizarlo, importe las funciones al inicio de su "main"

.. code-block:: python

   from ImgGrayMailJCWUCR.imagenes import showImageFromURL, downloadImageFromUrl, grayScaleImage
   from ImgGrayMailJCWUCR.mymail import sendQuickMail, sendAttachEmail

   def main(args):
      
      pass

   if __name__ == '__main__':
      main(sys.argv)

Referencias
***********

Ruta repositorio Python:
<https://github.com/Jeilin04/ProyectoPythonUCR.git>


.. toctree::
   :maxdepth: 2
   :caption: Contenidos:
   
   modules


Indices 
*******

* :ref:`genindex`
* :ref:`modindex`
* :ref:`search`
