# Funcionalidad-de-la-mascaras-de-red-y-como-se-calculan-segun-la-clasificacion-de-IPs

**¿Cómo funciona?**
Utiliza una operación lógica bit a bit para determinar a que red pertenece una dirección IP.Los bits en 1 indican que parte de la direccion IP pertenece a la red, mientras los bits que son 0 nos indican que pertenecen al host.

Para calcular segun sus clasificaciones se basa en su estructura y en la cantidad de bits que se utlizan para identificar la red y los hots dentro de ella por ejemplo:

***Clase A:*** El primer bit era siempre 0

***Clase B:***  Los dos primeros bits eran 10 

***Clase C:*** Los tres primeros bits eran 110 

