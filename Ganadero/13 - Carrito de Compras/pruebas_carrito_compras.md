# Pruebas Atómicas - Carrito de Compras

**Usuario:** _______________ | **Fecha:** _______________ | **Duración:** _____ min  
**Dispositivo:** _______________ | **Versión App:** _______________

---

## PRUEBA 1: Verificación de Adición Automática al Carrito
**Funcionalidad:** Confirmar que guías y bonos se agregan automáticamente después de presionar "Agregar al carrito"

### Pasos a realizar:
1. Completar proceso de creación de una guía (cualquier tipo)
2. Llegar al resumen final de la guía
3. Presionar botón "Agregar al carrito"
4. Verificar confirmación de agregado
5. Acceder al carrito de compras
6. Verificar que la guía aparece en el carrito

### Resultado esperado:
La guía se agrega automáticamente al carrito después de presionar el botón

### Resultado obtenido:
□ **PASA** - Guía aparece automáticamente en carrito  
□ **FALLA** - Guía no aparece o hay errores  

**Tipo de guía creada:** ________________________________  
**¿Confirmó que se agregó?** □ Sí □ No  
**¿Apareció en el carrito?** □ Sí □ No  
**Tiempo de procesamiento:** _____ segundos  
**Observaciones:** ________________________________

---

## PRUEBA 2: Verificación de Bono Asociado (Si Aplica)
**Funcionalidad:** Confirmar que cuando una guía tiene bono, ambos ítems se agregan al carrito

### Pasos a realizar:
1. Crear una guía CON bono (planta de beneficio con bono)
2. Completar proceso hasta el resumen
3. Presionar "Agregar al carrito"
4. Acceder al carrito de compras
5. Verificar que aparecen DOS ítems: guía Y bono
6. Confirmar que están relacionados

### Resultado esperado:
Aparecen dos ítems en el carrito: la guía y su bono asociado

### Resultado obtenido:
□ **PASA** - Aparecen guía y bono como ítems separados  
□ **FALLA** - Solo aparece uno o no están relacionados  

**¿Aparecieron ambos ítems?** □ Sí □ No  
**¿Se ve la relación entre guía y bono?** □ Sí □ No  
**¿Nombres de ítems son claros?** □ Sí □ No  
**Observaciones:** ________________________________

---

## PRUEBA 3: Acceso al Carrito de Compras
**Funcionalidad:** Localizar y acceder al carrito de compras en la aplicación

### Pasos a realizar:
1. Desde cualquier pantalla de la app, buscar ícono/opción del carrito
2. Verificar si está en menú principal, tabs, o como ícono
3. Hacer clic para acceder al carrito
4. Observar interfaz del carrito

### Resultado esperado:
El carrito de compras es fácil de encontrar y accesible desde la app

### Resultado obtenido:
□ **PASA** - Carrito fácil de encontrar y acceder  
□ **FALLA** - Carrito difícil de localizar o no accesible  

**¿Dónde encontró el carrito?** ________________________________  
**¿Ícono/texto era claro?** □ Sí □ No  
**¿Mostraba cantidad de ítems?** □ Sí □ No  
**Tiempo para encontrarlo:** _____ segundos  
**Observaciones:** ________________________________

---

## PRUEBA 4: Visualización de Ítems en el Carrito
**Funcionalidad:** Revisar cómo se muestran las guías y bonos en el carrito

### Pasos a realizar:
1. Observar lista de ítems en el carrito
2. Verificar información mostrada de cada ítem
3. Identificar guías vs bonos
4. Revisar precios, cantidades, y detalles

### Resultado esperado:
Los ítems se muestran claramente con información relevante y distinguible

### Resultado obtenido:
□ **PASA** - Ítems claros y bien diferenciados  
□ **FALLA** - Información confusa o ítems no diferenciables  

**¿Información de cada ítem era clara?** □ Sí □ No  
**¿Se distinguen guías de bonos?** □ Sí □ No  
**¿Precios están visibles?** □ Sí □ No  
**¿Qué información muestra cada ítem?** ________________________________  
**Observaciones:** ________________________________

---

## PRUEBA 5: Eliminación de Guía Sin Bono
**Funcionalidad:** Eliminar una guía que NO tiene bono asociado

### Pasos a realizar:
1. Localizar una guía sin bono en el carrito
2. Buscar opción para eliminar (botón, swipe, menú)
3. Eliminar la guía del carrito
4. Confirmar eliminación si se solicita
5. Verificar que solo se elimina esa guía

### Resultado esperado:
La guía se elimina del carrito sin afectar otros ítems

### Resultado obtenido:
□ **PASA** - Guía se elimina correctamente  
□ **FALLA** - Error al eliminar o elimina ítems incorrectos  

**¿Cómo se elimina?** □ Botón □ Swipe □ Menú □ Otro: ____________  
**¿Pidió confirmación?** □ Sí □ No  
**¿Solo eliminó esa guía?** □ Sí □ No  
**Observaciones:** ________________________________

---

## PRUEBA 6: Eliminación de Guía CON Bono (Prueba Crítica)
**Funcionalidad:** Eliminar una guía que SÍ tiene bono y verificar que se eliminan ambos ítems

### Pasos a realizar:
1. Localizar una guía CON bono en el carrito
2. Eliminar LA GUÍA (no el bono directamente)
3. Observar qué pasa con ambos ítems
4. Verificar que se eliminaron TANTO la guía COMO su bono asociado

### Resultado esperado:
Al eliminar la guía, automáticamente se elimina también su bono asociado

### Resultado obtenido:
□ **PASA** - Se eliminan automáticamente guía Y bono  
□ **FALLA** - Solo se elimina la guía o queda bono "huérfano"  

**¿Se eliminaron ambos ítems?** □ Sí □ No  
**¿Fue automático?** □ Sí □ No  
**¿Quedó bono sin guía?** □ Sí □ No  
**¿Mostró alguna advertencia?** □ Sí □ No  
**Observaciones:** ________________________________

---

## PRUEBA 7: Eliminación de Bono Directamente
**Funcionalidad:** Intentar eliminar un bono directamente y ver el comportamiento

### Pasos a realizar:
1. Crear nueva guía con bono para tener ítems en carrito
2. Intentar eliminar EL BONO (no la guía)
3. Observar si permite eliminarlo
4. Verificar qué pasa con la guía asociada

### Resultado esperado:
Sistema debe manejar correctamente la eliminación de bonos y su relación con guías

### Resultado obtenido:
□ **PASA** - Maneja eliminación de bono apropiadamente  
□ **FALLA** - Comportamiento incorrecto o inconsistente  

**¿Permite eliminar bono directamente?** □ Sí □ No  
**Si se elimina bono, ¿qué pasa con la guía?** ________________________________  
**¿Comportamiento es lógico?** □ Sí □ No  
**Observaciones:** ________________________________

---

## PRUEBA 8: Múltiples Guías con y sin Bonos
**Funcionalidad:** Probar carrito con múltiples ítems de diferentes tipos

### Pasos a realizar:
1. Agregar al carrito: 2 guías sin bono + 1 guía con bono
2. Verificar que aparecen 4 ítems total (2 guías + 1 guía + 1 bono)
3. Eliminar la guía CON bono
4. Verificar que quedan solo 2 ítems (las guías sin bono)

### Resultado esperado:
Carrito maneja correctamente múltiples ítems y eliminaciones selectivas

### Resultado obtenido:
□ **PASA** - Manejo correcto de múltiples ítems  
□ **FALLA** - Errores con múltiples ítems o eliminaciones  

**Ítems inicial:** _____ ítems  
**Después de eliminar guía con bono:** _____ ítems  
**¿Eliminó correctamente guía + bono?** □ Sí □ No  
**¿Otras guías no se afectaron?** □ Sí □ No  
**Observaciones:** ________________________________

---

## PRUEBA 9: Totales y Cálculos en el Carrito
**Funcionalidad:** Verificar que totales se calculan correctamente

### Pasos a realizar:
1. Observar precios individuales de cada ítem
2. Verificar cálculo del subtotal
3. Verificar impuestos si aplican
4. Confirmar total final
5. Eliminar un ítem y verificar recálculo

### Resultado esperado:
Todos los cálculos son correctos y se actualizan automáticamente

### Resultado obtenido:
□ **PASA** - Cálculos correctos y actualizaciones automáticas  
□ **FALLA** - Errores en cálculos o no se actualizan  

**¿Precios individuales correctos?** □ Sí □ No  
**¿Subtotal correcto?** □ Sí □ No  
**¿Se recalcula al eliminar ítems?** □ Sí □ No  
**¿Hay impuestos mostrados?** □ Sí □ No  
**Observaciones:** ________________________________

---

## PRUEBA 10: Vaciar Carrito Completamente
**Funcionalidad:** Eliminar todos los ítems del carrito

### Pasos a realizar:
1. Con ítems en el carrito, eliminar uno por uno
2. Observar comportamiento cuando queda 1 ítem
3. Eliminar el último ítem
4. Verificar estado del carrito vacío

### Resultado esperado:
Carrito muestra estado vacío apropiadamente cuando no hay ítems

### Resultado obtenido:
□ **PASA** - Estado de carrito vacío es claro  
□ **FALLA** - Carrito vacío confuso o con errores  

**¿Muestra mensaje de carrito vacío?** □ Sí □ No  
**¿Interfaz de carrito vacío es clara?** □ Sí □ No  
**¿Hay opción para seguir agregando?** □ Sí □ No  
**Observaciones:** ________________________________

---

## RESUMEN FINAL - CARRITO DE COMPRAS

**Total Pruebas Pasadas:** ___/10  
**Total Pruebas Falladas:** ___/10  
**Tiempo Total del Proceso:** _____ minutos

### Análisis por Secciones:
- **Adición al Carrito (1-2):** ___/2 ✅
- **Navegación y Visualización (3-4):** ___/2 ✅  
- **Eliminaciones Individuales (5-6):** ___/2 ✅
- **Eliminaciones Complejas (7-8):** ___/2 ✅
- **Gestión General (9-10):** ___/2 ✅

### Validación Crítica - Guías con Bonos:
□ **CRÍTICO**: Eliminar guía elimina automáticamente su bono  
□ Guías y bonos se agregan como ítems separados  
□ Relación entre guía y bono es clara  
□ No quedan bonos "huérfanos" en el carrito  

### Puntos de Fricción Más Críticos:
1. ________________________________
2. ________________________________
3. ________________________________

### Funcionalidades del Carrito que Funcionaron:
□ Adición automática de ítems  
□ Visualización clara de contenido  
□ Eliminación individual funciona  
□ **Eliminación de guía + bono asociado**  
□ Cálculos y totales correctos  
□ Estado de carrito vacío claro  

### Problemas de Lógica de Negocio:
□ Bonos quedan sin guía asociada  
□ Eliminaciones no funcionan correctamente  
□ Cálculos incorrectos  
□ Relaciones guía-bono confusas  

### ¿Funcionalidad crítica (guía+bono) funciona correctamente?** □ Sí □ No

### Nivel de Dificultad para Gestionar Carrito (1-5):
⭐ Muy Fácil | ⭐⭐ Fácil | ⭐⭐⭐ Normal | ⭐⭐⭐⭐ Difícil | ⭐⭐⭐⭐⭐ Muy Difícil

### ¿Carrito se comporta como esperaría un usuario?** □ Sí □ No

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