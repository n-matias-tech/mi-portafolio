# Proyecto 02 – Subredes y Enrutamiento entre LANs

## Objetivo
Demostración visual y escrita de una topología con dos subredes conmutadas y enrutadas a través de un router. 

## Topología
<img width="1040" height="598" alt="image" src="https://github.com/user-attachments/assets/2112329d-55da-4167-a63d-3fb4d8343cf1" />
En primer lugar, se encuentra diseñada la topología. Se puede visualizar en la imágen, ambas redes diferentes partiendo de una red 192.168.1.0/24.
En cada una, le asigné su IP de red, broadcast y rango de direcciones para host. 

## Configuración de red
<img width="1920" height="891" alt="image" src="https://github.com/user-attachments/assets/e6a7c7ca-ee18-4241-a276-60c423f10b39" />
Nuevamente, asigné la configuración de red de manera manual a cada dispositivo con fines demostrativos. La diferencia en este proyecto, es que la "puerta de enlace" no es la misma para cada red dado que, cada una es diferente a la otra por más que partan de una misma IP, son subredes distintas. La comunicación depende de cada puerta de enlace.

## Enrutamiento y prueba de conectividad
<img width="1912" height="900" alt="image" src="https://github.com/user-attachments/assets/0d4703fe-ccd8-4c21-bd71-cce805ea391f" />
<img width="1918" height="900" alt="image" src="https://github.com/user-attachments/assets/44282ec6-e363-450e-a6ff-c6123f28cb10" />
<img width="1920" height="900" alt="image" src="https://github.com/user-attachments/assets/36cf244e-8c85-4747-b958-7605a952042f" />
En esta última, se ve como la PC N° 10 de la red: 192.168.1.0 envía una trama a la PC N° 13 de la red contraria y ambas establecen una comunicación correcta y estable. 

## Final
Con estos ejemplos busco demostrar que, más allá de utilizar subnetting para administrar mejor las direcciones, también se aplica el enrutamiento entre ambas redes gracias a la configuración de las interfaces del router. Si no fuera por ello, no habría comunicación entre redes distintas.

## Conceptos aplicados
- Modelo OSI - Capa de enlace y capa de red.
- Pruebas de red (ICMP)
- Routing (Enrutamiento)
- Gateway (Puertas de enlace)
