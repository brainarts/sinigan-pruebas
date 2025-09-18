# Pruebas Atómicas - Realización de Pagos PSE

**Usuario:** _______________ | **Fecha:** _______________ | **Duración:** _____ min  
**Dispositivo:** _______________ | **Versión App:** _______________

---

## PRUEBA 1: Preparación del Carrito para Pago
**Funcionalidad:** Tener ítems listos en el carrito para proceder al pago

### Pasos a realizar:
1. Verificar que hay ítems en el carrito de compras
2. Revisar que totales están calculados correctamente
3. Confirmar que todos los ítems están listos para pagar
4. Localizar botón "Siguiente" o "Proceder al pago"

### Resultado esperado:
Carrito tiene ítems y está listo para proceder al proceso de pago

### Resultado obtenido:
□ **PASA** - Carrito listo con ítems y totales correctos  
□ **FALLA** - Carrito vacío o problemas con ítems  

**Cantidad de ítems en carrito:** _____ ítems  
**Total a pagar:** $ ________________________________  
**¿Botón "Siguiente" visible?** □ Sí □ No  
**Observaciones:** ________________________________

---

## PRUEBA 2: Transición a Página Web de Pago
**Funcionalidad:** Presionar "Siguiente" y acceder a portal web de pagos

### Pasos a realizar:
1. Presionar botón "Siguiente" desde el carrito
2. Esperar que abra navegador web
3. Verificar que carga página web de pagos
4. Observar diseño y elementos de la página

### Resultado esperado:
Se abre navegador web automáticamente con página de pagos de SINIGAN

### Resultado obtenido:
□ **PASA** - Portal web de pagos carga correctamente  
□ **FALLA** - No abre web o portal no carga  

**¿Abrió navegador automáticamente?** □ Sí □ No  
**¿Página cargó rápidamente?** □ Sí □ No | **Tiempo:** _____ segundos  
**¿Diseño coherente con la app?** □ Sí □ No  
**Observaciones:** ________________________________

---

## PRUEBA 3: Verificación de Ítems en Portal Web
**Funcionalidad:** Confirmar que ítems del carrito aparecen correctamente en web

### Pasos a realizar:
1. Revisar lista de ítems mostrados en portal web
2. Comparar con ítems que había en el carrito móvil
3. Verificar cantidades, precios y totales
4. Confirmar que información coincide

### Resultado esperado:
Todos los ítems del carrito móvil aparecen correctamente en portal web

### Resultado obtenido:
□ **PASA** - Ítems coinciden exactamente con el carrito  
□ **FALLA** - Ítems faltantes, diferentes o errores  

**¿Todos los ítems aparecen?** □ Sí □ No  
**¿Precios coinciden?** □ Sí □ No  
**¿Total es el mismo?** □ Sí □ No  
**¿Información es clara?** □ Sí □ No  
**Observaciones:** ________________________________

---

## PRUEBA 4: Acceso al Proceso de Pago
**Funcionalidad:** Presionar botón "Pagar" e iniciar proceso de pago

### Pasos a realizar:
1. Localizar botón "Pagar" en portal web
2. Presionar el botón para iniciar pago
3. Esperar que aparezca ventana de verificación
4. Observar nueva interfaz de métodos de pago

### Resultado esperado:
Aparece ventana de verificación con opciones de métodos de pago

### Resultado obtenido:
□ **PASA** - Ventana de pago aparece correctamente  
□ **FALLA** - No aparece ventana o hay errores  

**¿Botón "Pagar" era claro?** □ Sí □ No  
**¿Ventana de verificación apareció?** □ Sí □ No  
**¿Tiempo de respuesta aceptable?** □ Sí □ No | **Tiempo:** _____ segundos  
**Observaciones:** ________________________________

---

## PRUEBA 5: Selección de Método de Pago PSE
**Funcionalidad:** Seleccionar PSE como método de pago

### Pasos a realizar:
1. Revisar métodos de pago disponibles
2. Localizar opción "PSE"
3. Seleccionar PSE como método de pago
4. Confirmar selección

### Resultado esperado:
PSE está disponible como opción y se puede seleccionar fácilmente

### Resultado obtenido:
□ **PASA** - PSE disponible y selección exitosa  
□ **FALLA** - PSE no disponible o error en selección  

**Métodos de pago disponibles:** ________________________________  
**¿PSE era fácil de identificar?** □ Sí □ No  
**¿Había otros métodos disponibles?** □ Sí □ No ¿Cuáles? ____________  
**Observaciones:** ________________________________

---

## PRUEBA 6: Pantalla de Confirmación de Datos del Pagador
**Funcionalidad:** Verificar datos del pagador en PSE

### Pasos a realizar:
1. Revisar pantalla que aparece después de seleccionar PSE
2. Verificar datos del pagador mostrados
3. Confirmar que datos son correctos
4. Proceder según las instrucciones

### Resultado esperado:
Pantalla muestra datos del pagador claramente para confirmación

### Resultado obtenido:
□ **PASA** - Datos del pagador correctos y claros  
□ **FALLA** - Datos incorrectos, faltantes o confusos  

**¿Datos del pagador eran correctos?** □ Sí □ No  
**¿Información era clara?** □ Sí □ No  
**¿Había opción para corregir datos?** □ Sí □ No  
**Observaciones:** ________________________________

---

## PRUEBA 7: Selección del Banco (Banco Unión Colombiano)
**Funcionalidad:** Seguir instrucciones para seleccionar banco y proceder

### Pasos a realizar:
1. Seguir instrucciones del documento anexo
2. Seleccionar "Banco Unión Colombiano" de la lista
3. Proceder con las instrucciones específicas
4. Llegar a opciones de simulación de pago

### Resultado esperado:
Proceso sigue las instrucciones del documento y llega a opciones de pago

### Resultado obtenido:
□ **PASA** - Instrucciones funcionan y llega a opciones  
□ **FALLA** - Instrucciones no funcionan o proceso diferente  

**¿Banco Unión Colombiano estaba disponible?** □ Sí □ No  
**¿Instrucciones del documento coinciden?** □ Sí □ No  
**¿Proceso fue como se esperaba?** □ Sí □ No  
**Observaciones:** ________________________________

---

## PRUEBA 8: Escenario 1 - Pago Exitoso
**Funcionalidad:** Seleccionar opción "Pagar" para simular pago exitoso

### Pasos a realizar:
1. Seleccionar la opción que simula "Pago exitoso"
2. Completar proceso de pago simulado
3. Esperar respuesta del sistema
4. Verificar que regresa al portal con confirmación

### Resultado esperado:
Pago se procesa exitosamente y sistema confirma transacción aprobada

### Resultado obtenido:
□ **PASA** - Pago exitoso, confirmación clara  
□ **FALLA** - Error en pago o confirmación confusa  

**¿Proceso de pago fue fluido?** □ Sí □ No  
**¿Confirmación de éxito era clara?** □ Sí □ No  
**Tiempo del proceso:** _____ minutos  
**Observaciones:** ________________________________

---

## PRUEBA 9: Generación Automática de Código de Guía
**Funcionalidad:** Verificar que se genera automáticamente código de guía después del pago exitoso

### Pasos a realizar:
1. Después del pago exitoso, verificar ítems en portal
2. Buscar códigos de guía generados
3. Confirmar que cada guía tiene su código único
4. Verificar que códigos se muestran claramente

### Resultado esperado:
Se generan automáticamente códigos únicos para cada guía pagada

### Resultado obtenido:
□ **PASA** - Códigos de guía generados automáticamente  
□ **FALLA** - No se generan códigos o no son visibles  

**¿Aparecieron códigos de guía?** □ Sí □ No  
**¿Códigos son únicos para cada guía?** □ Sí □ No  
**¿Códigos son claramente visibles?** □ Sí □ No  
**Ejemplos de códigos:** ________________________________  
**Observaciones:** ________________________________

---

## PRUEBA 10: Escenario 2 - Transacción Pendiente
**Funcionalidad:** Probar escenario de transacción que queda pendiente

### Pasos a realizar:
1. Realizar nuevo proceso de pago con ítems diferentes
2. Seleccionar opción que simula "Transacción pendiente"
3. Verificar estado de transacción pendiente
4. Esperar 20 minutos (o tiempo especificado)
5. Verificar liberación automática de transacción

### Resultado esperado:
Sistema maneja transacción pendiente y la libera automáticamente después del tiempo especificado

### Resultado obtenido:
□ **PASA** - Transacción pendiente manejada correctamente  
□ **FALLA** - Error en manejo de transacción pendiente  

**¿Estado "pendiente" era claro?** □ Sí □ No  
**¿Se liberó automáticamente después de 20 min?** □ Sí □ No  
**¿Qué pasó con los ítems durante la espera?** ________________________________  
**Observaciones:** ________________________________

---

## PRUEBA 11: Escenario 3 - Transacción Rechazada
**Funcionalidad:** Probar escenario de transacción rechazada y reintento

### Pasos a realizar:
1. Realizar proceso de pago con nuevos ítems
2. Seleccionar opción que simula "Transacción rechazada"
3. Verificar mensaje de rechazo
4. Confirmar que permite intentar nuevamente el pago
5. Realizar reintento exitoso

### Resultado esperado:
Sistema informa rechazo claramente y permite reintento de pago sin perder ítems

### Resultado obtenido:
□ **PASA** - Rechazo manejado correctamente con opción de reintento  
□ **FALLA** - Error en manejo de rechazo o no permite reintento  

**¿Mensaje de rechazo era claro?** □ Sí □ No  
**¿Permitió reintento inmediatamente?** □ Sí □ No  
**¿Ítems se conservaron para reintento?** □ Sí □ No  
**¿Reintento funcionó correctamente?** □ Sí □ No  
**Observaciones:** ________________________________

---

## PRUEBA 12: Regreso a Aplicación Móvil
**Funcionalidad:** Regresar a app móvil después del proceso de pago

### Pasos a realizar:
1. Después de completar proceso de pago exitoso
2. Regresar a la aplicación móvil SINIGAN
3. Verificar estado del carrito
4. Buscar guías pagadas en la aplicación

### Resultado esperado:
Puede regresar a app móvil y verificar que guías pagadas están disponibles

### Resultado obtenido:
□ **PASA** - Regreso exitoso con guías disponibles en app  
□ **FALLA** - Problemas para regresar o guías no disponibles  

**¿Cómo regresó a la app?** ________________________________  
**¿Carrito se actualizó correctamente?** □ Sí □ No  
**¿Guías pagadas aparecen en la app?** □ Sí □ No  
**Observaciones:** ________________________________

---

## RESUMEN FINAL - REALIZACIÓN DE PAGOS PSE

**Total Pruebas Pasadas:** ___/12  
**Total Pruebas Falladas:** ___/12  
**Tiempo Total del Proceso:** _____ minutos

### Análisis por Secciones:
- **Preparación y Transición Web (1-3):** ___/3 ✅
- **Proceso de Pago PSE (4-7):** ___/4 ✅  
- **Escenarios de Pago (8-11):** ___/4 ✅
- **Finalización (12):** ___/1 ✅

### Validaciones Críticas de Negocio:
□ **Pago exitoso genera códigos de guía automáticamente**  
□ Transacciones pendientes se liberan automáticamente (20 min)  
□ Transacciones rechazadas permiten reintento  
□ Ítems del carrito coinciden en web y móvil  
□ Códigos de guía son únicos y visibles  

### Escenarios de Pago Probados:
□ **Escenario 1**: Pago exitoso - ✅ Códigos generados  
□ **Escenario 2**: Transacción pendiente - ✅ Liberación automática  
□ **Escenario 3**: Transacción rechazada - ✅ Permite reintento  

### Puntos de Fricción Más Críticos:
1. ________________________________
2. ________________________________
3. ________________________________

### Aspectos de Integración Web-Móvil:
□ Transición app → web es fluida  
□ Datos coinciden entre plataformas  
□ Regreso web → app funciona correctamente  
□ Estados se sincronizan apropiadamente  

### Funcionalidad PSE:
□ PSE está disponible como método de pago  
□ Selección de banco funciona  
□ Instrucciones del documento coinciden  
□ Simulaciones de pago funcionan correctamente  

### ¿Todos los escenarios de pago funcionaron correctamente?** □ Sí □ No

### Nivel de Dificultad del Proceso de Pago (1-5):
⭐ Muy Fácil | ⭐⭐ Fácil | ⭐⭐⭐ Normal | ⭐⭐⭐⭐ Difícil | ⭐⭐⭐⭐⭐ Muy Difícil

### ¿Proceso de pago inspira confianza?** □ Sí □ No

### ¿Usaría regularmente esta funcionalidad de pago?** □ Sí □ No

**Comentarios finales del usuario:**
_________________________________________________
_________________________________________________
_________________________________________________

**Problemas más críticos encontrados:**
1. ________________________________
2. ________________________________
3. ________________________________

---

**Notas Finales del Evaluador:**
_________________________________________________
_________________________________________________
_________________________________________________