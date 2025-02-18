TranslateBot 
------------

## English

### Overview
Translation Bot is a Discord bot built with Python and the discord.py library. It enables users to translate messages between supported languages directly within Discord servers. The bot leverages third-party translation APIs and supports administrator commands for managing translation settings.

### Features
- **Automatic Translation:** Detects the language of messages and translates them to a default or specified language.
- **Specific Translation Commands:** Use commands like `!translate_[source]_to_[target]` to activate targeted translations.
- **Administration Tools:** Admins can enable/disable translations, block/unblock users, and clear active translation configurations.
- **Direct Commands via DM:** Provides language codes and help instructions via direct messages.

### How to Invite the Bot
1. Visit the Discord Developer Portal and log in with your Discord account.
2. Go to your application’s page and navigate to the “OAuth2” section.
3. Under "OAuth2 URL Generator," select the "bot" scope.
4. Choose the necessary permissions for the bot (e.g., reading messages, sending messages).
5. Copy the generated URL and open it in your browser.
6. Select the server you wish to invite the bot to and authorize its access.

### Usage
- **User Commands:**
  - `!translate_[source]_to_[target]`: Activate specific translation (e.g., `!translate_es_to_en`).
  - `!translate_status`: View current translation configurations and active users.
  - `!translate_codes`: List available language codes.
  - `!translate_help`: Receive help instructions via DM.
  - `!translate_off`: Disable your active translation.

- **Administrator Commands:**
  - `!translate_clean`: Clear all active translations.
  - `!translate_block <user>`: Block a user from translation features.
  - `!translate_unblock <user>`: Unblock a previously blocked user.
  - `!translate_disable`: Disable translations for the server.
  - `!translate_enable`: Enable translations for the server.

### Contributing
Contributions are welcome! Please fork this repository and submit pull requests with detailed descriptions of your changes.

### License
This project is provided "as is" without any warranty. Refer to the project's license file for more information.

### Contact
For questions, issues, or support, please contact the bot administrator or open an issue in the repository.

---

## Español

### Descripción General
Bot de Traducción es un bot de Discord desarrollado en Python utilizando la librería discord.py. Permite a los usuarios traducir mensajes entre idiomas compatibles directamente en los servidores de Discord. El bot utiliza APIs de traducción de terceros y ofrece comandos de administración para gestionar la configuración de las traducciones.

### Características
- **Traducción Automática:** Detecta el idioma de los mensajes y los traduce a un idioma predeterminado o especificado.
- **Comandos de Traducción Específica:** Utiliza comandos como `!translate_[source]_to_[target]` para activar traducciones específicas.
- **Herramientas de Administración:** Los administradores pueden activar/desactivar las traducciones, bloquear/desbloquear usuarios y limpiar las configuraciones de traducción activas.
- **Comandos Directos por DM:** Proporciona códigos de idioma e instrucciones de ayuda mediante mensajes directos.

### Cómo Invitar al Bot
1. Ingresa al Discord Developer Portal e inicia sesión con tu cuenta de Discord.
2. Dirígete a la página de tu aplicación y navega a la sección “OAuth2”.
3. En "Generador de URL de OAuth2", selecciona el alcance "bot".
4. Elige los permisos necesarios para el bot (por ejemplo, leer mensajes, enviar mensajes).
5. Copia la URL generada y ábrela en tu navegador.
6. Selecciona el servidor al que deseas invitar al bot y autoriza su acceso.

### Uso
- **Comandos para Usuarios:**
  - `!translate_[source]_to_[target]`: Activa una traducción específica (por ejemplo, `!translate_es_to_en`).
  - `!translate_status`: Muestra las configuraciones actuales y los usuarios con traducciones activas.
  - `!translate_codes`: Lista los códigos de idioma disponibles.
  - `!translate_help`: Recibe instrucciones de ayuda por mensaje directo.
  - `!translate_off`: Desactiva tu traducción activa.

- **Comandos para Administradores:**
  - `!translate_clean`: Elimina todas las traducciones activas.
  - `!translate_block <usuario>`: Bloquea a un usuario para que no use las funciones de traducción.
  - `!translate_unblock <usuario>`: Desbloquea a un usuario previamente bloqueado.
  - `!translate_disable`: Desactiva las traducciones en el servidor.
  - `!translate_enable`: Activa las traducciones en el servidor.

### Contribuciones
¡Las contribuciones son bienvenidas! Por favor, haz un fork de este repositorio y envía pull requests con descripciones detalladas de los cambios realizados.

### Licencia
Este proyecto se proporciona "tal cual", sin garantía alguna. Consulta el archivo de licencia del proyecto para más detalles.

### Contacto
Para consultas, problemas o soporte, por favor contacta al administrador del bot o abre un issue en el repositorio.
