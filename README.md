# Redes_18_Parcial
Entrega Parcial TP 18 Redes - Santino D'Acunti

Escáner de Red + Netstat (Parcial) – TP Redes 5to Año

=
INFORMACIÓN GENERAL
=

Este proyecto consiste en un escáner de red y un módulo adicional de Netstat desarrollado en Java con interfaz gráfica.

Escáner de Red
--------------
Permite detectar qué dispositivos están activos dentro de un rango de direcciones IP en una red local, utilizando comandos del sistema como ping y nslookup.

- Tiene interfaz gráfica básica
- Permite ingresar IP de inicio y fin
- Verifica si las IPs están bien escritas
- Realiza el escaneo dentro de un rango
- Muestra resultados en tabla (IP, nombre, estado, tiempo de respuesta)
- Puede guardar resultados en archivo de texto
- Incluye barra de progreso
- Incluye filtros (texto y estado) para buscar resultados en la tabla

Netstat (Versión Parcial)
-------------------------
El proyecto también incorpora un módulo adicional que ejecuta el comando `netstat -ano` desde Java, mostrando las conexiones activas y puertos abiertos.

- Ejecuta automáticamente netstat con 3 modificadores:
  - `-a` → muestra todas las conexiones y puertos en escucha
  - `-n` → muestra direcciones en formato numérico
  - `-o` → muestra el PID asociado a cada conexión
- Tiene su propia ventana con botón para ejecutar Netstat
- Muestra los resultados en un área de texto con scroll

=
REQUISITOS RECOMENDADOS
=

- Java JDK 8 o superior
- Eclipse IDE
- Sistema operativo Windows (para compatibilidad con comandos ping y netstat)
- Acceso a una red local

=
CÓMO USAR EL PROGRAMA
=

Escáner de Red
--------------
1. Desde el menú principal, presionar el botón **"Abrir Escáner de Red"**.
2. Ingresar una dirección IP de inicio (por ejemplo: `192.168.0.1`).
3. Ingresar una dirección IP de fin (por ejemplo: `192.168.0.10`).
4. Presionar el botón **"Escanear"**.
5. Esperar a que se complete la barra de progreso.
6. (Opcional) Presionar **"Guardar"** para exportar los resultados.
7. (Opcional) Usar el botón **"Limpiar"** para borrar los campos y la tabla.
8. (Opcional) Usar los filtros de texto y estado para refinar los resultados.

Netstat (Parcial)
-----------------
1. Desde el menú principal, presionar el botón **"Abrir Netstat"**.
2. Presionar el botón **"Ejecutar Netstat -ano"**.
3. Los resultados se mostrarán en un área de texto con scroll.
4. Analizar conexiones activas, puertos abiertos y procesos asociados.

=
Autor/Alumno
=

Santino D'Acunti
