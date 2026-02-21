# Kali Linux on Samsung Tab S6 with Raspberry Pi Zero 2 W --> Hacking without a "PC"
### 📌 Here you can see how I implemented a Raspberry Pi Zero 2 W with Kali Linux OS (for this board) using a Samsung tablet Tab S6 Lite 2022 Edition as monitor via VNC


<img src="https://github.com/user-attachments/assets/0d1251fb-096a-48b1-bab8-cdc030bb3567" width="400">

---

### 🛒 Things we need
En primer lugar debemos contar con los siguientes elementos para llevar a cabo el proyecto:
- Raspberry Pi Zero 2 W
- Cable alimentador para la Raspberry
- Raspberry Pi Imager Software (PC)
- Tarjeta SD (cualquier tamaño, recomendado 64gb) para Raspberry
- Porta-SD (para cargar mediante nuestra PC el OS Kali Linux desde Raspberry Pi Imager)
- Tablet o dispositivo mobil que pueda descargarse/correr la app VNC (RVNC Viewver en Playstore)
- Termux para android (realizar la conexion ssh y comandos)
- Conexion a misma red wifi (entre tablet y Raspberry)

---

### 🔎 What's the first step here?
Una vez obtenido todo lo anterior, procedemos con lo siguiente
- En nuestra PC descargamos `Raspberry Pi Imager`, con este software podremos colocar cualquier Sistema Operativo a nuestra placa, en este caso, Kali Linux para Raspberry Pi Zero 2 W.
- Ya instalada la app deberemos conectar nuestra tarjeta SD a un porta-SD, y conectarlo a nuestra computadora.
- Volvemos al softare de Raspberry y nos dirijimos al menu en la parte de `OS` O "Sistemas Operativos". Aqui seleccionaremos `Other specific-purpose OS` y buscamos entre las opciones `Kali Linux`, y luego buscamos `Raspberry Pi Zero 2 W` (Kali Linux ARM image for the Raspberry Pi Zero 2 W).
- 
