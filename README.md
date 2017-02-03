# ejercicioExamenEsther
Examen 2ª evaluación
Hemos realizado 3 redes enlazadas por 3 routers.
La primera red está compuesta por dos subredes, una para 100 host y otra para 2 host, siendo esta primera una red aislada del resto
Para ello hemos calculado las subredes por VLSM, y las hemos conectado a un router a traves de los seriales Fast-Ethernet con un switch
Una vez conectada hemos usado solo la IP de la que nos interesa enlazar para configurarla con los routers de enlace que van a ser 3.
Colocamos la segunda red compuesta por 4 ordenadores con ip fija a los les vamos a asignar sus ip a traves de Deskopt entrando en el propio terminal
Seguidamente añadiremos a esta misma red dos ordenadores con ip dinamica a traves de un servidor DHCP. El servidor tiene que tener asociada una ip estatica de la red
que no esté en uso. Estos irán todos conectados a un switch. Para que nuestros ordenadores tenga ip dinámica solo tenemos que clicar en DHCP entrando en Deskopt.
Hacemos una tercera red con 1 ordenador de IP fija entrando en Deskopt le asignamos su ip, y 5 ordenadores con DHCP añadiendo un servidor DHCP.

Una vez esté todo esto solo tenemos que configurar los router entre sí, usamos la conexión serial para añadirles las ip de los routers
y la conexción fast-Ethernet para conectarlos al switch de cada red. Una vez tengamos todas las redes conectadas todo debe ir correctamente.

Añadimos por último los servidores Web y DNS para que podamos acceder a las páginas directamente poniendo la URL.
