
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
2. Hacer clic en el botón `+` para crear un nuevo servidor.
3. Elegir "Crear Mi Propio Servidor" y seguir los pasos del asistente.
4. Crea un canal con nombre adecuado para la comunicación del equipo.

📸 **Imagen sugerida:** captura del proceso de creación del servidor  
`![Creación de servidor en Discord](ruta/a/la/imagen1.png)`
![INICIO DE SESION]("imagenes/Captura de pantalla 2025-06-09 195628.png")

✏️ *Agregar una breve descripción del propósito del canal.*

---

## 2. Configuración de Repositorio en GitHub

1. Ve a [https://github.com](https://github.com) y accede a tu cuenta.
2. Haz clic en **New repository**.
3. Asigna un nombre al repositorio (por ejemplo: `proyecto-xyz`).
4. Marca la opción "Initialize this repository with a README" si lo deseas.
5. Crea el repositorio.

📸 **Imagen sugerida:** captura de pantalla del formulario de creación de repositorio  
`![Formulario de creación de repositorio](ruta/a/la/imagen2.png)`

✏️ *Explica aquí si el repositorio será público o privado y por qué.*

---

## 3. Generación de Personal Access Token (PAT)

1. Ve a [https://github.com/settings/tokens](https://github.com/settings/tokens).
2. Haz clic en **Generate new token**.
3. Asigna un nombre y define la expiración.
4. Marca los permisos necesarios, como:
   - `repo`
   - `workflow`
5. Copia el token generado y guárdalo en un lugar seguro.

📸 **Imagen sugerida:** vista de configuración de token  
`![Generación del token en GitHub](ruta/a/la/imagen3.png)`

⚠️ *Nota: El token no podrá verse nuevamente después de salir de la página. Guarda una copia segura.*

---

## 4. Instalación de Git para Windows

1. Descarga Git desde: [https://git-scm.com/download/win](https://git-scm.com/download/win).
2. Ejecuta el instalador.
3. Acepta las opciones predeterminadas (salvo que se requiera una configuración especial).

📸 **Imagen sugerida:** proceso de instalación paso a paso  
`![Instalación de Git](ruta/a/la/imagen4.png)`

✏️ *Especificar aquí si se requiere alguna configuración personalizada (por ejemplo: uso de editores como VS Code).*

---

## 5. Configuración Inicial de Git

Ejecuta estos comandos desde Git Bash:

```bash
git config --global user.name "Tu Nombre"
git config --global user.email "tu@email.com"
git config --global credential.helper manager
```

📸 **Imagen sugerida:** terminal Git Bash con los comandos ejecutados  
`![Configuración inicial de Git](ruta/a/la/imagen5.png)`

✏️ *Puedes comentar sobre buenas prácticas para configurar múltiples cuentas si se usan.*

---

## 6. Conclusión

Con estos pasos realizados:

- Se cuenta con un canal de comunicación funcional en Discord.
- El repositorio en GitHub está listo para control de versiones.
- Git está instalado y configurado correctamente.

📌 *A partir de aquí puedes comenzar el trabajo colaborativo usando ramas, pull requests y commits firmados.*

---

## 📎 Anexos (Opcional)

- [ ] Enlaces útiles
- [ ] Recursos del equipo
- [ ] Plantillas para issues o documentación interna
