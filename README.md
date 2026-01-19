# Ejercicio Carrera Camellos
## Integrantes
Agustín Borreguero Castro<br>
Adrián Bautista<br>
Alberto <br>
Virgilio<br>
José Antonio<br>

<br>

### ¿Qué IP has tenido que poner en el código del Cliente? ¿Es una IP pública o privada? 
Hemos puesto esta IP:<br>
<img width="501" height="30" alt="image" src="https://github.com/user-attachments/assets/d72a33ad-b4a4-40b1-a95a-8333e6623722" /><br><br>
Es una IP pública ya que pertenece a la aplicación Radmin.



---

### Si el Árbitro cierra su portátil a mitad de carrera, ¿qué excepción salta en tu pantalla? 
Sale este error: <br>
<img width="678" height="229" alt="image" src="https://github.com/user-attachments/assets/ff159c7b-7b17-47cf-b40a-d4a6c281b671" /><br> 

Este error aparece en el cliente cuando el servidor (el Árbitro) se cierra de forma repentina mientras la carrera está en marcha. En nuestro caso, ocurre cuando el árbitro apaga o cierra su portátil o finaliza el programa del servidor sin avisar a los clientes.

---

### ¿Por qué es necesario que todos estéis conectados a la misma red (mismo Router/Switch) para que esto funcione con IPs tipo 192.168.x.x?

En nuestro caso no es necesario que todos estemos conectados al mismo router porque usamos una IP pública (26.116.126.185), que es accesible desde Internet. Esto permite que los clientes se conecten al servidor aunque estén en redes distintas, a diferencia de las IP privadas 192.168.x.x que solo funcionan en la red local.
