La descripción de la máquina dice lo siguiente:

Laboratorio sencillo donde debemos inspeccionar el código fuente para obtener información de cómo realizar la intrusión.

Desplegamos la maquina

<img width="536" height="431" alt="image" src="https://github.com/user-attachments/assets/aabd87bf-6fde-4b68-ab9c-8e0e7c8b69cf" />

Realizamos un escaneo con nmap para hacer un levantamiento y ver por donde podemos empezar.

nmap -sV 172.17.02 

<img width="798" height="231" alt="image" src="https://github.com/user-attachments/assets/3460cf4d-fbc8-45aa-ae65-fccfbd6f13a4" />

El resultado nos indica que tiene los puertos 22 (ssh) y 80 (http) a abiertos. Proseguimos a abrir un navegador y ver que nos muestra la ip.

<img width="1366" height="720" alt="image" src="https://github.com/user-attachments/assets/5fc136ce-c3db-452c-9a5e-b8e6dd711756" />
Es una pagina web llamada TechWorld Noticias

Proseguimos con analizar su codigo fuente. Para esto ejecutamos en la terminal curl 172.17.0.2 





