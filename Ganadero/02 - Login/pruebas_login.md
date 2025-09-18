# Pruebas Atómicas - Login de Usuario

**Usuario:** _______________ | **Fecha:** _______________ | **Duración:** _____ min  
**Dispositivo:** _______________ | **Versión App:** _______________

---

## PRUEBA 1: Pantalla de Login al Iniciar
**Funcionalidad:** Verificar que la pantalla de login aparece al abrir la aplicación

### Pasos a realizar:
1. Abrir la aplicación SINIGAN
2. Observar que la pantalla de login se muestra automáticamente
3. Verificar elementos visibles en pantalla

### Resultado esperado:
La aplicación abre directamente en la pantalla de login con todos los elementos necesarios

### Resultado obtenido:
□ **PASA** - Pantalla de login aparece correctamente  
□ **FALLA** - No aparece login o pantalla incorrecta  

**Elementos visibles:** □ Campo correo □ Campo contraseña □ Botón login □ Opción registro  
**¿Tiempo de carga aceptable?** □ Sí □ No | **Tiempo:** _____ segundos  
**Observaciones:** ________________________________

---

## PRUEBA 2: Identificación de Campos de Login
**Funcionalidad:** Localizar y reconocer campos de correo y contraseña

### Pasos a realizar:
1. Identificar campo para correo electrónico
2. Identificar campo para contraseña
3. Verificar que los campos están claramente etiquetados
4. Observar botón de login

### Resultado esperado:
Los campos de correo y contraseña son fáciles de identificar y están bien etiquetados

### Resultado obtenido:
□ **PASA** - Campos claros y bien identificados  
□ **FALLA** - Campos confusos o mal etiquetados  

**¿Etiquetas de campos son claras?** □ Sí □ No  
**¿Botón de login es visible?** □ Sí □ No  
**¿Hay opción "¿No tienes cuenta?"** □ Sí □ No  
**Observaciones:** ________________________________

---

## PRUEBA 3: Ingreso de Correo Electrónico
**Funcionalidad:** Introducir dirección de correo en el campo correspondiente

### Pasos a realizar:
1. Hacer clic en el campo de correo electrónico
2. Escribir dirección de correo válida registrada
3. Verificar que el texto se ingresa correctamente
4. Observar comportamiento del campo

### Resultado esperado:
El campo acepta el correo electrónico y lo muestra correctamente

### Resultado obtenido:
□ **PASA** - Campo funciona correctamente  
□ **FALLA** - Problemas al ingresar correo  

**Correo ingresado:** ________________________________  
**¿Campo responde bien al teclado?** □ Sí □ No  
**¿Formato de email se valida?** □ Sí □ No  
**Observaciones:** ________________________________

---

## PRUEBA 4: Ingreso de Contraseña
**Funcionalidad:** Introducir contraseña en el campo correspondiente

### Pasos a realizar:
1. Hacer clic en el campo de contraseña
2. Escribir contraseña correcta
3. Verificar que la contraseña se oculta (asteriscos/puntos)
4. Observar si hay opción para mostrar/ocultar contraseña

### Resultado esperado:
El campo acepta la contraseña, la oculta por seguridad, y funciona correctamente

### Resultado obtenido:
□ **PASA** - Campo de contraseña funciona correctamente  
□ **FALLA** - Problemas con campo de contraseña  

**¿Contraseña se oculta correctamente?** □ Sí □ No  
**¿Hay opción mostrar/ocultar?** □ Sí □ No  
**¿Campo responde bien al teclado?** □ Sí □ No  
**Observaciones:** ________________________________

---

## PRUEBA 5: Validación con Datos Incorrectos
**Funcionalidad:** Probar login con credenciales incorrectas

### Pasos a realizar:
1. Ingresar correo incorrecto o contraseña incorrecta
2. Presionar botón de login
3. Observar mensaje de error
4. Verificar que no permite acceso

### Resultado esperado:
Sistema muestra mensaje de error claro y no permite acceso con credenciales incorrectas

### Resultado obtenido:
□ **PASA** - Valida credenciales y muestra error apropiado  
□ **FALLA** - No valida o mensaje de error confuso  

**¿Mostró mensaje de error?** □ Sí □ No  
**¿Mensaje de error era claro?** □ Sí □ No  
**Tipo de error probado:** □ Email incorrecto □ Contraseña incorrecta  
**Observaciones:** ________________________________

---

## PRUEBA 6: Login Exitoso con Credenciales Correctas
**Funcionalidad:** Realizar login con correo y contraseña correctos

### Pasos a realizar:
1. Limpiar campos si tienen datos incorrectos
2. Ingresar correo correcto registrado
3. Ingresar contraseña correcta
4. Presionar botón de login
5. Observar respuesta del sistema

### Resultado esperado:
Sistema valida credenciales correctas y procede al siguiente paso

### Resultado obtenido:
□ **PASA** - Login exitoso, avanza al siguiente paso  
□ **FALLA** - Error con credenciales correctas  

**¿Tiempo de validación aceptable?** □ Sí □ No | **Tiempo:** _____ segundos  
**¿Mostró confirmación de login exitoso?** □ Sí □ No  
**Observaciones:** ________________________________

---

## PRUEBA 7: Transición a Pantalla de Sincronización
**Funcionalidad:** Verificar que después del login exitoso aparece pantalla de sincronización

### Pasos a realizar:
1. Después del login exitoso, observar siguiente pantalla
2. Verificar que aparece pantalla de sincronización
3. Confirmar que es similar a la del registro
4. Observar elementos de la pantalla

### Resultado esperado:
Aparece pantalla de sincronización automáticamente después del login exitoso

### Resultado obtenido:
□ **PASA** - Transición correcta a sincronización  
□ **FALLA** - No aparece sincronización o pantalla incorrecta  

**¿Transición fue fluida?** □ Sí □ No  
**¿Pantalla similar a la del registro?** □ Sí □ No  
**Elementos visibles:** ________________________________  
**Observaciones:** ________________________________

---

## PRUEBA 8: Proceso de Sincronización de Datos
**Funcionalidad:** Completar descarga de datos de la nube al dispositivo

### Pasos a realizar:
1. Observar inicio del proceso de sincronización
2. Esperar durante la descarga de datos
3. Verificar indicadores de progreso
4. Confirmar finalización de sincronización

### Resultado esperado:
- Proceso de sincronización es visible y claro
- Muestra progreso de descarga
- Se completa exitosamente

### Resultado obtenido:
□ **PASA** - Sincronización completa exitosamente  
□ **FALLA** - Error en sincronización o proceso confuso  

**¿Mostró progreso de sincronización?** □ Sí □ No  
**Tiempo de sincronización:** _____ minutos  
**¿Indicó qué datos se estaban descargando?** □ Sí □ No  
**Observaciones:** ________________________________

---

## PRUEBA 9: Finalización de Sincronización
**Funcionalidad:** Verificar que la sincronización termina correctamente

### Pasos a realizar:
1. Esperar a que termine la sincronización
2. Observar mensaje de finalización
3. Verificar acceso a funcionalidades principales
4. Confirmar que datos están disponibles

### Resultado esperado:
- Sincronización termina con confirmación clara
- Usuario puede acceder a funcionalidades principales
- Datos están disponibles localmente

### Resultado obtenido:
□ **PASA** - Sincronización termina correctamente  
□ **FALLA** - No termina o no da acceso a funcionalidades  

**¿Mostró confirmación de finalización?** □ Sí □ No  
**¿Puede acceder a funcionalidades?** □ Sí □ No  
**¿Datos parecen estar disponibles?** □ Sí □ No  
**Observaciones:** ________________________________

---

## PRUEBA 10: Acceso a Aplicación Principal
**Funcionalidad:** Verificar acceso completo a la aplicación después del login

### Pasos a realizar:
1. Intentar navegar por las funcionalidades principales
2. Verificar que menús y opciones están disponibles
3. Confirmar que el usuario está logueado
4. Probar acceso a una funcionalidad básica

### Resultado esperado:
Usuario tiene acceso completo a todas las funcionalidades de la aplicación

### Resultado obtenido:
□ **PASA** - Acceso completo a la aplicación  
□ **FALLA** - Acceso limitado o funcionalidades no disponibles  

**¿Menús principales disponibles?** □ Sí □ No  
**¿Se ve información del usuario logueado?** □ Sí □ No  
**¿Puede acceder a crear guías?** □ Sí □ No  
**Observaciones:** ________________________________

---

## RESUMEN FINAL - LOGIN DE USUARIO

**Total Pruebas Pasadas:** ___/10  
**Total Pruebas Falladas:** ___/10  
**Tiempo Total del Proceso:** _____ minutos

### Análisis por Secciones:
- **Pantalla de Login (1-2):** ___/2 ✅
- **Ingreso de Credenciales (3-4):** ___/2 ✅  
- **Validación y Login (5-6):** ___/2 ✅
- **Sincronización (7-9):** ___/3 ✅
- **Acceso a App (10):** ___/1 ✅

### Puntos de Fricción Más Críticos:
1. ________________________________
2. ________________________________
3. ________________________________

### Validaciones de Seguridad que Funcionaron:
□ Credenciales incorrectas son rechazadas  
□ Contraseña se oculta correctamente  
□ Mensajes de error son claros  
□ No hay acceso sin login exitoso  

### Aspectos de Sincronización:
□ Sincronización inicia automáticamente  
□ Progreso es visible para el usuario  
□ Tiempo de sincronización es aceptable  
□ Datos quedan disponibles localmente  

### Experiencia General:
□ Proceso de login es intuitivo  
□ Transiciones son fluidas  
□ Tiempo total es aceptable  
□ Usuario entiende cada paso  

### ¿Completó exitosamente todo el proceso de login?** □ Sí □ No

### Nivel de Dificultad del Login (1-5):
⭐ Muy Fácil | ⭐⭐ Fácil | ⭐⭐⭐ Normal | ⭐⭐⭐⭐ Difícil | ⭐⭐⭐⭐⭐ Muy Difícil

### ¿Proceso es similar al registro en cuanto a sincronización?** □ Sí □ No

### ¿Usaría la aplicación regularmente después de este login?** □ Sí □ No □ Tal vez

**Comentarios finales del usuario:**
_________________________________________________
_________________________________________________
_________________________________________________

**Problemas más significativos encontrados:**
1. ________________________________
2. ________________________________
3. ________________________________

---

**Notas Finales del Evaluador:**
_________________________________________________
_________________________________________________
_________________________________________________