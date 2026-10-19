# Como instalarlo
---------------

## primero debemos ingresar a nuestro sitio y movernos al directorio de notificaciones 
```bash
omd su MI_SITIO
cd ~/local/share/check_mk/notifications/
```

## Ahora descargamos el archivo y lo instalamos
```bash
wget https://github.com/yupi-yups/checkmk-telegram-graphs/releases/download/checkmk-telegram/telegram_graphs-2.0.0.mkp
mkp add telegram_graphs-2.0.0.mkp
mkp enable telegram_graphs 2.0.0
```

### Ya hechos esos pasos tenemos listo el plugin dentro de nuestro sitio
### Recuerden que para que el bot envie notificaciones SIEMPRE debemos enviar un mensaje al bot primero
### Sino el bot no tendrá permisos para enviar los mensajes
