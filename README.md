# 🔍 Task Insider - URL Redirect Service

**Servicio de redirección inteligente para Task Insider**

Este repositorio contiene una página de redirección que automáticamente dirige a los usuarios a la URL actual de Task Insider en Cloudflare Tunnel.

---

## 🌐 URL Pública

**URL fija para embedar:**
```
https://ecabanas-rgb.github.io/taskinsider-redirect/
```

Esta URL **nunca cambia** y siempre redirige a la instancia actual de Task Insider.

---

## 🔄 Cómo Funciona

1. **Usuario accede** a `https://ecabanas-rgb.github.io/taskinsider-redirect/`
2. **Página lee** el archivo `url-actual.txt`
3. **Redirige automáticamente** a la URL de Cloudflare Tunnel
4. **Usuario accede** a Task Insider

---

## 📋 Archivos

### `index.html`
Página de redirección con:
- Diseño moderno de Task Insider
- Spinner de carga
- Manejo de errores
- Redirección automática

### `url-actual.txt`
Archivo de texto simple que contiene la URL actual de Cloudflare Tunnel.

**Actualizado automáticamente** por el sistema cada vez que cambia la URL.

---

## 🔐 Seguridad

### ✅ Seguro
- Solo contiene una URL pública de redirect
- No expone credenciales
- No expone código de Task Insider
- No almacena datos de usuarios

### 🔒 Protección
Task Insider requiere autenticación:
- Login con email + password
- OAuth con Google (localhost)

**Sin credenciales = Sin acceso a datos**

---

## 🎯 Uso con Google Sites

Esta URL se puede embedar en Google Sites usando un iframe:

1. Crear página en Google Sites
2. Insertar → Embed
3. Pegar URL: `https://ecabanas-rgb.github.io/taskinsider-redirect/`
4. Ajustar tamaño
5. Publicar

**Resultado:** URL fija en Google Sites que siempre lleva a Task Insider.

---

## 🔧 Mantenimiento

El archivo `url-actual.txt` se actualiza automáticamente mediante:

- Script Python en el servidor de Task Insider
- GitHub Personal Access Token
- PyGithub API

**No requiere intervención manual.**

---

## 📞 Soporte

**Administrador:** Enrique Cabañas  
**Email:** ecabanas@findep.com.mx

---

**Task Insider** - Visibilidad total de tus proyectos
