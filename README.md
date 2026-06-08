# Homelab
## Introducción
Servidor domestico con varios servicios. Este repositorio recopila todas las configuraciones raliazdas a modo de BackUp y de referencia para fututas ampliaciones.

Todos los servicios están alojados en docker y segemtados en diferentes redes según su función.

## Servicios

### Proxy Net
- Nginx Proxy Manager (NPM) 

  Nota: NPM está en está red y en todas las demás, actúa como punto de entrada y redirige al servicio pertinente ahorrándome potenciales problemas de puertos.

### Tools Net
- It-tools
- Stirling-pdf

### Hobbies Net
- FoundryVTT
- ItsMyTabs

### Media Net
- Filebrowser
- Immich
- Jellyfin
- Nextcloud

### Dev Net
- Glances
- Guacamole
- Homepage
- Portainer
- Uptime-Kuma

### Contenedores Host
- PiHole
- Wg-Easy

  Nota: Servicios "Criticos". Tienes que poder ser accesibles incluso si otros servicios se caen.
  
