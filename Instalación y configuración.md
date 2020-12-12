# Instalación y configuración

![Instalación](/Fotos/Captura1.PNG)

## Instalación del servidor dnsmasq

apt install dnsmasq

## Configuración dnsmasq

#### Iniciar servicio

service dnsmasq start

#### Detener servicio

service dnsmasq stop 

## Empezamos con la configuración

Primero vamos a abrir el fichero /etc/dnsmasq.conf

Ponemos nuestro nombre dns y la IP, y como es local tambien se lo indicamos.

![Instalación](/Fotos/configuracion.PNG)

Editamos el archivo /etc/resolv.conf

![Instalación](/Fotos/resolv.PNG)

Y por último editamos el archivo /etc/hosts

![Instalación](/Fotos/hosts.PNG)

Y reiniciamos con service dnsmasq restart

