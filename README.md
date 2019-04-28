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

![Diagrama] (https://1.bp.blogspot.com/-XqZmuHxhXM8/XMXyaM4E5yI/AAAAAAAALYE/XvZnO_cdm40qm7VNMLtREZ5m4KAYw0inwCPcBGAYYCw/s1600/HAProxy.png)
