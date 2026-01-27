## SIN ACABAR

# En este artículo se va a hablar sobre las diferencias de rendimiento/usabilidad que hay entre 2 distros de GNU/LINUX y W11

Estos SO serán instalados en el mismo equipo:

## EQUIPO

**Nombre** 
- HP Laptop 15s-eq1xxx

**Procesador**
- AMD Ryzen 7 4700U
  - 8 Núcleos

**Gráfica**
- AMD Radeon Graphics 512MB

**RAM**
- 32 GB Crucial DDR4 3200 MHz

**Disco duro**
- Intel 1TB

**Placa Base**
- HP 8707

Este equipo ha sido usado por mi durante los últimos 4 años tanto para jugar, como para máquinas virtuales, como para ofimática, etc

## Distros elegidas

### ZORIN OS
(Agregar enlaces a la página oficial)
Agregar versiones

### LINUX MINT
- Versión 22.2
  - Kernel 6.14.0.29



# COMPARACIONES

## LINUX MINT

Como se puede observar, la interfaz de Linux Mint es bastante limpia gracias al uso de [Cinnamon](https://projects.linuxmint.com/cinnamon/) que es la interfaz gráfica usada por esta distro de GNU/LINUX.

Nada más iniciar el equipo, se abre una ventana de bienvenida, desde la cual podemos realizar diferentes acciones como:

- Configurar el equipo
- Instalar actualizaciones
- Personalizar el equipo
- Leer la documentación del sistema
- Buscar información en foros

Si vemos el monitor de rendimiento del sistema (el equivalente al **Administrador de tareas**) vemos, que el sistema esta consumiendo apenas 1.5GB de RAM y que el espacio ocupado en disco es de 7.5GB.

Otra cosa a tener en cuenta del sistema, es que no te obliga a actualizar cada vez que el sistema lo requiera, si no que puedes estar sin atualizar el tiempo que quieras.

En cuanto al uso general del sistema, se siente más rápido que Windows, pero no tanto. No se si se deba a Cinnamon, pero probando otras distros de Linux con KDE como escritorio, siento que es mucho más eléctrico y responsivo. La parte positiva es que en Linux, puedes instalar el entorno gráfico que más te guste con un comando.

Tambien he de mencionar el uso de RAM. En el caso de Linux Mint, todas las aplicaciones consumen menos RAM que en Windows (ya sean aplicaciones nativas o de terceros) y estan no suelen aumentar el consumo de la RAM, o si lo aumentan, no lo hacen de una forma exagerada.

### Software preinstalado

**Inutil**
- En Linux Mint encontramos algunas plaicaciones preintsladas que sirven para conectarse a servicios de Linux Mint y que la gente no va a llegar a usar 

**Útil**
- Suite de LibreOffice
- Mozilla Firefox
- Gestor de software
  - El equivalente a la Microsoft Store, pero con software útil y popular
- Aplicaciones nativas (que no necesitas inicar sesión para usarlas) 


## Windows 11

Por lo general, el sistema no se siente fluido y las aplicaciones nativas tardan en abirse (siendo el explorador de archivos el peor caso), además de que para la mayoría de ellas, hace falta una cuenta de Microsoft para poder usarlas.

Además, si quieres usar herramientas ofimaticas (la suite de Microsoft 365 copilot) no solo necesitas una cuenta de Microsoft, si no que has de pagar una licencia para poder usarlo


---
### Psoible anexo?
**Software inutil**
- Aplicación Experience
- Centro de opiniones
- Asistencia rápida
- Cámara
- Contactos
  - Directorio
- Grabadora **
- Mapas - Fuera de soporte
- Noticias - ES LITERALMENTE EDGE, PERO CONSUMIENTO MAS 
- Peliculas y TV
- Power Automate **
- Family
- Journal
- Kinect
- Mensajes del operador
- Bing
- Microsoft Phone Link
 
**Software para el que necesitas una cuenta de Microsoft**
- Copilot	
- Clipchamp
- Onedrive
- Outlook
  - Correo y calendario
- Power Automate
- Teams
- Microsoft To Do
- XBOX
- Whiteboard
- Centro de opiniones
  - Necesitas iniciar sesión con Microsoft para la experiencia completa

 **Software vomitivo**
 - MICROSOFT DESIGNER 

## Diferencias en el uso de  RAM 

Para estas pruebas, he capturado el consumo de RAM nada más iniciar el programa y despuÉs de unos minutos de uso, para ver como y cuento aumenta el condumo en los SO

### Inicio equipo

**Linux Mint**
- 1.4GB

**Windows 11**
- 4GB 

### Explorador de archivos

**Linux Mint**
- 39.8MB

**Windows 11**
- 193MB - 252MB
  - En Windows, el explorador de archivos se encuentran precargado en el sistema, porloq ue siempre esta consumiento RAM. Al dejar de usar el explorador de archivos y encontraerse en 2º plano, mantiene el consumo de 190-250MB y poco a poco va disminuyendo el consumo (he llegado a ver mínimos de 55MB)

### Bloc de notas

**Linux Mint**
- 39.8MB

**Windows 11**
- 85MB 

### Navegador

**Linux Mint**
- 1.5GB

**Windows 11**
- 4GB 

### Suite de Office

**Linux Mint**
- Writer - 135MB
- Calc - 129MB
- Point

**Windows 11**
- Writer - 270-714MB
- Calc - 270-339MB
- Point

### Thunderbird

**Linux Mint**
- 194 - 214 MB

**Windows 11**
- 400 MB - 500 MB

### Calculadora

**Linux Mint**
- 26.5 MB

**Windows 11**
- 75 - 140 MB 

### Navegador - Mozilla/Microsoft Edge
Para esta prueba he abierto un navegador con 4 pestañas: Youtube, Drive, google imagenes y nueva pestaña

**Linux Mint**
- 1GB

**Windows 11**
- 1.2GB 

# Ventajas Windows 11 vs GNU/Linux

- Es más intuitivo de usar/instalar gracias a su interfaz y sus 
- La mayoria de software se desarrolla para Windows y no tiene una versión para GNU/LINUX o las versiones alternativas para Linux suelen ser desarrolladas por equipos más pequeños y no tienen tanto soporte / funcionalidades
- 

# ÚLTIMAS CAGADAS DE MICROSOFT

- Sacar parches para arreglar actualizaciones, para tener que sacar más parches que arreglen los parches anteriores
- Meter copilot en todos lados cuando nadie lo usa
  - Cambiar/Eliminar la suite de Office para integrarla con Copilot
- Elevar los requisitos mínimos de hardware para Windows 11 y dejar a millones de equipos completamente funcionales sin opción a actualizarse (mejor para GNU/LINUX)
- Agregar morralla y bloatware innecsesario e inutil
  - Hacer que la mayoría de software nativo de Windows sea funcional solo con cuentas de Microsoft
