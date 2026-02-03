✅ Requisitos previos

ISO de Ubuntu Server (recomendada la versión LTS).

VMware Workstation instalado.

Mínimo:

4 GB RAM (ideal 8 GB).

20–30 GB de disco libre.

CPU con virtualización activada.

👉 Descarga oficial:

Ubuntu Server 24.04 LTS → https://ubuntu.com/download/server

🧩 Paso 1 — Crear la máquina virtual

Abre VMware y sigue:

Create a New Virtual Machine

Selecciona Typical (Recommended)

Elige Installer disc image file (ISO) y carga el ISO.

💡 VMware normalmente detecta Ubuntu automáticamente.

⚙️ Paso 2 — Configuración recomendada

Usa estos valores para un laboratorio o servidor ligero:

Sistema: Linux → Ubuntu 64-bit

CPU: 2 cores

RAM: 4–8 GB

Disco: 30 GB (modo single file mejora rendimiento)

👉 Antes de terminar, entra en Customize Hardware y verifica que el adaptador de red esté en:

👉 NAT (más fácil para tener internet).

🚀 Paso 3 — Arrancar e instalar Ubuntu Server

Cuando inicie la VM:

Selecciona Install Ubuntu Server

Idioma → Español o Inglés

Keyboard → automático

Network → DHCP normalmente funciona sin tocar nada.

💾 Paso 4 — Almacenamiento

Para instalación rápida:

👉 Selecciona:

✅ Use entire disk
✅ Set up this disk as an LVM group (recomendado)

No necesitas cifrado para laboratorio.

👤 Paso 5 — Usuario y seguridad

Define:

Nombre del servidor

Usuario

Contraseña fuerte

💡 Marca:

✅ Install OpenSSH server

👉 Esto es CLAVE para conectarte por SSH sin abrir la consola.

📦 Paso 6 — Software adicional

Cuando pregunte por paquetes:

👉 Puedes dejarlo vacío para un servidor limpio.

(O elegir Docker o file server si ya sabes que lo necesitas).

⏳ Paso 7 — Finalizar

Espera la copia de archivos (~5–10 min).

Reinicia.

Si vuelve a arrancar el instalador 👉 quita el ISO de la VM.

🔥 Verificación rápida

Cuando veas algo como:

Ubuntu 24.04 LTS server login:


👉 ¡Listo! Tu servidor está funcionando.

Comprueba internet:

ping google.com

⭐ Recomendación PRO (muy importante)

Actualiza todo apenas entres:

sudo apt update && sudo apt upgrade -y
