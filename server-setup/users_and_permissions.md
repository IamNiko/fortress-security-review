# 🧑‍💻 Configuración de Usuarios, Grupos y Permisos

## 🎯 Objetivo
Configurar una estructura segura de usuarios y permisos en el servidor (Raspberry Pi) para simular un entorno realista.

---

## 👥 Crear usuarios y grupo

```bash
sudo adduser admin
sudo usermod -aG sudo admin

sudo adduser employee1
sudo adduser employee2

sudo groupadd developers
sudo usermod -aG developers employee1
sudo usermod -aG developers employee2
