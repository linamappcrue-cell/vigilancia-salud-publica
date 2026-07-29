# 🏥 Vigilancia en Salud Pública - Sistema EISP
## Aplicación Web para Laboratorios Clínicos de Colombia

---

## 📋 Descripción

Sistema web integral para **vigilancia en salud pública** basado en el protocolo **EISP (Eventos de Interés en Salud Pública)** del Instituto Nacional de Salud (INS) de Colombia.

Permite a laboratorios clínicos:
- 📊 Registrar muestras sospechosas de eventos de salud pública
- 🤖 Obtener asesoramiento automático con análisis de expertos (IA)
- 📋 Acceder a definiciones y criterios de caso
- 🔄 Consultar algoritmos diagnósticos
- 🧪 Conocer tipos de muestra requeridos
- ↔️ Gestionar referencia/contrarreferencia
- 📈 Monitorear estadísticas en tiempo real
- 📑 Consultar normativa vigente

---

## ✨ Características Principales

### 🎯 Módulos Disponibles

1. **🤖 Asesoramiento con IA**
   - Análisis automático de casos clínicos
   - Perspectivas de: Médico, Epidemiólogo, Infectólogo
   - Clasificación automática de casos
   - Recomendaciones de manejo

2. **📋 Definiciones**
   - Criterios diagnósticos OMS/INS
   - Definiciones de caso sospechoso, probable, confirmado
   - Protocolos oficiales

3. **🔄 Algoritmos**
   - Algoritmos diagnósticos por evento
   - Flujos de decisión clínica
   - Criterios de referencia

4. **🧪 Tipos de Muestra**
   - Muestras específicas por evento
   - Especificaciones técnicas
   - Procedimientos de recolección

5. **📝 Registrar Muestra**
   - Formulario completo de registro
   - Captura de síntomas y datos
   - Cálculo automático de edad
   - Validaciones en tiempo real

6. **📊 Dashboard**
   - Estadísticas en tiempo real
   - Gráficos de vigilancia
   - Contadores por evento
   - Últimas muestras registradas

7. **↔️ Referencia**
   - Flujo de referencia a Lab. Salud Pública
   - Contrarreferencia de resultados
   - Procesos de envío

8. **📑 Normativa**
   - Documentos oficiales
   - Resoluciones (Res. 1646/2013)
   - Organismos responsables
   - Marco legal

---

## 🚀 Despliegue

### En Netlify (Recomendado)

#### Opción A: Drag & Drop (2 minutos)
```bash
1. Ve a https://www.netlify.com
2. Sign Up (Email)
3. Arrastra index.html
4. ¡ONLINE!
```

#### Opción B: Git (5 minutos)
```bash
1. Ve a https://www.netlify.com
2. Sign Up → GitHub
3. Conecta repositorio
4. Deploy automático
```

### En el Navegador (Local)

```bash
1. Descarga: index.html
2. Doble click
3. Se abre en navegador
4. ¡Funciona!
```

---

## 🔐 Acceso

### Usuarios Demo

| Usuario | Contraseña | Laboratorio |
|---------|-----------|-------------|
| LAB001  | Lab@2024  | Laboratorio Central Bogotá |
| LAB002  | Lab@2024  | Laboratorio de Referencia Regional |
| LAB003  | Lab@2024  | Laboratorio Privado San José |

---

## 📦 Datos Precargados

Se incluyen **20 registros ficticios** de demostración:

- **Dengue**: 5 casos
- **COVID-19**: 4 casos
- **Tuberculosis**: 4 casos
- **Sarampión**: 4 casos
- **Malaria**: 3 casos

**Resultados:**
- Positivos: 15 (75%)
- Negativos: 3 (15%)
- Pendientes: 2 (10%)

---

## 💻 Tecnología

- **Frontend**: HTML5 + CSS3 + JavaScript
- **Almacenamiento**: LocalStorage (navegador)
- **Exportación**: XLSX (Excel)
- **Framework**: Vanilla JS (sin dependencias externas)
- **Compatibilidad**: Chrome, Firefox, Safari, Edge

---

## 📱 Características Técnicas

### Responsivo
- Desktop ✅
- Tablet ✅
- Mobile ✅

### Offline
- Funciona sin conexión ✅
- Datos se guardan localmente ✅
- Sincronización al conectar ✅

### Seguridad
- Autenticación por laboratorio ✅
- Separación de datos por usuario ✅
- Validación de formularios ✅

---

## 🎯 Eventos de Salud Pública Soportados

1. **Dengue**
   - Virus dengue (4 serotipos)
   - Transmisión: Aedes aegypti
   - Período incubación: 3-14 días

2. **COVID-19**
   - SARS-CoV-2
   - Transmisión: gotitas respiratorias
   - Período contagio: -2 a +10 días

3. **Tuberculosis**
   - Mycobacterium tuberculosis
   - Transmisión: aérea
   - Período latencia: 2-8 semanas

4. **Malaria**
   - Plasmodium spp.
   - Vector: mosquito Anopheles
   - Período incubación: 10-30 días

5. **Sarampión**
   - Virus del sarampión
   - Transmisión: aérea
   - Período contagio: -4 a +4 días rash

---

## 📊 Dashboard

Muestra en tiempo real:
- Total de muestras registradas
- Casos por resultado (positivo/negativo/pendiente)
- Casos por evento
- Casos referidos a laboratorio
- Últimas 5 muestras registradas
- Gráficos estadísticos

---

## 📥 Descargas

### Excel
Descarga todas las muestras en formato Excel con:
- ID de muestra
- Datos del paciente
- Síntomas
- Tipo de muestra
- Resultados
- Observaciones

---

## 🔄 Flujo de Trabajo

```
Paciente llega
    ↓
🤖 Asesoramiento IA (¿Qué puede ser?)
    ↓
📋 Definiciones (¿Qué es?)
    ↓
🔄 Algoritmos (¿Cómo identificar?)
    ↓
🧪 Muestras (¿Qué recolectar?)
    ↓
📝 Registrar (Documentar)
    ↓
📊 Dashboard (Ver resultados)
    ↓
↔️ Referencia (Enviar a laboratorio)
    ↓
📑 Normativa (Verificar requisitos)
```

---

## 🆘 Solución de Problemas

### Datos no aparecen
```javascript
// Abre consola (F12) y ejecuta:
localStorage.clear()
// Recarga la página
```

### Contraseña olvidada
Ver tabla de acceso arriba (usuarios demo)

### App no carga
- Recarga sin caché: Ctrl+Shift+R
- Verifica que sea HTML válido

---

## 📝 Licencia

MIT License - Libre para uso y distribución

---

## 👨‍💼 Autor

Desarrollado para vigilancia en salud pública en Colombia

---

## 🔗 Links Útiles

- **INS Colombia**: https://www.ins.gov.co
- **Ministerio de Salud**: https://www.minsalud.gov.co
- **EISP**: Eventos de Interés en Salud Pública
- **Resolución 1646/2013**: Protocolo de vigilancia

---

## 📧 Contacto

Para problemas o sugerencias, contacta al equipo de desarrollo

---

## 📋 Cambios Recientes (v2.2)

### ✨ Nuevas Características
- ✅ Módulo IA con análisis de expertos
- ✅ 3 perspectivas: Médico, Epidemiólogo, Infectólogo
- ✅ Clasificación automática de casos
- ✅ Historial de análisis
- ✅ Sidebar reorganizado lógicamente

### 🔧 Mejoras
- ✅ Interface optimizada
- ✅ Mejor flujo de trabajo
- ✅ Datos ficticios completos (20 registros)
- ✅ Documentación mejorada

### 🐛 Correcciones
- ✅ Validaciones de formularios
- ✅ Manejo de errores
- ✅ Compatibilidad móvil

---

## 📊 Estadísticas

- **Módulos**: 9
- **Eventos**: 5+ (dengue, COVID, TB, malaria, sarampión)
- **Usuarios demo**: 3
- **Datos ficticios**: 20 registros
- **Tamaño**: 122 KB
- **Líneas código**: 2500+

---

## 🎓 Uso Educativo

Perfecto para:
- Capacitación de personal
- Demostraciones
- Investigación
- Desarrollo de prototipos
- Enseñanza

---

## 🚀 Versión

**v2.2** - Junio 2024

- Módulo IA integrado
- Sidebar reorganizado
- 20 datos ficticios
- Documentación completa
- Listo para producción

---

## ✅ Estado

🟢 **Completamente Funcional**
- ✅ Todos los módulos operativos
- ✅ Datos ficticios cargados
- ✅ IA respondiendo
- ✅ Exportación Excel funcional
- ✅ Sistema de referencia activo
- ✅ Dashboard actualizado

---

**Última actualización:** Julio 2024
**Desarrollado para:** Vigilancia en Salud Pública - Colombia
**Marco normativo:** EISP - INS

