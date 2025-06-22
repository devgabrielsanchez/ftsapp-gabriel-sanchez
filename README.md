# 🚀 FTSApp – File Transfer Secure App

🔒 Proyecto de transferencia segura de archivos usando TLS, con arquitectura cliente-servidor y una interfaz web intuitiva.

Desarrollado como parte del proyecto final para la materia **Programación sobre Redes**.

---

## 🧰 Tecnologías utilizadas

- 🟢 **Node.js**
- ⚙️ **Express.js**
- 🔐 **TLS (Transport Layer Security)**
- 🌐 **HTML / CSS / JavaScript**

---

## 📁 Estructura del proyecto

```
ftsapp-gabriel-sanchez/
├── public/              # Archivos estáticos (frontend)
├── src/                 # Código fuente del servidor y cliente TLS
│   ├── web-server.js        # Servidor Express para la interfaz web
│   ├── secure-server.js     # Servidor TLS para manejo de archivos
│   ├── secure-client.js     # Cliente TLS para comandos
│   └── tls-client.js        # Cliente TLS alternativo
├── package.json         # Configuración del proyecto y dependencias
└── README.md            # Documentación del proyecto
```

---

## ⚙️ Instalación y ejecución

### 1. 🔽 Clonar el repositorio

```bash
git clone https://github.com/devgabrielsanchez/ftsapp-gabriel-sanchez.git
cd ftsapp-gabriel-sanchez
```

### 2. 📆 Instalar dependencias

```bash
npm install
```

### 3. 🧪 Ejecutar en modo desarrollo

```bash
npm run dev
```

> Asegurate de tener certificados TLS válidos en la carpeta `/src`.

---

## 🌐 Uso de la interfaz

Accedé a la app desde:\
➡️ `https://localhost:3000`

### Funciones disponibles:

- 📂 **Listar archivos** (`LIST`)
- ⬇️ **Descargar archivo** (`GET`)
- ⬆️ **Subir archivo** (`PUT`)
- 🗑️ **Eliminar archivo** (`DELETE`)
- ✏️ **Renombrar archivo** (`RENAME`)

La interfaz muestra una tabla dinámica y botones de acción con confirmación.

---

## 🔐 Seguridad

✅ Todas las operaciones se realizan sobre **TLS**\
📁 El servidor carga y descarga archivos desde una carpeta específica\
⚠️ ¡Tus datos viajan cifrados!

---

## 📌 ¿Por qué este proyecto?

Este proyecto busca:

- Comprender la implementación de **conexiones seguras**
- Aplicar el patrón **cliente-servidor** con Node.js
- Explorar el uso de protocolos inspirados en FTP
- Desarrollar una interfaz web funcional para operaciones básicas

---

## 🧪 Mejoras sugeridas

- 🔄 Autogeneración de certificados con `openssl`
- 👤 Autenticación de usuarios
- 📦 Dockerización del proyecto
- ✅ Pruebas automatizadas

---

## 👨‍💻 Autor

**Gabriel Sánchez**\
📧 [gabrielsancabify@gmail.com]\
🎓 Trabajo práctico final – Tecnicatura en Desarrollo de Software

---

## 📄 Licencia

Este proyecto está licenciado bajo la **MIT License**.\
Consultá el archivo [`LICENSE`](./LICENSE) para más información.

---

¡Gracias por visitar este proyecto! Si te gustó, no olvides dejar una ⭐ en el repo 😉
