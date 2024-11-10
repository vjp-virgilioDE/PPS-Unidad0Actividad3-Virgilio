# Guía de Introducción a GitLab: Registro, Inicio de Sesión y Funcionamiento Básico

GitLab es una plataforma de DevOps que permite a los desarrolladores alojar, gestionar y colaborar en proyectos de software mediante repositorios Git. Además de herramientas para la gestión del código, GitLab ofrece características avanzadas para la integración y entrega continua (CI/CD), gestión de tareas y seguridad. A continuación, te explicamos cómo registrarte, iniciar sesión y las funciones básicas de GitLab.

## 1. Crear una Cuenta en GitLab

### Paso a Paso para Abrir una Cuenta

1. **Accede a [GitLab.com](https://gitlab.com)** desde tu navegador.
2. Haz clic en **Register** (Registrarse) en la esquina superior derecha.
3. Completa el formulario de registro:
   - **Full name (Nombre completo)**: Ingresa tu nombre completo.
   - **Username (Nombre de usuario)**: Escoge un nombre único para identificarte en GitLab.
   - **Email**: Introduce una dirección de correo electrónico válida.
   - **Password (Contraseña)**: Crea una contraseña segura.
4. Lee y acepta los **Términos de Servicio** y haz clic en **Register**.
5. GitLab te enviará un correo electrónico de verificación a la dirección proporcionada. Ve a tu bandeja de entrada y sigue el enlace del correo para verificar tu cuenta.
6. Tras la verificación, puedes elegir entre el plan gratuito o explorar los planes de pago (el plan gratuito incluye la mayoría de las herramientas).

**¡Listo!** Ya tienes tu cuenta en GitLab.

## 2. Iniciar Sesión en GitLab

Para iniciar sesión en GitLab:

1. Dirígete a [GitLab.com](https://gitlab.com).
2. Haz clic en **Sign in** (Iniciar sesión) en la esquina superior derecha.
3. Introduce tu **nombre de usuario o correo electrónico** y **contraseña**.
4. Haz clic en **Sign in** para acceder a tu cuenta.

Si activaste la **autenticación de dos factores (2FA)**, GitLab te pedirá que ingreses un código de verificación desde tu dispositivo de autenticación.

## 3. Funcionamiento Básico de GitLab

GitLab organiza el trabajo en **proyectos**, que funcionan como repositorios para almacenar y gestionar el código fuente, además de otras herramientas para la colaboración. A continuación, se explican los conceptos y funciones clave.

### 3.1 Crear un Proyecto

1. Una vez que hayas iniciado sesión, haz clic en **New project** desde el panel principal.
2. Selecciona el tipo de proyecto:
   - **Create blank project**: Comienza un proyecto desde cero.
   - **Create from template**: Usa una plantilla preconfigurada.
   - **Import project**: Importa un proyecto existente desde otra plataforma o desde un archivo.
3. Completa los detalles del proyecto:
   - **Project name**: Nombre del proyecto.
   - **Description**: Opcionalmente, añade una breve descripción.
   - **Visibility level**: Escoge entre público, privado o interno.
4. Haz clic en **Create project** para finalizar.

### 3.2 Clonar un Proyecto

Para trabajar en el proyecto localmente, puedes clonarlo en tu computadora:

1. Ve a la página principal del proyecto y haz clic en **Clone**.
2. Copia la URL HTTPS o SSH.
3. Abre la terminal y ejecuta el siguiente comando para clonar el proyecto:

   ```bash
   git clone <URL_DEL_PROYECTO>
   ```

Este comando descargará el proyecto en tu computadora.

### 3.3 Realizar Cambios y Hacer Commit

Para hacer cambios en tu proyecto:

1. Modifica los archivos en tu repositorio local.
2. Añade los cambios a Git con el siguiente comando:

   ```bash
   git add .
   ```

3. Luego, realiza un commit para guardar los cambios localmente:

   ```bash
   git commit -m "Descripción breve de los cambios"
   ```

### 3.4 Subir Cambios a GitLab (Push)

Para enviar los cambios a GitLab, usa el siguiente comando en tu terminal:

```bash
git push origin main
```

Este comando sube los cambios a la rama `main` del proyecto en GitLab.

### 3.5 Colaboración en Proyectos

GitLab permite colaborar en proyectos de diversas maneras:

- **Fork**: Si deseas contribuir a un proyecto externo, puedes hacer un fork (copia) del proyecto y trabajar en él.
- **Merge Request**: Tras realizar cambios en tu fork, puedes enviar una solicitud de fusión o *merge request* para que tus cambios sean revisados e integrados al proyecto original.
- **Issues**: GitLab permite abrir y gestionar "issues" (problemas o solicitudes de mejora) en los proyectos, permitiendo la discusión de errores, sugerencias o mejoras.

### 3.6 Uso de GitLab CI/CD

GitLab CI/CD permite automatizar procesos de integración y entrega continua, como pruebas y despliegue de aplicaciones. Puedes configurar el CI/CD de GitLab añadiendo un archivo `.gitlab-ci.yml` en la raíz de tu repositorio, donde defines los pasos de construcción, pruebas y despliegue del proyecto.

## 4. Consejos de Seguridad

- **Autenticación de Dos Factores (2FA)**: Activa la autenticación de dos factores para mejorar la seguridad de tu cuenta.
- **SSH**: Configura una clave SSH para evitar usar contraseñas al interactuar con tus proyectos desde la terminal.
- **Gestión de Permisos**: GitLab permite administrar permisos y roles de los colaboradores para mantener la seguridad en proyectos privados.

## Conclusión

GitLab es una plataforma robusta para gestionar proyectos de desarrollo. Siguiendo estos pasos, podrás registrarte, iniciar sesión y entender el funcionamiento básico de la plataforma para comenzar a crear, colaborar y gestionar tus proyectos de manera eficiente.

¡Bienvenido a GitLab!
