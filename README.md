# Admin Guide
## By BrianCDev
 Hola querido administrador, es un gusto en recibirte, aca

## Descripción

En este documento se explica cómo enviar mensajes a las pantallas de los jugadores en un servidor de Minecraft 1.12.2 utilizando el comando `/title` y sus parámetros.

## Comando /title

El comando `/title` se utiliza para mostrar mensajes en la pantalla de los jugadores en Minecraft. Con este comando, puedes personalizar cómo se muestra el mensaje utilizando diferentes parámetros. Algunos de los parámetros más comunes que se utilizan son:

- `@a`: Este parámetro indica que el mensaje se enviará a todos los jugadores del servidor.
- `title`: Este parámetro indica que el mensaje se mostrará en la parte superior de la pantalla del jugador.
- `subtitle`: Este parámetro indica que el mensaje se mostrará en la parte inferior de la pantalla del jugador.
- `times`: Este parámetro se utiliza para especificar la duración del mensaje en la pantalla.
- `color`: Este parámetro se utiliza para especificar el color del mensaje.
- `text`: Este parámetro se utiliza para especificar el texto del mensaje.

## Conversión de ticks a segundos

En Minecraft, un tick es la unidad básica de tiempo utilizada en el juego y equivale a 1/20 de segundo. Para convertir ticks a segundos, simplemente divide el número de ticks por 20.

## Ejemplo de comando /title

Aquí se muestra un ejemplo de comando `/title` que muestra dos mensajes en la pantalla de los jugadores:
``` bash
/title @a title {"text":"test","color":"blue","times":{"fadeIn":10,"stay":100,"fadeOut":10}}
```