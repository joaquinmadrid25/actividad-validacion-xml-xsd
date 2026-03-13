Validación de XML mediante XSD y Expresiones Regulares

Descripción 

En este proyecto se ha creado un documento XML que contiene información de varios usuarios registrados. Para comprobar que los datos introducidos son correctos, se ha diseñado un esquema XSD que valida la estructura del XML y aplica diferentes restricciones utilizando expresiones regulares (RegEx).

El objetivo es asegurar que cada dato tenga el formato adecuado antes de ser aceptado.

* Restricciones aplicadas Correo electrónico El campo email debe respetar el formato habitual de una dirección de correo electrónico válida.

* Teléfono El número de teléfono debe tener 9 dígitos y comenzar por 6, 7, 8 o 9, siguiendo el formato utilizado en España.

* Código postal El código postal debe estar compuesto por 5 dígitos y corresponder a los rangos utilizados en el sistema postal español.

* Nombre de usuario El nombre de usuario debe empezar por una letra minúscula y solo puede contener letras, números o el carácter "_".

* Contraseña La contraseña debe cumplir ciertos requisitos de seguridad: Tener un mínimo de 8 caracteres. Incluir al menos una letra mayúscula. Incluir al menos una letra minúscula. Contener al menos un número. Incluir al menos un símbolo.

Herramientas utilizadas Para realizar esta actividad se han utilizado las siguientes herramientas: Visual Studio Code para la edición de los archivos. Extensión XML para validar los documentos. La página regex101 para diseñar y comprobar las expresiones regulares.


La validación del documento se ha realizado vinculando el archivo XML con el esquema XSD. Mediante Visual Studio Code se ha comprobado que el XML cumple correctamente todas las restricciones definidas en el esquema.

