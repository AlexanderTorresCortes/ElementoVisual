### COMPONENTE FORMULARIO CON VALIDACIÓN DE CONTRASEÑAS



#### DESCRIPCIÓN

El componente formulario es una ventana realizada en un JPanel en netbeans, ha sido creado con la finalidad de usarse en algun login por ejemplo, puedes ingresar diferentes tipos de datos y lo que diferencia este elemento de los demás es la librería usada para su creación, dicha librería es REGEX, esta nos ayudará con el tema de las validaciones brindandonos diferentes métodos que servirán como restricciones o condiciones que el usuario debe seguir para poder crear una contraseña segura.
El elemento puede ser arrastrado simplemente desde la paleta de elementos de netbeans y usado en cualquier tipo de frame que netbeans nos ofrece, una vez añadido el elemento obviamente.



#### DIFERENTES USOS DEL ELEMENTO

-  **Sistema de Registro de Usuarios:** Un sistema de registro de usuarios para una aplicación web o de escritorio. Los usuarios pueden crear una cuenta ingresando su información básica junto con una contraseña segura.
-   **Aplicación de Inicio de Sesión:** Un formulario de inicio de sesión que también permite a los usuarios registrarse si no tienen una cuenta. Aquí, el formulario solicitaría la información necesaria para crear una cuenta nueva, incluyendo la contraseña.
-   **Gestor de Contraseñas:** Una aplicación que ayuda a gestionar contraseñas, donde los usuarios pueden almacenar y organizar sus contraseñas. En este caso, el formulario sería para agregar una nueva contraseña a la lista, y el validador de contraseñas asegura que la contraseña sea lo suficientemente segura.
-  **Aplicación de Compras en Línea:** Un formulario de registro para una tienda en línea donde los usuarios pueden crear una cuenta para hacer compras. Además de la información básica, el validador de contraseñas garantizaría la seguridad de la cuenta.



#### CARACTERÍSTICAS 

- Fácil entendimiento
- implementación sencilla gracias a que es un elemento de la paleta


                    
#### API
<p>

</p>
El metodo ValidarMayuscula nos ayudara a verificar que nuestra contrasena ingresada contenga al menos una letra mayuscul.

Metodos

| Nombre | Tipo de dato que retorna | Tipo de dato que recibe | Descripcion |
|------- | -------------------------|-------------------------|-------------|
| validarMayuscula | Boolean | String | va a realizar las búsquedas especificas del patron dento de la cadena de texto.|


El metodo ValidarNumero nos ayudara a buscar un numero dentro de la contrasena qaue fue ingresada por el usuario.


| Nombre | Tipo de dato que retorna | Tipo de dato que recibe | Descripcion |
| ------ | ------------------------ |-------------------------|-------------|
| validarNumero|Boolean|String,int|va a buscar el patron definido \\d en la cadena de texto .|
<p>



#### VIDEO SOBRE EL FUNCIONAMIENTO DEL ELEMENTO VISUAL

https://youtu.be/iAe5nDsxpXg?si=fD0FBcrGJTPvzn3A



#### AUTORES
- Torres Cortés Alexander Jassiel - *Estudiante* - (https://github.com/AlexanderTorresCortes)
- Cruz Alonso Kelly Adanari - *Estudiante* - (https://github.com/adanari08)
