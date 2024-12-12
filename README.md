# Jmeter-Servers-Performance-Monitoring

Pruebas de rendimiento al sitio web asecuritysite.com con el plugin "Servers Performance Monitoring"  
midiendo metricas del servidor como CPU, discos, red y memoria en tiempo real.

Sitio Web: **asecuritysite.com**  
Internet speed: **25 Mbps**  
Conexion Type: **Conexión Ethernet**  
Operating system: **Qubes OS: Fedora Template**  
Users:  **1 (Simulación completa de interacción de usuario)**  

**Network:**
![Network_1](https://github.com/user-attachments/assets/79ef18b8-0c1a-4de9-aff1-3abe10edd097)

**CPU:**
![CPU_1](https://github.com/user-attachments/assets/ca0ed8df-e4b3-423d-9eb4-e6a92bf51f73)

**Memory:**
![Memory_1](https://github.com/user-attachments/assets/57b62139-c598-41e0-8523-b49315af0ddf)

**Disks:**
![Disks_1](https://github.com/user-attachments/assets/70388ad8-9cce-48f8-9ae0-09285fcf941a)

**RESULTADOS:**
Endpoint: https://asecuritysite.com/index consume demasiados recursos, como se puede observar en la gráfica general
y específicamente en la gráfica Network_1.png, y mucho disco,por lo que concluimos que está mal optimizado. 
Se reciben demasiados bytes, por lo que la carga es lenta.

<img width="1280" alt="jp@gc - PerfMon Metrics Collector" src="https://github.com/user-attachments/assets/97f0404c-ad25-4b75-a9f4-49ee482442f7" />
![Metricas_1](https://github.com/user-attachments/assets/83565103-e5b2-4f82-bf4a-479716575cf7)

Endpoints analizados:  
1-https://asecuritysite.com/  
2-https://asecuritysite.com/index  
3-https://asecuritysite.com/challenges  
4-https://asecuritysite.com/blogs  
5-https://asecuritysite.com/ip  
6-https://asecuritysite.com/ids  
7-https://asecuritysite.com/magic  
8-https://asecuritysite.com/forensics  
9-https://asecuritysite.com/Cisco  
10-https://asecuritysite.com/cyberdata  
11-https://asecuritysite.com/tests  
12-https://asecuritysite.com/fun  
13-https://asecuritysite.com/subjects  
14-https://asecuritysite.com/Home/About  
