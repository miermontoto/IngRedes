# Examen 1
- Nuevo edificio E, con R8 conectado a R4, con un switch, router-on-stick, 
red E 172.16.20.0/24
- Direccionamiento IP entre routers R4-R8 utilizando red 23.UO.24.0/22.
- Direccionamiento IP para dividir la red E con 2 subredes para PCs (cada una de ellas con el mayor número posible de equipos) (1 punto)
- Configurar 2 VLANs (VLAN5 y VLAN10) en el switch y probar conectividad entre equipos de las VLANs (1 punto)
- NAT en VLAN10 de la subred de PCs de E (1 punto)
- Red de routers: Cambiar OSPFv2 por RIPv2 en TODOS los routers y probar conectividad con el resto de la red (1 punto)
- Configurar ACLs extendidas en R8 para permitir conectividad "E-VLAN5"-E-VLAn10, permitir "E-VLAN5"-"B-VLAN40" y prohibir la conectividad con el resto de la red.


## VERIFICACIÓN
- Mostrar configuración VLAN en SW3 de Edificio A
- Mostrar direcciones IPs de PCs A-Planta 3
- Ping A-Planta 3-Dirección con A-Planta 4-Contabilidad
- Mostrar tabla de rutas (IPv4-IPv6) y ACLs en R6
- Web PC "B-VLAN 40" con servidor web "A-VLAN12"
- Ping PC "C-VLAN35" con servidor corporativo C-D
- Mostrar configuración NAT en R5


# Examen 2
- Añadir 2 queipos para dirección en planta 2 del Edificio A. Cambiar "SW0-Switch layer 3"
por "SW0-R0" en planta 0, manteniendo conectividad IPV4 e IPV6
- En el edificio C, añadir un router R9 conectado a R6, con dos subredes iguales(una de PCs y
otra de servidores) de capacidad "Hasta 10 equipos"
- Direccionamiento IP de las nuevas subredes (PCs: 172.16.20.0/24, Servidores:
23.UO.24.0/22)
- NAT para red de PCs. PAT para poder acceder a un nuevo servidor web en la red de PCs en el 
puerto 80 
- Configurar routing OSPFv2 en R9 y probar conectividad con el resto de la red
- Configurar ACL en R9 para permitit únicamente acceso desde C-Vlan35 a la nueva 
subred de servidores
