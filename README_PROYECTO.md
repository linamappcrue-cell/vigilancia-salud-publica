# 🏥 Sistema de Vigilancia en Salud Pública

Sistema web para vigilancia de eventos en salud pública desde laboratorios clínicos en Colombia.

## ✨ Características

✅ **Vigilancia en Tiempo Real**
- Registrar muestras y casos sospechosos
- Seguimiento automático de eventos

✅ **Parametrización Completa**
- Síntomas por evento (6 eventos: Dengue, COVID-19, TB, Malaria, Sarampión, Rabia)
- Tipos de muestra dinámicos
- Información técnica específica

✅ **Referencia a Laboratorio de Salud Pública**
- Flujo correcto de referencia
- No directo a INS (a través de Lab. SP)
- Control de contrarreferencia

✅ **100% Offline**
- Funciona sin internet
- Todos los datos en localStorage
- Perfecto para laboratorios remotos

✅ **Excel Descargable**
- 12 columnas completas
- Datos ordenados
- Listo para análisis

✅ **Interfaz Profesional**
- Responsive (móvil, tablet, desktop)
- Diseño moderno
- Fácil de usar

## 🚀 Inicio Rápido

### Credenciales de Demo

```
Usuario: LAB001
Contraseña: Lab@2024
```

### Otros Laboratorios

```
LAB002 / Lab@2024  → Laboratorio de Referencia Regional
LAB003 / Lab@2024  → Laboratorio Privado
```

## 📋 Módulos

1. **Dashboard** - Estadísticas en tiempo real
2. **Definiciones de Caso** - Criterios de sospecha y probabilidad
3. **Algoritmos Diagnósticos** - 5 pasos por evento
4. **Tipos de Muestras** - Especificaciones técnicas
5. **Registrar Muestra** - Formulario dinámico por evento
6. **Referencia y Contrarreferencia** - Flujo Lab. SP ↔ Laboratorio
7. **Normativa** - Documentos oficiales y leyes

## 🎯 Casos de Uso

### Para Laboratorios Clínicos
```
1. Reciben muestra
2. Abren aplicación
3. Registran datos
4. Seleccionan síntomas (dinámicos)
5. Registran tipos de muestra
6. Sistema sugiere referencia a Lab. SP si es necesario
7. Descargan Excel para enviar
```

### Para Coordinadores
```
1. Ven dashboard con estadísticas
2. Monitorizan eventos en tiempo real
3. Coordinan referencias
4. Analizan tendencias
```

## 🔧 Características Técnicas

- **Tecnología:** HTML5 + CSS3 + JavaScript
- **Almacenamiento:** localStorage
- **Responsividad:** Mobile-first
- **Compatibilidad:** Chrome, Firefox, Safari, Edge
- **Seguridad:** HTTPS automático (Vercel)
- **Escalabilidad:** CDN global

## 📦 Contenido del Proyecto

```
vigilancia-salud-publica/
├── index.html                  ← Aplicación principal
├── vercel.json                 ← Configuración Vercel
├── README.md                   ← Este archivo
└── .gitignore                  ← Archivos a ignorar
```

## 📊 Eventos Soportados

1. **Dengue**
   - Síntomas: Fiebre, Cefalea, Dolor retrorbitario, etc.
   - Muestras: Suero, Sangre EDTA
   - Tiempo respuesta: 5-7 días

2. **COVID-19**
   - Síntomas: Fiebre, Tos, Disnea, Pérdida olfato, etc.
   - Muestras: Hisopo Respiratorio
   - Tiempo respuesta: 3-5 días

3. **Tuberculosis**
   - Síntomas: Tos productiva, Hemoptisis, Fiebre, etc.
   - Muestras: Esputo (3 muestras)
   - Tiempo respuesta: 21-42 días

4. **Malaria**
   - Síntomas: Fiebre alta, Escalofríos, Sudoración, etc.
   - Muestras: Sangre EDTA, Laminillas
   - Tiempo respuesta: 5-7 días

5. **Sarampión/Rubéola**
   - Síntomas: Fiebre, Tos, Coriza, Conjuntivitis, Rash, etc.
   - Muestras: Suero, Hisopo, Orina
   - Tiempo respuesta: 7-10 días

6. **Rabia**
   - Síntomas: Fiebre, Cefalea, Hidrofobia, Espasmos, etc.
   - Muestras: Líquor, Suero, Hisopo
   - Tiempo respuesta: Urgente

## 🔐 Seguridad

✅ **HTTPS Automático** - Vercel proporciona certificado  
✅ **Sin Datos Sensibles** - Solo localStorage local  
✅ **Datos Privados** - Separados por laboratorio  
✅ **Validación** - Entrada validada en cliente  

## 📈 Versiones

**v2.2** - Julio 2024
- ✅ Síntomas parametrizados por evento
- ✅ Tipos de muestra parametrizados
- ✅ Referencia a Lab. de Salud Pública
- ✅ Síntomas registrados visibles
- ✅ Presentación mejorada

## 🤝 Contribuciones

Para reportar bugs o sugerir mejoras:

```
1. Fork el repositorio
2. Crea rama de feature
3. Haz commits descriptivos
4. Push a la rama
5. Abre Pull Request
```

## 📝 Licencia

MIT License - Libre para usar y modificar

## 📞 Contacto

**Email:** contacto@vigilancia-salud.co  
**Teléfono:** +57 (1) XXX-XXXX  
**Sitio:** https://vigilancia-salud-publica.vercel.app

## 📚 Documentación Adicional

- [Guía de Uso](GUIA_USO.md)
- [Algoritmos Diagnósticos](ALGORITMOS.md)
- [Normativa Aplicable](NORMATIVA.md)

---

## 🎓 Para Laboratorios Nuevos

### Cómo crear usuario nuevo

1. Contacta al administrador
2. Solicita credenciales de nuevo laboratorio
3. Se crea: LABXXX / contraseña
4. Los datos son privados por laboratorio

### Capacitación

```
Tiempo estimado: 30 minutos
Temas:
- Navegación de módulos
- Cómo registrar muestras
- Selección de síntomas y muestras
- Descarga de Excel
- Interpretación de resultados
```

---

## ✅ Verificación Rápida

1. ✅ Abre la app
2. ✅ Ingresa con LAB001/Lab@2024
3. ✅ Ve al Dashboard
4. ✅ Registra una muestra
5. ✅ Ve a "Ver Muestras"
6. ✅ Descarga Excel
7. ✅ ¡Funcionando!

---

**Sistema de Vigilancia en Salud Pública v2.2**  
*Para laboratorios de salud en Colombia*

Hecho con ❤️ para la salud pública

