
# Universidad de San Carlos de Guatemala
# Facultad de Ingenieria, escuela de Ciencias y Sistemas
# Redes de Computadoras 1
## Nombre: Piter Angel Esaú Valiente de León, Carnet: 201902301
## Diseño de Redes 

Conexión de switch a varias pc y de switch en switch, tomando en cuenta que el nivel 1 esta conformado por "Administración, Gerencia, Atención al Cliente y Recursos Humanos" para el nivel 2 se toman las siguientes áreas "Oficina A, Oficina B y Oficina C".

![Alt text](FOTO1-1.png)

---

## Configuración de Switch (1 y 2)

Tomando en cuenta los comandos utilizados 
```
enable -entrar como ser privilegiado   
 
show run -para todos los puertos que estamos usando

conf t -modo de configuración

exit -para salir

no ip domain-lookup -para al momento de ingresar un mal comando no de mucho problema 

wr -para guardar la configuración

hostname (nombre) -para configurar el cual el nombre que coloquemos

enable secret -para colocar contraseña
```

![Alt text](<FOTO9 SW1.png>)

![Alt text](<FOTO10 SW2.png>)

---

## Configuración VPC 

Área de Administración 
---
![Alt text](<FOTO2 admin.png>)
---
Área de Gerencia-Secretaria
---
![Alt text](<FOTO3 gerencia.png>)
---
Área de Atención al Cliente
---
![Alt text](<FOTO4 cliente.png>)
---
Área de Recursos Humanos
---
![Alt text](<FOTO5 RRHH.png>)
---
Área de Oficina A
---
![Alt text](<FOTO6 A.png>)
---
Área de Oficina B
---
![Alt text](<FOTO7 B.png>)
---
Área de Oficina C
---
![Alt text](<FOTO8 C.png>)

---

## Pings entre los hosts
Ping entre Administración a Oficina A
---
![Alt text](image-9.png)
---
Ping entre Oficina B a Gerencia
---
![Alt text](image-10.png)
---
Ping entre Atención al Cliente a Oficina C
---
![Alt text](image-11.png)

---

## Simulación ARP/ICMP

![Alt text](image-3.png)
![Alt text](image-4.png)
![Alt text](image-5.png)
![Alt text](image-6.png)
![Alt text](image-7.png)
![Alt text](image-8.png)

## Demostración de la captura de un paquete ARP/ICMP

![Alt text](image-12.png)