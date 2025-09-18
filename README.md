# SINIGAN - Scripts de Pruebas de Usuario

## 📋 Reporte de Hallazgos

**Los hallazgos y problemas identificados durante las pruebas deben documentarse en la mesa de ayuda:**  
🔗 **[https://brainarts.atlassian.net/servicedesk/customer/portal/4](https://brainarts.atlassian.net/servicedesk/customer/portal/4)**

## 📱 Acerca de SINIGAN

SINIGAN es el Sistema Nacional de Identificación e Información del Ganado Bovino en Colombia, una plataforma digital que centraliza y facilita trámites para ganaderos y comerciantes del sector pecuario. Permite realizar gestiones como la expedición de Guías Sanitarias de Movilización Interna (GSMI), registro de animales y hierros, y el seguimiento de la trazabilidad integral del ganado.

Este repositorio contiene scripts de pruebas atómicas diseñados para evaluar la experiencia de usuario en las funcionalidades principales del sistema.

## 🎯 Objetivo de las Pruebas

Las pruebas están diseñadas para:
- **Validar la usabilidad** de los flujos principales
- **Identificar puntos de fricción** en la experiencia de usuario
- **Verificar funcionalidades críticas** del negocio ganadero
- **Medir tiempos** de ejecución de procesos
- **Detectar errores** antes del lanzamiento

## 🚀 Cómo Usar los Scripts

### Preparación
1. **Dispositivo móvil** con SINIGAN instalado
2. **Datos de prueba** preparados:
   - Email de prueba funcional
   - Documento de identidad real
   - Datos de transportistas registrados
   - Cédulas de comerciantes registrados

### Ejecución
1. **Selecciona el script** apropiado para tu prueba
2. **Imprime el documento** o ten acceso digital
3. **Sigue cada prueba paso a paso**
4. **Marca ✅ PASA o ❌ FALLA** para cada validación
5. **Anota observaciones** detalladas
6. **Cronometra el proceso** completo

### Resultados
- **Métricas cuantitativas:** Pruebas pasadas/falladas, tiempos
- **Retroalimentación cualitativa:** Comentarios del usuario
- **Puntos de fricción:** Problemas identificados
- **Sugerencias de mejora:** Recomendaciones del usuario

## 🎯 Perfil de Usuarios de Prueba

### Usuario Ideal
- **Ganaderos** o personas familiarizadas con el sector
- **Experiencia móvil** básica a intermedia
- **Disponibilidad** de 30-45 minutos por sesión
- **Acceso** a datos reales para pruebas

### Consideraciones
- Usuarios con **diferentes niveles técnicos**
- Pruebas en **dispositivos variados** (Android/iOS)
- **Conexiones de internet** diferentes
- **Horarios diversos** para detectar problemas de servidor

## 📝 Reportes y Documentación

### Información a Recopilar
- **Datos demográficos** del usuario
- **Dispositivo** y versión de app utilizada
- **Resultados** de cada prueba
- **Observaciones** textuales
- **Sugerencias** de mejora

## 🔧 Troubleshooting

### Problemas Comunes
- **No llega código de verificación:** Revisar carpeta spam
- **Cámara no funciona:** Verificar permisos de la app
- **App muy lenta:** Revisar conexión a internet
- **Datos no cargan:** Verificar conectividad de servidor

---

## 📄 Licencia

Este repositorio contiene material interno para pruebas de usabilidad de SINIGAN. 

**Confidencial - Solo para uso interno del equipo de desarrollo.**
