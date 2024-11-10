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
   ```

Este comando descargará una copia del repositorio en tu computadora.

### 3.3 Realizar Cambios y Hacer Commit

1. Una vez que hayas modificado archivos en tu repositorio local, puedes "guardar" estos cambios en GitHub mediante un **commit**.
2. En tu terminal, añade los cambios al área de staging usando:

   ```bash
   git add .
   ```

3. Luego, crea un commit con el siguiente comando:

   ```bash
   git commit -m "Descripción breve de los cambios"
   ```

### 3.4 Subir Cambios a GitHub (Push)

Para enviar tus commits al repositorio en GitHub, usa el siguiente comando en tu terminal:

```bash
git push origin main
```

Este comando sube los cambios a la rama `main` en GitHub.

### 3.5 Colaboración en Proyectos

GitHub permite a los usuarios colaborar en proyectos de diversas maneras:

- **Fork**: Si deseas contribuir a un repositorio que no te pertenece, puedes hacer un fork (copia) del repositorio y trabajar en él.
- **Pull Request**: Después de realizar cambios en tu fork, puedes proponer que esos cambios se incorporen al proyecto original mediante un pull request.
- **Issues**: GitHub permite abrir "issues" (problemas o propuestas de mejora) en los proyectos, para que los usuarios discutan errores, sugerencias o mejoras.

### 3.6 Uso de GitHub Actions

GitHub Actions permite automatizar flujos de trabajo, como ejecutar pruebas automáticas o desplegar aplicaciones. Puedes configurar GitHub Actions desde la pestaña **Actions** en tu repositorio, eligiendo plantillas o creando flujos personalizados.

## 4. Consejos de Seguridad

- **Autenticación de Dos Factores (2FA)**: Activa la autenticación de dos factores para mejorar la seguridad de tu cuenta.
- **SSH**: Configura una clave SSH para evitar el uso de contraseñas al interactuar con tus repositorios desde la terminal.
- **Manejo de Colaboradores**: Si tienes un repositorio privado, puedes gestionar los permisos de otros usuarios para mantener la seguridad del proyecto.

## Conclusión

GitHub es una herramienta poderosa para colaborar en proyectos de software. Siguiendo estos pasos, podrás registrarte, iniciar sesión y entender el funcionamiento básico de la plataforma para comenzar a crear, colaborar y gestionar proyectos de desarrollo.

¡Bienvenido a GitHub!
