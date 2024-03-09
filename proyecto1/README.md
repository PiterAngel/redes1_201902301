# Universidad de San Carlos de Guatemala
# Facultad de Ingenieria, escuela de Ciencias y Sistemas
# Redes de Computadoras 1
# PROYECTO 1
# GRUPO 9 
*Carnet* | *Nombre* |
| ------ | ------ |
| 201902301 | Piter Angel Esaú Valiente de León |
| 201900647 | Eduardo Josué González Cifuentes |

# TOPOLOGIA


# CONFIGURACIÓN DE SWITCHES
## SERVER SW1
``` 
enable
conf t
no ip domain-lookup
hostname SW1
do w

interface range fa0/1-5   Para el rango de interfaz de 1 a 5
switchport trunk encapsulation dot1q
switchport mode trunk     CAMBIO DE LAS INTERFASES

vlan 18
name CONTABILIDAD
vlan 28
name SECRETARIA
vlan 38
name RRHH
vlan 48
name IT
end
```
## Cliente: SW7, SW8, SW10, SW2, SW3, SW4, SW5, SW6
