# KeyGenerator
# Generador de Claves

Este es un generador de claves desarrollado en Python que te permite generar claves seguras para tus aplicaciones.
Puedes personalizar la longitud de las claves y generar múltiples claves para diferentes aplicaciones.

## Sobre su Uso

1. Ejecuta el archivo `KeyGen1.ipynb` para generar tus claves. Puedes utilizar Jupyter Notebook o Google Colab para ejecutar el código.
2. El programa te pedirá tu nombre y te saludará personalmente.
3. Luego, podrás ingresar el nombre de la aplicación para la que deseas generar una clave o escribir 'salir' para finalizar.
4. Después, deberás especificar la longitud de la clave que deseas generar.
5. El generador de claves creará una clave que cumple con ciertos requisitos de seguridad (debe contener al menos un número, una letra y un símbolo).
6. Las claves generadas se almacenarán en un archivo de texto llamado `claves.txt` junto con el nombre de la aplicación a la que pertenecen.

## Ejemplo de Ejecución

```python
Escribe tu nombre: Juan
Hola, Juan, estas serán tus claves:

Ingrese el nombre de la aplicación para la que desea generar una clave (o 'salir' para terminar): Gmail
Ingrese en números la cantidad de caracteres para su clave: 16
Clave generada para 'Gmail': A1@bZc$D3!eFgH5I

Ingrese el nombre de la aplicación para la que desea generar una clave (o 'salir' para terminar): salir
```

## Requisitos

Este generador de claves utiliza Python y la biblioteca estándar de Python, por lo que no es necesario instalar ninguna dependencia adicional.
