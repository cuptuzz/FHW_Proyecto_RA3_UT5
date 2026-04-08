# Configuración de la máquina virtual

## Software utilizado
- **Aplicación:** VirtualBox 
- **Versión:** 7.2.2 r170484  

## Configuración aplicada
- **CPU:** 2 Núcleos  
- **RAM:** 512MB
- **Disco virtual:** 10GB  
- **Controlador de almacenamiento:** SATA 
- **Red:** NAT  
- **Audio / vídeo / otros ajustes relevantes:** 16MB VMSVGA, Audio ICH AC97  

## Relación con el equipo real
- He intentado simular el hardware del pc del taller, que tiene una CPU de 2 núcleos y 1GB de memoria RAM. 
- Lo que no puedo simular correctamente son los dispositivos de audio ni los de red, el resto es bastante cercano a lo que podríamos esperar.

## Observación importante
La máquina virtual sirve como **banco de pruebas previo**, pero no garantiza al 100 % el mismo comportamiento que el equipo real.
- Si se quiere instalar la versión completa del sistema operativo, debemos subir el espacio virtual del disco, esto se debe a que en la partición del /root se descargará el sistema operativo y todas sus aplicaciones, aunque podemos poner un disco más pequeño (5GB o el mínimo recomendado) y usar la versión live, que quizás se pueda hacer persistente.
