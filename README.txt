# 🌐 Laboratorio de Redes - Guía de Configuración y Evidencias

Este repositorio contiene la documentación, los pasos detallados y las capturas de pantalla del laboratorio de redes realizado.

---

## 🛠️ Pasos del Laboratorio y Evidencias

### Paso 1: Diseño de la Topología Física
Se realizó el despliegue lógico y físico de los routers, switches y dispositivos finales.
![Topología Inicial de la Red](./images/1.png)

### Paso 2: Configuración Básica de Dispositivos
Se ingresó a la CLI de cada router y switch para asignar el nombre de host y contraseñas.
![Configuración básica en la CLI](./images/2.png)

### Paso 3: Asignación y Configuración del Direccionamiento IP
Configuración de las direcciones IP, máscaras de subred y gateways en las interfaces.
![Asignación de direcciones IP](./images/3.png)

### Paso 4: Creación y Asignación de VLANs
Se configuraron las VLANs requeridas en los switches de distribución y acceso.
![Configuración de VLANs en Switches](./images/4.png)

### Paso 5: Configuración de Enlaces Troncales (Trunking)
Activación del protocolo del encapsulamiento IEEE 802.1Q en los enlaces de los switches.
![Configuración de Puertos Troncales](./images/5.png)

### Paso 6: Enrutamiento Inter-VLAN
Creación y configuración de subinterfaces en el router principal (Router-on-a-stick).
![Configuración de Subinterfaces en Router](./images/6.png)

### Paso 7: Implementación del Protocolo de Enrutamiento Dinámico
Configuración de las áreas de enrutamiento dinámico para garantizar la convergencia.
![Configuración del Protocolo de Enrutamiento](./images/7.png)

### Paso 8: Configuración de Servidores DHCP
Habilitación de pools de DHCP en el router para la asignación automática de direcciones IP.
![Verificación de Pool DHCP](./images/8.png)

### Paso 9: Configuración de Seguridad y Acceso Remoto (SSH)
Configuración de líneas VTY para permitir la administración segura vía SSH.
![Configuración de Acceso SSH Seguro](./images/9.png)

### Paso 10: Implementación de Listas de Control de Acceso (ACLs)
Creación y aplicación de ACLs para filtrar el tráfico de red y restringir accesos.
![Aplicación de Reglas de ACL](./images/10.png)

### Paso 11: Pruebas de Conectividad (Ping y Traceroute)
Verificación de la comunicación extremo a extremo mediante el envío de paquetes ICMP.
![Prueba de Ping Exitoso](./images/11.png)

### Paso 12: Verificación de Tablas de Enrutamiento
Inspección final de la tabla de rutas IP en el core de la red.
![Tabla de Enrutamiento Final](./images/12.png)
