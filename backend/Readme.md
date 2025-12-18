# Internet – Conocimientos breves

## LAN (Local Area Network)

Una red LAN se puede crear usando un **switch**, el cual permite la comunicación entre varias computadoras y dispositivos dentro de un mismo lugar (casa, aula u oficina).

El **router no es necesario** para que los dispositivos se comuniquen dentro de la LAN, pero **sí es necesario** si se desea salir a Internet o comunicarse con otras redes.

Para tener acceso a Internet, el **switch se conecta al router**, y las computadoras envían paquetes primero al switch y luego al router, que finalmente los envía hacia Internet.

---

## Paquetes de datos

Un **paquete** es como una pequeña “cajita” que contiene información que viaja por la red hacia otras computadoras o hacia Internet.

Un paquete puede contener:
- Dirección IP de origen  
- Dirección IP de destino  
- Protocolo (TCP o UDP)  
- Número de paquete  
- Datos  

---

## Tipos de redes

- **LAN (Local Area Network):** red local en un área pequeña como una casa o edificio.
- **CAN (Campus Area Network):** conecta varias redes LAN dentro de un campus, como universidades o institutos.
- **WAN (Wide Area Network):** conecta redes a grandes distancias, incluso entre países y continentes. Internet es la WAN más grande del mundo.

---

## Componentes de red

- **Switch:** permite la comunicación entre dispositivos dentro de una LAN.
- **Router:** conecta una red con otras redes.
- **Router doméstico:** dispositivo común en las casas que integra router, switch y WiFi.
- **ISP (Internet Service Provider):** proveedor de servicios de Internet que permite el acceso a la red mundial.
- **PoP (Point of Presence):** punto físico donde un ISP tiene su infraestructura para conectar a los usuarios a Internet.

---

## IP pública y privada

- **IP privada:** se usa dentro de una red local (LAN) y puede repetirse en distintas redes del mundo.
- **IP pública:** es asignada por el ISP y permite que una red se comunique con Internet.

---

## Peering

El **peering** es un acuerdo entre redes para intercambiar tráfico directamente, sin pasar por intermediarios innecesarios.  
Esto permite **menor latencia**, **mayor velocidad** y **reducción de costos**, haciendo la comunicación más eficiente.

---

## Jerarquía de red

La **jerarquía de red** organiza la infraestructura en niveles para mejorar el rendimiento y la administración:
- **Acceso:** donde se conectan los usuarios.
- **Distribución:** conecta varias redes de acceso.
- **Núcleo (core):** conecta toda la red principal del campus o proveedor.

---

## ¿Cómo funciona Internet?

Internet funciona como una **red de redes** a nivel mundial.

Las LAN de casas, empresas e instituciones se conectan a través de **routers** y **proveedores de Internet (ISP)**.  
Los ISP utilizan **PoP**, enlaces de alta velocidad y acuerdos de **peering** para interconectar redes a nivel nacional e internacional.

La información viaja en forma de **paquetes**, pasando por múltiples routers hasta llegar a su destino, formando así la red global conocida como **Internet**.

---

## ¿Qué es HTTP?

HTTP es un protocolo que permite que el navegador y una página web se comuniquen, enviando y recibiendo información a través de una URL.

---

## ¿Qué es el nombre de dominio?

El nombre de dominio es la dirección de una página web que usamos en lugar de la dirección IP del servidor.  
El **DNS** se encarga de traducir ese nombre en una dirección IP para que nuestra computadora pueda encontrar la página web.

---

## ¿Qué es el Hosting?
El Hosting es un espacio en un servidor donde se puede almacenar varios archivos de una página web para que
pueda ser accesible desde internet.

---

## DNS y ¿cómo funciona?
El DNS(Sistema de nombres de dominios) es un sistema que traduce los nombres de dominios a una dirección IP.
Cuando una persona escribe el nombre de una página web, el DNS busca la IP asociada a ese nombre y se la envía a la computadora del usuario para que pueda conectarse al servidor correcto.

---

## ¿Los navegadores y cómo funcionan?

El navegador web es un programa que nos permite accedar a páginas web en internet.Funciona enviando peticiones HTTP/HTTPS a servidores web, recibiendo respuestas y renderizando el contenido para mostrarlo al usuario.