# 🏗️ Arquitectura del laboratorio

## 📡 Red

- Red local: 192.168.1.0/24

## 🖥️ Equipos

### Kali Linux (Atacante)
- IP: 192.168.1.92

### Ubuntu Server (NAS)
- IP: 192.168.1.126
- Servicios:
  - SSH
  - HTTP
  - DVWA
Los servicios y recursos vulnerables se iran añadiendo con el tiempo

### Windows (Cliente)
- IP: 192.168.1.118

## 🔁 Flujo de ataque

Kali → NAS (escaneo y ataque)
