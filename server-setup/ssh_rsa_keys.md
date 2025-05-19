# 🔐 Configuración de Acceso SSH por Clave RSA

## 🎯 Objetivo
Configurar el acceso al servidor (Raspberry Pi) exclusivamente mediante autenticación por clave pública RSA, deshabilitando el ingreso por contraseña.

---

## 📍 Parte 1 – Generar par de claves en Parrot OS

En tu máquina **Parrot (cliente/auditor)**:

```bash
ssh-keygen -t rsa -b 4096 -C "pepín@parrot"
