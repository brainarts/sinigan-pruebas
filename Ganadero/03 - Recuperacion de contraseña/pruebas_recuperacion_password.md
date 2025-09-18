# Pruebas Atómicas - Recuperación de Contraseña

**Usuario:** _______________ | **Fecha:** _______________ | **Duración:** _____ min  
**Dispositivo:** _______________ | **Versión App:** _______________

---

## PRUEBA 1: Localización de Opción "Olvidé mi Contraseña"
**Funcionalidad:** Encontrar la opción de recuperación en pantalla de login

### Pasos a realizar:
1. Abrir la aplicación y llegar a pantalla de login
2. Buscar opción "Olvidé mi contraseña" o similar
3. Verificar que la opción es visible y clara
4. Hacer clic en la opción

### Resultado esperado:
La opción de recuperación de contraseña es fácil de encontrar en la pantalla de login

### Resultado obtenido:
□ **PASA** - Encuentra y accede a opción sin problemas  
□ **FALLA** - No encuentra la opción o no es clara  

**¿Dónde estaba ubicada la opción?** ________________________________  
**¿Texto de la opción era claro?** □ Sí □ No  
**Tiempo para encontrarla:** _____ segundos  
**Observaciones:** ________________________________

---

## PRUEBA 2: Acceso a Pantalla de Recuperación
**Funcionalidad:** Verificar transición a pantalla de recuperación de contraseña

### Pasos a realizar:
1. Después de hacer clic en "Olvidé mi contraseña"
2. Observar que aparece nueva pantalla
3. Verificar elementos de la pantalla de recuperación
4. Leer instrucciones si las hay

### Resultado esperado:
Aparece pantalla específica para recuperación con instrucciones claras

### Resultado obtenado:
□ **PASA** - Pantalla de recuperación carga correctamente  
□ **FALLA** - No aparece pantalla o es confusa  

**¿Transición fue fluida?** □ Sí □ No  
**¿Hay instrucciones claras?** □ Sí □ No  
**Elementos visibles:** ________________________________  
**Observaciones:** ________________________________

---

## PRUEBA 3: Identificación de Campo de Correo
**Funcionalidad:** Localizar campo para ingresar correo electrónico

### Pasos a realizar:
1. Identificar campo de correo electrónico en pantalla
2. Verificar que está claramente etiquetado
3. Observar botón de envío o confirmación
4. Leer cualquier texto explicativo

### Resultado esperado:
Campo de correo es claro y está bien etiquetado con botón de envío visible

### Resultado obtenido:
□ **PASA** - Campo claro y bien identificado  
□ **FALLA** - Campo confuso o mal etiquetado  

**¿Etiqueta del campo era clara?** □ Sí □ No  
**¿Hay texto explicativo?** □ Sí □ No  
**¿Botón de envío es visible?** □ Sí □ No  
**Observaciones:** ________________________________

---

## PRUEBA 4: Ingreso de Correo Electrónico
**Funcionalidad:** Introducir dirección de correo registrada

### Pasos a realizar:
1. Hacer clic en el campo de correo
2. Escribir dirección de correo registrada en el sistema
3. Verificar que el correo se ingresa correctamente
4. Confirmar formato correcto del email

### Resultado esperado:
Campo acepta el correo electrónico y lo muestra correctamente

### Resultado obtenido:
□ **PASA** - Correo se ingresa sin problemas  
□ **FALLA** - Problemas al ingresar correo  

**Correo ingresado:** ________________________________  
**¿Campo responde bien al teclado?** □ Sí □ No  
**¿Valida formato de email?** □ Sí □ No  
**Observaciones:** ________________________________

---

## PRUEBA 5: Envío de Solicitud de Recuperación
**Funcionalidad:** Enviar solicitud de recuperación al servidor

### Pasos a realizar:
1. Presionar botón de envío/confirmar
2. Observar respuesta del sistema
3. Verificar mensaje de confirmación
4. Anotar tiempo de respuesta

### Resultado esperado:
Sistema confirma que enviará correo con instrucciones si el email está registrado

### Resultado obtenido:
□ **PASA** - Envío exitoso con confirmación clara  
□ **FALLA** - Error en envío o mensaje confuso  

**¿Mostró mensaje de confirmación?** □ Sí □ No  
**Tiempo de respuesta:** _____ segundos  
**¿Mensaje era claro?** □ Sí □ No  
**Observaciones:** ________________________________

---

## PRUEBA 6: Verificación de Correo Recibido
**Funcionalidad:** Confirmar llegada de correo con instrucciones

### Pasos a realizar:
1. Revisar bandeja de entrada del correo ingresado
2. Buscar correo de recuperación de SINIGAN
3. Verificar remitente y asunto del correo
4. Abrir el correo recibido

### Resultado esperado:
Correo de recuperación llega en tiempo razonable con información clara

### Resultado obtenido:
□ **PASA** - Correo llega correctamente  
□ **FALLA** - Correo no llega o información incorrecta  

**¿Correo llegó?** □ Sí □ No  
**Tiempo de llegada:** _____ minutos  
**¿Verificar carpeta spam?** □ Sí □ No | **¿Estaba en spam?** □ Sí □ No  
**Remitente:** ________________________________  
**Observaciones:** ________________________________

---

## PRUEBA 7: Contenido y Claridad del Correo
**Funcionalidad:** Verificar que el correo contiene instrucciones claras

### Pasos a realizar:
1. Leer contenido completo del correo
2. Verificar que hay enlace para cambiar contraseña
3. Confirmar que instrucciones son claras
4. Localizar enlace principal

### Resultado esperado:
Correo contiene instrucciones claras y enlace funcional para cambiar contraseña

### Resultado obtenido:
□ **PASA** - Correo claro con enlace visible  
□ **FALLA** - Correo confuso o enlace no visible  

**¿Instrucciones eran claras?** □ Sí □ No  
**¿Enlace era fácil de identificar?** □ Sí □ No  
**¿Mencionaba pasos a seguir?** □ Sí □ No  
**Observaciones:** ________________________________

---

## PRUEBA 8: Acceso al Portal Web via Enlace
**Funcionalidad:** Hacer clic en enlace y acceder al portal web

### Pasos a realizar:
1. Hacer clic en el enlace del correo
2. Esperar que abra navegador web
3. Verificar que carga portal de cambio de contraseña
4. Confirmar que el código se reconoce automáticamente

### Resultado esperado:
Enlace abre portal web de SINIGAN para cambio de contraseña con código válido

### Resultado obtenido:
□ **PASA** - Portal web carga correctamente  
□ **FALLA** - Enlace no funciona o portal no carga  

**¿Abrió navegador automáticamente?** □ Sí □ No  
**¿Portal cargó rápidamente?** □ Sí □ No | **Tiempo:** _____ segundos  
**¿Código se reconoció automáticamente?** □ Sí □ No  
**Observaciones:** ________________________________

---

## PRUEBA 9: Interfaz del Portal Web
**Funcionalidad:** Verificar elementos del portal web de cambio de contraseña

### Pasos a realizar:
1. Observar diseño y elementos del portal web
2. Localizar campos para nueva contraseña
3. Verificar que hay confirmación de contraseña
4. Observar botón de aceptar/guardar

### Resultado esperado:
Portal web tiene interfaz clara con campos para nueva contraseña y confirmación

### Resultado obtenido:
□ **PASA** - Interfaz web clara y completa  
□ **FALLA** - Interfaz confusa o elementos faltantes  

**Elementos visibles:** □ Nueva contraseña □ Confirmar contraseña □ Botón guardar  
**¿Diseño coherente con la app?** □ Sí □ No  
**¿Instrucciones claras?** □ Sí □ No  
**Observaciones:** ________________________________

---

## PRUEBA 10: Ingreso de Nueva Contraseña
**Funcionalidad:** Escribir nueva contraseña en el portal web

### Pasos a realizar:
1. Hacer clic en campo "Nueva contraseña"
2. Escribir contraseña nueva y segura
3. Hacer clic en campo "Confirmar contraseña"
4. Escribir la misma contraseña para confirmar

### Resultado esperado:
Campos aceptan nueva contraseña y permiten confirmación correcta

### Resultado obtenido:
□ **PASA** - Campos funcionan correctamente  
□ **FALLA** - Problemas con campos o validación  

**¿Contraseña se oculta correctamente?** □ Sí □ No  
**¿Valida que coincidan las contraseñas?** □ Sí □ No  
**¿Hay requisitos de seguridad?** □ Sí □ No  
**Observaciones:** ________________________________

---

## PRUEBA 11: Confirmación de Cambio de Contraseña
**Funcionalidad:** Guardar nueva contraseña en el sistema

### Pasos a realizar:
1. Presionar botón "Aceptar" o "Guardar"
2. Esperar respuesta del sistema
3. Observar mensaje de confirmación
4. Verificar que proceso se completó

### Resultado esperado:
Sistema guarda nueva contraseña y confirma cambio exitoso

### Resultado obtenido:
□ **PASA** - Contraseña cambiada exitosamente  
□ **FALLA** - Error al guardar o proceso incompleto  

**¿Mostró confirmación de cambio?** □ Sí □ No  
**Tiempo de procesamiento:** _____ segundos  
**¿Mensaje de éxito era claro?** □ Sí □ No  
**Observaciones:** ________________________________

---

## PRUEBA 12: Retorno a la Aplicación Móvil
**Funcionalidad:** Volver a la app móvil para probar nueva contraseña

### Pasos a realizar:
1. Cerrar navegador web o regresar a app móvil
2. Ir a pantalla de login de SINIGAN
3. Verificar que está en pantalla de login limpia
4. Prepararse para probar nueva contraseña

### Resultado esperado:
Usuario puede regresar fácilmente a la aplicación móvil para hacer login

### Resultado obtenido:
□ **PASA** - Regreso a app móvil sin problemas  
□ **FALLA** - Dificultad para regresar a app  

**¿Cómo regresó a la app?** ________________________________  
**¿Pantalla de login estaba disponible?** □ Sí □ No  
**¿Campos estaban limpios?** □ Sí □ No  
**Observaciones:** ________________________________

---

## PRUEBA 13: Login con Nueva Contraseña
**Funcionalidad:** Probar login con contraseña recién cambiada

### Pasos a realizar:
1. Ingresar correo electrónico en campo correspondiente
2. Ingresar nueva contraseña recién creada
3. Presionar botón de login
4. Verificar que login es exitoso

### Resultado esperado:
Login funciona correctamente con la nueva contraseña

### Resultado obtenido:
□ **PASA** - Login exitoso con nueva contraseña  
□ **FALLA** - Login falla con nueva contraseña  

**¿Login fue inmediato?** □ Sí □ No  
**¿Tiempo de validación normal?** □ Sí □ No  
**¿Procedió a sincronización?** □ Sí □ No  
**Observaciones:** ________________________________

---

## PRUEBA 14: Validación de Contraseña Anterior
**Funcionalidad:** Confirmar que contraseña anterior ya no funciona

### Pasos a realizar:
1. Cerrar sesión o regresar a login
2. Intentar login con correo y contraseña ANTERIOR
3. Verificar que sistema rechaza contraseña vieja
4. Confirmar mensaje de error apropiado

### Resultado esperado:
Sistema rechaza contraseña anterior y solo acepta la nueva

### Resultado obtenido:
□ **PASA** - Contraseña anterior rechazada correctamente  
□ **FALLA** - Contraseña anterior aún funciona  

**¿Rechazó contraseña anterior?** □ Sí □ No  
**¿Mensaje de error apropiado?** □ Sí □ No  
**¿Seguridad funcionó correctamente?** □ Sí □ No  
**Observaciones:** ________________________________

---

## RESUMEN FINAL - RECUPERACIÓN DE CONTRASEÑA

**Total Pruebas Pasadas:** ___/14  
**Total Pruebas Falladas:** ___/14  
**Tiempo Total del Proceso:** _____ minutos

### Análisis por Secciones:
- **Inicio Recuperación (1-3):** ___/3 ✅
- **Solicitud por Email (4-5):** ___/2 ✅  
- **Recepción de Correo (6-7):** ___/2 ✅
- **Portal Web (8-11):** ___/4 ✅
- **Validación Final (12-14):** ___/3 ✅

### Puntos de Fricción Más Críticos:
1. ________________________________
2. ________________________________
3. ________________________________

### Validaciones de Seguridad que Funcionaron:
□ Solo emails registrados reciben instrucciones  
□ Enlace con código único funciona  
□ Contraseña anterior queda invalidada  
□ Nueva contraseña se valida correctamente  
□ Portal web es seguro  

### Aspectos de Comunicación:
□ Correo llega en tiempo razonable  
□ Instrucciones en correo son claras  
□ Portal web es intuitivo  
□ Mensajes de confirmación son claros  

### Experiencia Multi-Canal:
□ Transición app → correo → web → app es fluida  
□ Usuario entiende cada paso del proceso  
□ No se pierde en las transiciones  
□ Proceso general es lógico  

### ¿Completó exitosamente todo el proceso de recuperación?** □ Sí □ No

### Nivel de Dificultad del Proceso (1-5):
⭐ Muy Fácil | ⭐⭐ Fácil | ⭐⭐⭐ Normal | ⭐⭐⭐⭐ Difícil | ⭐⭐⭐⭐⭐ Muy Difícil

### ¿Proceso fue más complejo de lo esperado?** □ Sí □ No

### ¿Confiaría en usar esta funcionalidad cuando olvide su contraseña?** □ Sí □ No

**Comentarios finales del usuario:**
_________________________________________________
_________________________________________________
_________________________________________________

**Sugerencias para mejorar el proceso:**
1. ________________________________
2. ________________________________
3. ________________________________

---

**Notas Finales del Evaluador:**
_________________________________________________
_________________________________________________
_________________________________________________