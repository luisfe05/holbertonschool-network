# Network Basics 1

Este proyecto profundiza en la configuración y diagnóstico de red en Ubuntu Linux:
- Modificación del archivo `/etc/hosts` para resolución de nombres personalizada.
- Identificación de direcciones IPv4 activas en la máquina.
- Apertura de puertos de escucha en loopback/localhost mediante herramientas de red (`nc`).

## Archivos y Tareas

- `0-change_your_home_IP`: Configura `/etc/hosts` para que `localhost` apunte a `127.0.0.2` y `facebook.com` apunte a `8.8.8.8`.
- `1-show_attached_IPs`: Muestra todas las direcciones IPv4 activas en la máquina.
- `2-port_listening_on_localhost`: Abre un socket en escucha en el puerto 98 sobre `localhost`.
