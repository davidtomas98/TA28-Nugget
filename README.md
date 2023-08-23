# 🚀 Tarea: Creación de Proyecto de Consola .NET y Uso de NuGet

Este documento detalla cómo crear un proyecto de consola .NET y agregar librerías mediante NuGet.

## 📌 Pasos a Seguir

### 1. Crear el Proyecto de Consola .NET

1. Abre Visual Studio.
2. Navega a "Archivo" > "Nuevo" > "Proyecto..."
3. Selecciona "Consola de la aplicación (.NET Core)".
4. Ingresa un nombre y una ubicación para el proyecto.
5. Haz clic en "Crear".

### 2. Instalar las Librerías con NuGet

1. Accede a "Herramientas" > "Administrador de paquetes NuGet" > "Consola del Administrador de paquetes".
2. Asegúrate de que el proyecto esté seleccionado en el menú desplegable.
3. Ejecuta los siguientes comandos para instalar las librerías:

   - **NUnit:**
     ```shell
     Install-Package NUnit
     ```

   - **Entity Framework:**
     ```shell
     Install-Package Microsoft.EntityFrameworkCore
     ```

   - **Identity Framework:**
     ```shell
     Install-Package Microsoft.AspNetCore.Identity
     ```

   - **JWT:**
     ```shell
     Install-Package System.IdentityModel.Tokens.Jwt
     ```

### 3. Verificar las Librerías Instaladas

1. En el Explorador de soluciones, dentro de la sección "Referencias", las librerías deberían estar listadas.
