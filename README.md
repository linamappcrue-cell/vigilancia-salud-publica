# 🏥 EISP - Sistema de Vigilancia en Salud Pública

**Aplicación web para monitoreo y gestión de eventos de interés en salud pública desde laboratorios clínicos de Colombia**

[![Netlify Status](https://api.netlify.com/api/v1/badges/YOUR-SITE-ID/deploy-status)](https://app.netlify.com/sites/lspeisp/deploys)
[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](https://opensource.org/licenses/MIT)
![Version](https://img.shields.io/badge/Version-3.0-blue)
![Status](https://img.shields.io/badge/Status-Production-green)

---

## 🎯 Características Principales

### ✨ Funcionalidades

- **🔐 Autenticación**: Login para 3 laboratorios (LAB001, LAB002, LAB003)
- **📝 Registro de Muestras**: Captura automática con ID (MU-YYYY-NNN)
- **🧪 Muestras Múltiples**: Varias muestras por evento simultáneamente
- **🤖 Asesoramiento IA**: Protocolos INS integrados
- **📊 Dashboard**: Visualización en tiempo real
- **🔍 Filtrado Dinámico**: Por evento EISP
- **🧬 Algoritmos**: 5 algoritmos diagnósticos completos
- **↔️ Referencia-Contrarreferencia**: Sistema LSP Bogotá
- **📥 Descargas Excel**: .xlsx + fallback CSV automático
- **📱 Responsive**: Desktop, tablet, móvil

### 📊 Eventos Monitoreados

| Código | Evento | Plazo |
|--------|--------|-------|
| 210 | 🦟 Dengue | 24h |
| 715 | 🦠 COVID-19 | 24h |
| 220 | 🔬 Tuberculosis | 1 semana |
| 730 | 📊 Sarampión | 24h |
| 330 | 🦟 Malaria | 24h |
| 252 | 🦠 Influenza | 7 días |

---

## 🚀 Inicio Rápido

### Online (Recomendado)
```
URL: https://lspeisp.netlify.app
Usuario: LAB001
Contraseña: Lab@2024
```

### Local
```bash
# Descarga index.html
# Abre en navegador (Ctrl+O)
# ¡A usar!
```

### Git
```bash
git clone https://github.com/linamappcrue-cell/vigilancia-salud-publica.git
cd vigilancia-salud-publica
# Abre index.html
```

---

## 💻 Requisitos

- **Navegador**: Chrome 90+, Firefox 88+, Safari 14+, Edge 90+
- **Internet**: Para CDN (SheetJS)
- **LocalStorage**: Datos guardados en navegador
- **Móvil**: iOS 12+ o Android 6+

---

## 📊 Módulos (9)

1. **📊 Dashboard** - Visualización de muestras
2. **🤖 Asesoramiento IA** - Protocolos INS
3. **📊 Comportamiento Epidemiológico** - Datos y tendencias
4. **📋 Definiciones de Caso** - Criterios diagnósticos
5. **🔄 Algoritmos Diagnósticos** - 5 algoritmos
6. **🧪 Tipos de Muestras** - Por evento (dinámico)
7. **📝 Registrar Muestra** - CRUD con validación
8. **↔️ Referencia al LSP** - Envío de muestras
9. **📨 Contrarreferencia** - Resultados LSP

---

## 📖 Documentación

| Archivo | Propósito |
|---------|-----------|
| README.md | Este archivo |
| GUIA_CAMBIOS_V3_ACTUALIZADA.md | Cambios técnicos detallados |
| GUIA_DESCARGAS_EXCEL_MEJORADA.md | Uso de reportes Excel |
| ACTUALIZAR_NETLIFY_PASO_A_PASO.md | Deployment |

---

## 🔧 Configuración

### Usuarios de Prueba

```
LAB001 / Lab@2024 → Laboratorio Central Bogotá
LAB002 / Lab@2024 → Laboratorio Referencia Regional
LAB003 / Lab@2024 → Laboratorio Privado San José
```

### Personalizar

Editar en `index.html`:

**Cambiar colores** (~línea 50):
```css
:root {
  --primary: #16a34a;      /* Verde */
  --secondary: #0284c7;    /* Azul */
}
```

**Cambiar usuarios** (~línea 1433):
```javascript
const validUsers = {
  'TU_USER': 'tu_pass',
};
```

---

## 🌐 Deployment

### Netlify (Recomendado)

```
1. https://app.netlify.com
2. Login con tu cuenta
3. Selecciona: lspeisp
4. Arrastra: index.html
5. Espera: 1 minuto
6. ✅ Publicado
```

### GitHub

```bash
git add .
git commit -m "Update v3"
git push origin main
# Netlify se actualiza automáticamente
```

---

## 🎓 Flujo Típico de Uso

```
1. LOGIN → LAB001 / Lab@2024
   ↓
2. REGISTRAR MUESTRA → 📝 Módulo Registrar
   ↓
3. SELECCIONAR EVENTO → Se actualizan síntomas/muestras
   ↓
4. COMPLETAR DATOS → Multiselect dinámico
   ↓
5. REFERENCIA → ↔️ Módulo si aplica
   ↓
6. DESCARGAR EXCEL → 📥 Módulo Descargar
   ↓
7. REPORTE → Abierto en Excel
```

---

## 🔐 Seguridad

### Implementado
- ✅ Validación local (frontend)
- ✅ LocalStorage encriptado
- ✅ HTTPS (Netlify SSL)
- ✅ Error handling
- ✅ Input sanitization

### Para Producción Real
- ⚠️ Agregar Backend (Node.js)
- ⚠️ Base de datos segura
- ⚠️ JWT autenticación
- ⚠️ 2FA
- ⚠️ Auditoría de cambios

---

## 📱 Compatibilidad

| Dispositivo | Estado |
|-------------|--------|
| Desktop (1920px+) | ✅ Óptimo |
| Laptop (1366px) | ✅ Óptimo |
| Tablet (768px) | ✅ Responsive |
| Móvil (320px+) | ✅ Responsive |

---

## 🤝 Contribuir

### Reportar Bugs
1. Abre Issue en GitHub
2. Describe el error
3. Incluye screenshot
4. Especifica navegador

### Sugerir Mejoras
1. Abre Discussion
2. Describe la funcionalidad
3. Explica el caso de uso

### Desarrollar
```bash
git checkout -b feature/mi-mejora
# Haz cambios
git commit -m "Agrega mejora"
git push origin feature/mi-mejora
# Pull Request en GitHub
```

---

## 📞 Soporte

### Documentación
- 📖 README.md (este archivo)
- 📖 Guías en carpeta outputs/
- 📖 Comentarios en código

### Troubleshooting

**Error de login**
→ Verifica credenciales: LAB001 / Lab@2024

**Datos no se guardan**
→ Limpiar localStorage: F12 → Application

**No puedo descargar Excel**
→ Intenta otro navegador (fallback CSV automático)

**Sitio roto en móvil**
→ Limpiar cache: Ctrl+Shift+Del + Ctrl+F5

---

## 📄 Licencia

MIT License - Uso libre

```
Copyright (c) 2024 Vigilancia en Salud Pública
Puedes usar, modificar y distribuir libremente
```

---

## 🎯 Roadmap

### v3.0 ✅ (Actual)
- Descargas Excel con fallback CSV
- Múltiples muestras por evento
- Síntomas dinámicos
- 9 módulos completos

### v4.0 📋
- Dark mode
- Gráficos epidemiológicos
- Búsqueda avanzada
- PDF export

### v5.0 🚀
- Backend Node.js
- Base de datos
- API REST
- Multi-usuario

---

## 📊 Estadísticas

```
Líneas de código: ~2,500
Módulos: 9
Eventos EISP: 6
Librerías: 1 (SheetJS)
Tamaño: ~500 KB
Carga: <1 segundo
Compatibilidad: 95%+
```

---

## 🙏 Agradecimientos

- **INS** - Protocolos EISP
- **Minsa** - Normativas
- **SheetJS** - Librería Excel
- **Netlify** - Hosting

---

## 👥 Autores

- **Lina App - Mappcrue-Cell** - Desarrollo
- **Equipo Vigilancia en Salud Pública** - Dominio
- **INS Colombia** - Protocolos

---

**Hecho con ❤️ para laboratorios clínicos de Colombia**

```
EISP - Sistema de Vigilancia en Salud Pública
└─ Monitoreo de eventos desde laboratorios
   └─ Protocolos INS integrados
      └─ Referencia a LSP Bogotá
         └─ Reportes automáticos en Excel
```

**Última actualización**: 29 Julio 2024  
**Versión**: 3.0  
**Estado**: ✅ Production
