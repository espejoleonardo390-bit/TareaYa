# TareaYa# 🧩 TareaYa — Plataforma de microtrabajos y proveedores locales 🇨🇴

**TareaYa** es una plataforma creada en Colombia para conectar **clientes**, **trabajadores independientes** y **proveedores de materiales y repuestos**.  
Nace en Medellín como proyecto piloto, con el propósito de dinamizar el empleo local y facilitar el acceso a servicios rápidos, seguros y cercanos.

---

## 🚀 Características principales

### 👥 Para clientes
- Publica tareas locales (limpieza, pintura, plomería, mensajería, etc.)
- Paga con **Nequi, Daviplata o tarjeta** directamente desde la app.
- Califica y guarda tus trabajadores favoritos.

### 👷 Para trabajadores
- Acepta tareas disponibles cerca de tu ubicación.
- Cobra de forma segura y recibe notificaciones de pago.
- Accede a descuentos en materiales mediante el módulo **TareaYa Proveedores**.

### 🏬 Para proveedores
- Registra tu negocio (ferreterías, tiendas de limpieza, eléctricos, repuestos).
- Gestiona catálogo, precios y entregas locales.
- Recibe pedidos automáticos de trabajadores y clientes.

---

## 🛠️ Estructura del proyecto
tareaya_backend/
├── src/
│ ├── routes/
│ │ ├── tasks.js
│ │ ├── users.js
│ │ ├── providers.js
│ │ └── payments.js
│ ├── db/
│ │ ├── schema.sql
│ │ └── seed.sql
│ ├── app.js
│ ├── server.js
│ └── config/
│ └── db.js
├── .env.example
├── package.json
├── README.md

### 🧩 Tecnologías utilizadas
- Node.js + Express.js  
- PostgreSQL (configurable a MySQL)  
- JWT para autenticación  
- Multer y Cloudinary para imágenes  
- CORS y Helmet para seguridad  
- Frontend en **Figma** (assets incluidos)

---

## ⚙️ Instrucciones de instalación

```bash
# 1. Clonar el repositorio
git clone https://github.com/espejoleonardo390-bit/TareaYa.git
cd TareaYa/tareaya_backend

# 2. Instalar dependencias
npm install

# 3. Configurar variables de entorno
cp .env.example .env
# Edita las variables DATABASE_URL, JWT_SECRET y API_KEYS si aplica

# 4. Ejecutar el servidor en desarrollo
npm run dev

