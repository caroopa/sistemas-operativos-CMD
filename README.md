# Introducción a comandos de CMD

### Fecha de entrega: 19/6

Poner "CMD" en el buscador de Windows y abrirlo.  
Ejecutar los siguientes comandos (se puede copiar y pegar con `Ctrl + C` y `Ctrl + V`).  
Para cada uno, describir lo que sucede o el resultado que les devuelve.   

Dentro de este Drive, crear un documento dentro de su curso correspondiente y escribir sus respuestas:  
https://drive.google.com/drive/folders/1QTvgGz76OgoNEJOAWywEUe_F7AlZ7yaJ?usp=sharing  
Nombrarlo con su nombre y apellido (o nombre de grupo).

**Puntos extra 👀:**
- Investigar y explicar con sus palabras qué hace cada comando.
- Buscar qué otros comandos existen para ver el hardware de la computadora o información del sistema operativo. 

## 🧠 Información general del sistema

`systeminfo`  
`hostname`  
`whoami`  
`wmic os get caption`  
`wmic cpu get name`  
`wmic logicaldisk get name,size,freespace`  
`help`  
`tree` (OJO, con este van a necesitar Ctrl + C para cancelar la escritura porque es mucho)  
`date /t`  
`time /t`  

## 🧼 Consola y entorno

`cls`  
`title Hola que tal`  
`color 0a`  
`set`  
`echo %PATH%`  
`echo Hola, mundo`  
`echo mensaje & ping localhost -n 10 >nul`  
`echo Bienvenidos > saludo.txt`  
`for /l %i in (5,-1,1) do @echo %i & timeout /t 1 >nul`  

## 💾 Información de hardware (RAM, CPU, disco, BIOS)

`wmic memorychip get capacity`  
`wmic computersystem get TotalPhysicalMemory`  
`wmic cpu get name,NumberOfCores`  
`wmic logicaldisk get name,size,freespace`  
`wmic diskdrive get model,size`  
`wmic bios get version`  
`wmic baseboard get product,manufacturer`  

## 📡 Red y conectividad
`ipconfig`  
`ping google.com`  
`netstat` (OJO, con este van a necesitar Ctrl + C para cancelar la escritura porque es mucho)  
`getmac`  
