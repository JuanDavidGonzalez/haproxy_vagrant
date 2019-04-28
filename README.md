# Balanceador de Carga HAProxy + Vagrant

### Requisitos: 
- Tener instalado Vagrant y VirtualBox


Despliegue de dos servidores web corriendo Apache que cumplen la función de backend atendiendo las peticiones enviadas por el HAProxy.

 HAProxy servidor que mediante algoritmo Round robin realiza el balanceo de las peticiones entre los servidores del backend.

Explicación detallada ver :  [Vagrant + HAProxy](https://www.juandavidgonzalez.com/2019/04/haproxy-vagrant.html)

```
$ cd haproxy_vagrant
$ vagrant up
```
