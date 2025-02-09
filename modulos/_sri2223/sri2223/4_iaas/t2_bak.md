---
title: "Taller 2: Primeros pasos con OpenStack"
---

## ¿Qué vas a aprender en este taller?

* Acceder a Horizon.
* Configurar el cliente de OpenStack.
* Gestionar imágenes de OpenStack.
* Crear una primera instancia en Openstack.

## Recursos para realizar este taller

* Capítulos 1,2 y 3 del [Curso OpenStack](https://github.com/josedom24/curso_openstack_ies).

## ¿Qué tienes que hacer?

1. Comprueba que puedes acceder a Horizon.
2. Instala el cliente de OpenStack y configúralo con tu fichero de credenciales que debes bajar de Horizon. Los siguientes pasos los debes hacer con el cliente de OpenStack, puedes entrar en Horizon para comprobar si se ha realizado de forma correcta la acción realizada.
3. Sube tu clave pública SSH a openstack. A continuación lista las claves que tienes en tu proyecto.
4. Abre el puerto 22 TCP en el grupo de seguridad *Default*. Permite el protocolo ICMP en el mismo grupo. Lista las reglas del grupoo de seguridad *Default*.
5. CirrOS es una distribución mínima de Linux que fue diseñada para su uso como imagen de prueba en nubes como OpenStack. Sube a tu proyecto la imagen de CirrOS que puedes encontrar [aquí](http://download.cirros-cloud.net/0.5.1/cirros-0.5.1-x86_64-disk.img). Lista las imágenes a las que tienes acceso.
6. Crea una instancia a partir de la imagen CirrOS. Asóciale una IP flotante. Y accede a la instancia por SSH (usuario: **cirros**, contraseña: **gocubsgo**). Visualiza la lista de instancia que tienes creada. Apaga la instancia y vuelve a arrancarla.
7. Elimina la instancia y la imagen que has subido.

{% capture notice-text %}
## ¿Qué tienes que entregar?

1. El comando OSC para subir tu clave pública. La salida y el comando OSC que visualiza las claves SSH que tienes en el proyecto.
2. El comando OSC para añadir las reglas al cortafuego. La salida y el comando OSC que visualiza las reglas del grupo de seguridad *Default*.
3. El comando OSC para añadir la imagen CirrOS. La salida y el comando OSC que visualiza las imágenes disponibles.
4. El comando OSC para crear la instancia. La salida y el comando OSC que visualiza las instancias creadas. Los comandos OSC para asociar una IP flotante.
5. El acceso por SSH a la instancia.
6. Los comandos OSC para borrar la instancia y la imagen CirrOS.
{% endcapture %}<div class="notice--info">{{ notice-text | markdownify }}</div>
