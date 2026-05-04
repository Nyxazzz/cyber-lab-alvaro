# ⚙️ Instalación del servidor (Ubuntu Server)

## 🖥️ Instalación

- Sistema: Ubuntu Server
- IP estática configurada

## 🌐 Configuración de red

```bash
ip a
```

## Acceso SSH

```bash
sudo apt update
sudo apt install openssh-server
```
Comprobar:

```bash
systemctl status ssh
```

---

# 🌐 4. servicios.md

```markdown
# 🌐 Servicios instalados

## 🖥️ Servidor web

```bash
sudo apt install apache2
```
Comprobar en navegador:
http://IP_DEL_SERVIDOR
