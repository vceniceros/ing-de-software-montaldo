# docker

![funciono en tu maquina? joya ahi se la mando a cada usuario (seguramente el creador de docker)](image-50.png)

## que es docker

docker automatiza el despliegue de aplicaciones aisladas en contenedores

## tradicionalmente

### como se despliega una aplicacion

- acceder directamente al sistema a configurar
- copiar codigo/ejecutable a desplegar
- usar herramientas interactivas para inspeccionar y modificar sistemas
- asegurar que todas las dependencias este presentes

### problemas

- altamente repetitivo
- gran chance de error
- interacciones entre aplicaciones
- es dificil reconstruir la configuracion(en mi maquina funciona)

## infraestructura as Code (IaC)

en lugar de realizar modificaciones manualmente se usa un lenguaje de programacion especifico para el dominio de configuraciones de maquina

Algunas herramientas:

- chef
- puppet
- ansible
- terraform

## infraestructura declarativa

las herramientas de infraestrutura como codigo suelen ser declarativas

Declarativo: especifica que objetivo lograr
Imperativo: especifica el como 

![alt text](image-51.png)

## Mascota vs ganado

### infraestructura mascota

- nombre especifico
- unicas
- cuidadas
- mantenimiento delicado
- presentes aunque no sean necesarios
- servicios legacy
- servicios unicos 

### infraestructura ganado

- numero de serie
- practicamente identicas
- remplazables
- "mantenimiento" creando otras intancias
- se crean y se destruyen a necesidad
- servicios sin estado interno relevante

## maquinas virtuales

![alt text](image-52.png)

emulacion de una maquina real
- provee aislamiento total
- unica opcion para ejecutar programas de otras arquitecturas de hardware
- al menos dos sistemas operativos ejecutandose

algunas herramientas
- virtual box
- vmware

![alt text](image-53.png)

## linux namespaces

separa grupos del sistema para que diferentes procesos tengan acceso a diferentes conjuntos de recursos

- mnt (sistema de archivos)
- pid (listados de procesos)
- net (interfaces de red)
- ipc (comunicacion entre procesos)

mostrar todos los procesos: 
``` bash
$ ps -e
PID TTY TIME CMD
1 ? 00:00:33 systemd
2 ? 00:00:00 kthreadd
4 ? 00:00:00 kworker/0:0H
6 ? 00:00:00 mm_percpu_wq
```

mostrar todos los procesos, aislando el namespace pid:

```bash

$ unshare --pid --mount-proc --fork ps -e
PID TTY TIME CMD
1 pts/0 00:00:00 ps
```

## contenedores

Linux namespaces para separar grupos de procesos

- aislamiento configurable de aplicaciones
- usan el mismo kernel que el host
- overhead minimo

Algunas herramientas

- Docker
- LXC

![alt text](image-54.png)

## contenerdores vs virtual machine

![alt text](image-55.png)

## docker

conceptos centrales que administra docker 

- container: grupo aislado de procesos
- image: template usado para crear crear contenedores (sistemas de archivos + meta data)
- dockerfile: Archivo con instrucciones para construir una imagen

## que brinda docker

- consistencia:

cualquier imagen se obtiene , inicia y configura de la misma forma

- replicidad

los contenedores basados en una misma imagen con inicialmente iguales

- aislamiento 

se puede controlar la interaccion entre el conetenedor y el mundo exterior