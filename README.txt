# 🌐 Laboratorio de Redes - Guía de Configuración y Evidencias

Este repositorio contiene la documentación, los pasos detallados y las capturas de pantalla del laboratorio de redes realizado. A continuación, se presenta la secuencia de implementación junto con sus respectivas evidencias visuales.

---

## 📌 Requisitos Previos
* Simulador de redes instalado (Cisco Packet Tracer, GNS3 o EVE-NG).
* Archivo de topología base (incluido en la carpeta `/topologias`).

---

## 🛠️ Pasos del Laboratorio y Evidencias

### Paso 1: Diseño de la Topología Física
Se realizó el despliegue lógico y físico de los routers, switches y dispositivos finales de acuerdo al diagrama de red establecido.
![Topología Inicial de la Red](images/1.png)

### Paso 2: Configuración Básica de Dispositivos (Hostname y Contraseñas)
Se ingresó a la CLI de cada router y switch para asignar el nombre de host, contraseñas de consola y habilitar el cifrado de claves.
![Configuración básica en la CLI](images/2.png)

### Paso 3: Asignación y Configuración del Direccionamiento IP
Configuración de las direcciones IP, máscaras de subred y gateways en todas las interfaces Ethernet y Serial.
![Asignación de direcciones IP](images/3.png)

### Paso 4: Creación y Asignación de VLANs
Se configuraron las VLANs requeridas en los switches de distribución y acceso, asignando los puertos correspondientes a cada departamento.
![Configuración de VLANs en Switches](images/4.png)

### Paso 5: Configuración de Enlaces Troncales (Trunking)
Activación del protocolo del encapsulamiento IEEE 802.1Q en los enlaces que interconectan los switches y el router.
![Configuración de Puertos Troncales](images/5.png)

### Paso 6: Enrutamiento Inter-VLAN (Router-on-a-Stick)
Creación y configuración de subinterfaces en el router principal para permitir la comunicación entre los diferentes segmentos de red.
![Configuración de Subinterfaces en Router](images/6.png)

### Paso 7: Implementación del Protocolo de Enrutamiento Dinámico (OSPF/EIGRP)
Configuración de las áreas de enrutamiento dinámico y publicación de las redes para garantizar la convergencia global de la infraestructura.
![Configuración del Protocolo de Enrutamiento](images/7.png)

### Paso 8: Configuración de Servidores DHCP
Habilitación de pools de DHCP en el router central para la asignación automática de direcciones IP a los hosts de la red de acceso.
![Verificación de Pool DHCP](images/8.png)

### Paso 9: Pruebas de Conectividad (Ping y Traceroute)
Verificación de la comunicación extremo a extremo mediante el envío de paquetes ICMP entre hosts de distintas subredes.
![Prueba de Ping Exitoso](images/9.png)

### Paso 10: Verificación de Tablas de Enrutamiento
Inspección final de la tabla de rutas IP en el core de la red para validar que todas las rutas se hayan aprendido correctamente de forma dinámica.
![Tabla de Enrutamiento Final](images/10.png)

---

## 📂 Estructura del Proyecto

```text
├── README.md
├── topologias/
│   └── laboratorio.pkt
└── images/
    ├── 1.png
    ├── 2.png
    ├── 3.png
    ├── 4.png
    ├── 5.png
    ├── 6.png
    ├── 7.png
    ├── 8.png
    ├── 9.png
    ├── 10.png
    ├── 11.png
    └── 12.png
```

## 👥 Autores
* **Tu Nombre** - [@tu_usuario_github](https://github.com)
