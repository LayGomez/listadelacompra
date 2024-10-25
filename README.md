## Lista de la compra
**Deploy Link:** 👉  <a href="https://laygomez.github.io/listadelacompra/">Lista de la compra</a>
## Descripción

Creación de una lista de la compra donde poder añadir, modificar, eliminar productos, así como poder actualizar la página y que este guarde los productos introducidos y eliminados.

## Tecnologías

- Visual Studio Code
- HTML/CSS
- JavaScript
- Git
- GitHub

## Uso

- Hemos diseñado una interfaz intuitiva y fácil de usar, tanto para dispositivos móviles como para web.
- Se trata de una lista de la compra en la que el usuario puede añadir productos a la lista, marcar los productos de la lista como comprados o no comprados para poder llevar un control, también puede eliminar un producto de la lista.
- Hemos implementado la funcionalidad para poder sincronizar la lista de la compra entre diferentes dispositivos o usuarios.

![alt text](listadecompras.gif)

## Características

- **FUNCIONALIDAD 1:** AÑADIR ÍTEMS A LA LISTA
  1. Permite añadir un artículo con un formato estandarizado a la lista.
  2. Valida que el campo de entrada no esté vacío ni contenga solo espacios en blanco.
  3. Evita duplicados al comparar nombres de ítems sin importar mayúsculas/minúsculas.
  4. Limita el nombre del ítem a un máximo de 25 caracteres.
  5. Limpia el campo de entrada después de añadir un ítem exitosamente.
- **FUNCIONALIDAD 2:** ELIMINAR ÍTEMS DE LA LISTA
  1. Cada ítem tiene un botón de eliminar que permite removerlo de la lista.
  2. Elimina el ítem de la lista inmediatamente sin necesidad de confirmación.
- **FUNCIONALIDAD 3:** Marcar Ítems como Comprados
  1. Incluye una casilla de verificación para marcar ítems como "comprados".
  2. Cambia el estilo visual del ítem para diferenciar los artículos comprados de los que no.
  3. Permite desmarcar ítems, restaurando su estilo original.
- **FUNCIONALIDAD 4:** SINCRONIZACIÓN DE ÍTEMS CON UNA API EXTERNA
  1. Carga automáticamente los ítems desde la API al iniciar la aplicación.
  2. Cada ítem recibe un ID único de la API para facilitar la gestión de datos.
  3. Sincroniza automáticamente los cambios en la lista (añadir, eliminar, marcar como comprado) con la API.
  4. Al recargar la página, muestra el estado actualizado de cada ítem en la lista.

## Autores y Agradecimientos

|                                                                                   **Juan ignacio**                                                                                    |                                                                                **Mónica Simó**                                                                                |                                                                                **Layla Gomez**                                                                                 |                                                                                   **Miguel Reyes**                                                                                    |
| :-----------------------------------------------------------------------------------------------------------------------------------------------------------------------------------: | :---------------------------------------------------------------------------------------------------------------------------------------------------------------------------: | :----------------------------------------------------------------------------------------------------------------------------------------------------------------------------: | :-----------------------------------------------------------------------------------------------------------------------------------------------------------------------------------: |
|            <a href="https://github.com/juanignacioFG"> <img src="https://img.shields.io/badge/github-%23121011.svg?&style=for-the-badge&logo=github&logoColor=white"/></a>            |        <a href="https://github.com/monicasimoF5"> <img src="https://img.shields.io/badge/github-%23121011.svg?&style=for-the-badge&logo=github&logoColor=white"/></a>         |           <a href="https://github.com/LayGomez"> <img src="https://img.shields.io/badge/github-%23121011.svg?&style=for-the-badge&logo=github&logoColor=white"/></a>           |            <a href="https://github.com/MIANREVA2024"> <img src="https://img.shields.io/badge/github-%23121011.svg?&style=for-the-badge&logo=github&logoColor=white"/></a>             |
| <a href="https://www.linkedin.com/in/juan-ignacio-fauro/"> <img src="https://img.shields.io/badge/linkedin%20-%230077B5.svg?&style=for-the-badge&logo=linkedin&logoColor=white"/></a> | <a href="https://www.linkedin.com/in/mónica-simó/"><img src="https://img.shields.io/badge/linkedin%20-%230077B5.svg?&style=for-the-badge&logo=linkedin&logoColor=white"/></a> | <a href="www.linkedin.com/in/layla-gomez-vallejos"> <img src="https://img.shields.io/badge/linkedin%20-%230077B5.svg?&style=for-the-badge&logo=linkedin&logoColor=white"/></a> | <a href="https://www.linkedin.com/in/miguelreyesvasquez/"> <img src="https://img.shields.io/badge/linkedin%20-%230077B5.svg?&style=for-the-badge&logo=linkedin&logoColor=white"/></a> |
