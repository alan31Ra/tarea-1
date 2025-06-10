
# Documentación Técnica: Creación del Ambiente de Trabajo

Esta guía proporciona los pasos necesarios para configurar un entorno de trabajo colaborativo usando Discord, GitHub y Git en Windows.

---

## Tabla de Contenidos

1. [Creación de Canal en Discord](#1-creación-de-canal-en-discord)
2. [Configuración de Repositorio en GitHub](#2-configuración-de-repositorio-en-github)
3. [Generación de Personal Access Token (PAT)](#3-generación-de-personal-access-token-pat)
4. [Instalación de Git para Windows](#4-instalación-de-git-para-windows)
5. [Configuración Inicial de Git](#5-configuración-inicial-de-git)
6. [Conclusión](#6-conclusión)

---

## 1. Creación de Canal en Discord

1. Acceder a [https://discord.com](https://discord.com) e iniciar sesión.
![INICIO DE SESION](https://github.com/alan31Ra/tarea-1/blob/9ff17f07eabe4c753b97958c558f2df003847004/imagenes/Captura%20de%20pantalla%202025-06-09%20195628.png)

2. Hacer clic en el botón `+` para crear un nuevo servidor. <br><br>

![Presionar + ](https://github.com/alan31Ra/tarea-1/blob/f7dced70a56008c910f2424cfdd35939be0b4a4a/imagenes/Captura%20de%20pantalla%202025-06-09%20203619.png)

3. Elegir "Crear Mi Propio Servidor" y seguir los pasos del asistente.
4. Crea un canal con nombre adecuado para la comunicación del equipo.


![FINAL](https://github.com/alan31Ra/tarea-1/blob/431ca171e2fcdbb305469fb5252369434d395b05/imagenes/Captura%20de%20pantalla%202025-06-09%20204718.png)

✏️ *DESCRIPCION*
Al crear un canal de Discord se facilita la comunicación, además de tener una mejor organización de la información, ya que cuenta con divisiones (CANALES DE TEXTO) que ayudan a la distribución 
de tareas o temas en específico.


---

## 2. Configuración de Repositorio en GitHub desde Git Bash


1. Crear un nuevo repositorio vacío en GitHub desde [https://github.com](https://github.com).  
   - **No** marcar la opción *"Initialize this repository with a README"*.  
   - Asignar un nombre al repositorio.
   - Seleccionar si será **público** o **privado**.  

✏️ *En este caso el repositorio será público para que los compañeros puedan visualizarlo en caso de que tengan alguna duda.*

2. Abrir **Git Bash** en la carpeta local de tu proyecto:

   ```bash
   cd ruta/de/el/proyecto
   ```

![FINAL](https://github.com/alan31Ra/tarea-1/blob/16a464b62bc8832ddad0bc90be1b5410e1b09988/imagenes/Captura%20de%20pantalla%202025-06-09%20105840.png)

3. Clonar el repositorio principal

![FINAL](https://github.com/alan31Ra/tarea-1/blob/16a464b62bc8832ddad0bc90be1b5410e1b09988/imagenes/Captura%20de%20pantalla%202025-06-09%20105931.png)

4. Posteriormente se pueden hacer modificaciones en él

 ```bash
   git init
   git add . //Para añadir cualquier archivo al Git
   git commit -m "Primer commit"
   git remote add origin https://github.com/tuusuario/proyecto-xyz.git
   git branch -M main
   git push -u origin main
```
![FINAL](https://github.com/alan31Ra/tarea-1/blob/16a464b62bc8832ddad0bc90be1b5410e1b09988/imagenes/Captura%20de%20pantalla%202025-06-09%20110447.png)


---

## 3. Generación de Personal Access Token (PAT)

1. Clic en [https://github.com/settings/tokens](https://github.com/settings/tokens).

![X](https://github.com/alan31Ra/tarea-1/blob/c34e1c0dc548ca86726a9308fd6be3f125e9e7a2/imagenes/Captura%20de%20pantalla%202025-06-09%20103640.png)

Al momento de  entrar a Settings se debe seleccionar *Developer Settings*  y despues 
personal access tokens.

2. Hacer clic en **Generate new token**.
![X](https://github.com/alan31Ra/tarea-1/blob/c34e1c0dc548ca86726a9308fd6be3f125e9e7a2/imagenes/Captura%20de%20pantalla%202025-06-09%20103655.png)

3. Asigna un nombre y define la expiración.
![X](https://github.com/alan31Ra/tarea-1/blob/c34e1c0dc548ca86726a9308fd6be3f125e9e7a2/imagenes/Captura%20de%20pantalla%202025-06-09%20103726.png)

4. Marcar los permisos necesarios, como:
   - `repo`
   - `workflow`
   - `etc`
![X](https://github.com/alan31Ra/tarea-1/blob/c34e1c0dc548ca86726a9308fd6be3f125e9e7a2/imagenes/Captura%20de%20pantalla%202025-06-09%20103807.png)

5. Copiar el token generado y guárdalo en un lugar seguro.



⚠️ *Nota: El token no podrá verse nuevamente después de salir de la página. Guardar una copia segura.*

---

## 4. Instalación de Git para Windows

1. Descarga Git desde: [https://git-scm.com/download/win](https://git-scm.com/download/win).
2. Ejecuta el instalador.<br><br>
![X](https://github.com/alan31Ra/tarea-1/blob/fe1666f3dc62ab297cb7292afbd8f5ee4619a879/imagenes/Captura%20de%20pantalla%202025-06-09%20104936.png)


3. Acepta las opciones predeterminadas (salvo que se requiera una configuración especial).
<p align="center">
  <img src="https://github.com/alan31Ra/tarea-1/blob/fe1666f3dc62ab297cb7292afbd8f5ee4619a879/imagenes/Captura%20de%20pantalla%202025-06-09%20105016.png"
  " width="300">
</p>


4.Dar *Siguiente* hasta que aparezca la siguiente ventana: <br><br>

<p align="center">
  <img src="https://github.com/alan31Ra/tarea-1/blob/fe1666f3dc62ab297cb7292afbd8f5ee4619a879/imagenes/Captura%20de%20pantalla%202025-06-09%20105153.png"
  width="300">
</p>

5. Finalizar la instalación y ejecutar Git Bash.<br><br>

<p align="center">
  <img src="https://github.com/alan31Ra/tarea-1/blob/fe1666f3dc62ab297cb7292afbd8f5ee4619a879/imagenes/Captura%20de%20pantalla%202025-06-09%20105303.png" width="300">
</p>

6. Se podrá usar la terminal de GIT  
<p align="center">
  <img src="https://github.com/alan31Ra/tarea-1/blob/fe1666f3dc62ab297cb7292afbd8f5ee4619a879/imagenes/Captura%20de%20pantalla%202025-06-09%20105447.png" width="300">
</p>

---
