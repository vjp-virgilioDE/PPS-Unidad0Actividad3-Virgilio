# Guía de Introducción a GitHub: Registro, Login y Funcionamiento Básico

GitHub es una plataforma de desarrollo colaborativo de software que permite almacenar, gestionar, y colaborar en proyectos de código mediante el uso de repositorios Git. Además, GitHub ofrece múltiples herramientas y servicios para facilitar la colaboración y el desarrollo en equipo. A continuación, te mostramos cómo registrarte, iniciar sesión y cómo utilizar las funciones básicas de la plataforma.

## 1. Crear una Cuenta en GitHub

### Paso a Paso para Abrir una Cuenta

1. **Accede a [GitHub.com](https://github.com)** desde tu navegador.
2. Haz clic en el botón **Sign up** (Registrarse), ubicado en la parte superior derecha.
3. Completa el formulario de registro:
   - **Username (Nombre de usuario)**: Escoge un nombre único que te identifique en la plataforma.
   - **Email address (Correo electrónico)**: Introduce una dirección de correo electrónico válida.
   - **Password (Contraseña)**: Crea una contraseña segura.
4. Haz clic en **Create account** (Crear cuenta).
5. GitHub puede solicitarte completar un captcha para verificar que no eres un robot.
6. Luego, GitHub te enviará un correo electrónico de verificación a la dirección proporcionada. Ve a tu bandeja de entrada y sigue las instrucciones en el correo para verificar tu cuenta.
7. Una vez verificada la cuenta, puedes seleccionar el plan gratuito o de pago (el plan gratuito es adecuado para la mayoría de los usuarios).

**¡Listo!** Ahora tienes una cuenta en GitHub.

## 2. Iniciar Sesión en GitHub

Para iniciar sesión en GitHub:

1. Dirígete a [GitHub.com](https://github.com).
2. Haz clic en **Sign in** (Iniciar sesión) en la esquina superior derecha.
3. Introduce tu **nombre de usuario o correo electrónico** y **contraseña**.
4. Haz clic en **Sign in** para acceder a tu cuenta.

Si activaste la **autenticación de dos factores (2FA)**, GitHub te pedirá que ingreses el código de verificación desde tu aplicación de autenticación o dispositivo.

## 3. Funcionamiento Básico de GitHub

GitHub organiza el trabajo en **repositorios**, que son espacios para almacenar y gestionar proyectos. A continuación, se presentan las funciones y conceptos clave:

### 3.1 Crear un Repositorio

1. Después de iniciar sesión, haz clic en el icono **+** en la esquina superior derecha y selecciona **New repository**.
2. Rellena los campos:
   - **Repository name**: Nombre del repositorio.
   - **Description**: Opcionalmente, añade una breve descripción del proyecto.
   - **Visibility**: Puedes escoger entre repositorio público o privado.
3. Haz clic en **Create repository** para crear el repositorio.

### 3.2 Clonar un Repositorio

Para trabajar en un proyecto de forma local, puedes clonar el repositorio en tu computadora:

1. En la página del repositorio, haz clic en el botón **Code**.
2. Copia la URL del repositorio.
3. En tu terminal, ejecuta el siguiente comando para clonar el repositorio:

   ```bash
   git clone <URL_DEL_REPOSITORIO>
