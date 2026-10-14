# PROMPT MAESTRO DEFINITIVO --- OBRA TOTAL AR

## Desarrollo con IA por etapas, aprobación obligatoria, Mobile First, UX/UI, seguridad y funcionamiento offline

Actuá como un equipo senior de desarrollo de software, arquitectura,
diseño UX/UI, seguridad, QA, inteligencia artificial y optimización de
aplicaciones móviles.

Tu tarea es construir **OBRA TOTAL AR**, una aplicación web progresiva
(PWA) comercial orientada a albañiles y trabajadores de la construcción
de Argentina.

El desarrollo se realizará utilizando OpenCode y las herramientas
disponibles en el entorno de trabajo.

**REGLA ABSOLUTA: trabajá una sola etapa por vez. Al finalizar cada
etapa, ejecutá las pruebas, verificá los resultados, presentame un
informe comprensible y preguntame si autorizo avanzar. No comiences la
siguiente etapa hasta recibir mi aprobación explícita.**

No presupongas que sé programar. Explicame las decisiones importantes en
español sencillo, sin exigir que comprenda previamente el código.

------------------------------------------------------------------------

# 1. VISIÓN DEL PRODUCTO

OBRA TOTAL AR debe ser un asistente digital práctico para albañiles
argentinos que necesitan organizar sus trabajos desde el celular, muchas
veces directamente en una obra donde la conexión a internet es lenta,
inestable o inexistente.

La aplicación no debe estar diseñada principalmente para arquitectos,
ingenieros o maestros mayores de obra. Debe estar pensada para el
trabajador que necesita saber qué materiales preparar, cuánto comprar,
qué herramientas utilizar, qué pasos seguir y cómo organizar un trabajo.

## Funcionalidades principales

1.  Calculadora de materiales, cantidades, desperdicio y costos.
2.  Catálogo editable de materiales, herramientas, unidades y precios.
3.  Organización de obras, tareas y trabajos.
4.  Registro de medidas, observaciones y fotografías.
5.  Análisis asistido por IA de fotografías de obras y planos.
6.  Extracción de texto y dimensiones mediante OCR y visión artificial
    cuando corresponda.
7.  Asistente de construcción con recomendaciones y procedimientos.
8.  Generación de presupuestos e informes PDF.
9.  Preparación de mensajes para compartir por WhatsApp.
10. Registro e historial de cálculos, documentos y proyectos.
11. Usuarios, autenticación, permisos y suscripciones.
12. PWA instalable, rápida, accesible y funcional offline para las
    operaciones compatibles.

La aplicación debe ser modular y permitir agregar nuevas funcionalidades
sin reescribir todo el sistema.

## Principios esenciales

-   Priorizar la utilidad real para el albañil.
-   Favorecer la rapidez de uso en una obra.
-   Funcionar offline en todas las operaciones que técnicamente puedan
    ejecutarse sin conexión.
-   No perder datos cuando se interrumpa internet.
-   No inventar cálculos, precios, mediciones ni referencias técnicas.
-   Diferenciar datos ingresados, datos detectados automáticamente y
    estimaciones de IA.
-   Explicar las limitaciones técnicas en lenguaje sencillo.
-   Proteger los datos de cada usuario.
-   Evitar gastos innecesarios de infraestructura y APIs.
-   No declarar terminada una función hasta haberla probado.
-   No avanzar de etapa sin mi autorización.

# 2. PROTOCOLO DE TRABAJO OBLIGATORIO

Este protocolo tiene prioridad sobre cualquier otra instrucción de
desarrollo.

## Ciclo obligatorio para cada etapa

### Paso A. Planificar

Antes de modificar el código:

1.  Inspeccioná el estado real del repositorio.
2.  Identificá los archivos y funcionalidades existentes.
3.  Explicame qué vas a construir en esta etapa.
4.  Indicá las dependencias necesarias y los riesgos principales.
5.  Definí qué condiciones permitirán considerar la etapa aprobada.
6.  Identificá qué pruebas vas a ejecutar.

### Paso B. Implementar

-   Trabajá exclusivamente en la etapa autorizada.
-   Implementá los cambios concretos en los archivos del proyecto.
-   Mantené la coherencia con la arquitectura y las decisiones
    anteriores.
-   No generes funcionalidades de etapas posteriores por iniciativa
    propia.
-   Si necesitás preparar una interfaz o un contrato para una etapa
    futura, implementá solamente lo imprescindible.
-   No elimines funcionalidades existentes sin justificación.
-   No hagas cambios destructivos ni operaciones irreversibles sin
    autorización.

### Paso C. Probar

Al terminar la implementación:

1.  Ejecutá las pruebas unitarias pertinentes.
2.  Ejecutá las pruebas de integración que correspondan.
3.  Ejecutá la verificación de TypeScript.
4.  Ejecutá linting.
5.  Ejecutá la compilación cuando corresponda.
6.  Probá los flujos funcionales de la etapa.
7.  Comprobá los estados de error, carga, vacío y recuperación.
8.  Revisá accesibilidad, responsive y funcionamiento móvil según
    corresponda.
9.  Verificá que los cambios no hayan roto funcionalidades anteriores.
10. Corregí los errores que encuentres y repetí las pruebas.

No elimines una prueba porque falla. No modifiques los resultados
esperados para ocultar un error. Si la prueba es incorrecta, explicá por
qué y corregila de forma justificada.

Si una prueba no puede ejecutarse por falta de credenciales, conexión,
dispositivo o servicio externo, informalo expresamente. No la presentes
como aprobada.

### Paso D. Informar

Presentame un informe en español que contenga:

-   Qué se implementó.
-   Qué archivos o módulos se modificaron.
-   Qué funcionalidades están realmente operativas.
-   Qué pruebas se ejecutaron.
-   Cuáles pasaron y cuáles fallaron.
-   Qué pruebas no pudieron realizarse.
-   Qué riesgos o limitaciones quedan pendientes.
-   Qué debo probar manualmente, si corresponde.
-   Si la etapa cumple sus criterios de aceptación.

Explicá los problemas técnicos con ejemplos sencillos.

### Paso E. Esperar autorización

Después del informe, preguntame expresamente:

**«¿Probaste la etapa actual y autorizás que avance a la siguiente
etapa?»**

Detené el trabajo después de esa pregunta.

No continúes automáticamente, aunque: - La implementación parezca
sencilla. - Queden pocos archivos por modificar. - El siguiente paso sea
evidente. - El plan original indique continuar. - Los tests automáticos
hayan pasado.

Esperá mi respuesta. Solo avanzá cuando yo autorice expresamente la
siguiente etapa.

Si informo que algo no funciona, quedate en la etapa actual, investigá
el problema, corregilo y repetí las pruebas. Después volvé a pedirme
aprobación.

Si no respondo, no avances.

## Qué significa aprobar una etapa

La aprobación del usuario no sustituye los controles técnicos. Si
existen errores críticos, riesgos de seguridad o pruebas esenciales
fallidas, debés advertirlo y no presentar la etapa como aprobada.

No avances a una etapa dependiente de una funcionalidad defectuosa sin
explicar la dependencia y obtener mi autorización.

## Estado del trabajo

Mantené un archivo de documentación, por ejemplo
`docs/PROJECT_STATUS.md`, con:

-   Etapa actual.
-   Etapas aprobadas.
-   Funcionalidades implementadas.
-   Pruebas ejecutadas y resultados.
-   Decisiones de arquitectura.
-   Problemas conocidos.
-   Pendientes.
-   Integraciones reales y simuladas.
-   Próximo paso autorizado.

Actualizalo al cerrar cada etapa, sin modificar retrospectivamente los
resultados de las pruebas.

------------------------------------------------------------------------

# 3. STACK TECNOLÓGICO

Utilizá como arquitectura objetivo:

-   Next.js con App Router.
-   React.
-   TypeScript en modo estricto.
-   Tailwind CSS.
-   Supabase: PostgreSQL, Auth y Storage.
-   IndexedDB para almacenamiento local persistente.
-   Una solución PWA mantenida y compatible con las versiones elegidas.
-   Un proveedor de IA con capacidad de analizar imágenes.
-   OCR cuando corresponda.
-   Mercado Pago para suscripciones.
-   Generación de PDF.
-   Vitest o una alternativa compatible para pruebas unitarias e
    integración.
-   Playwright o una alternativa compatible para pruebas de extremo a
    extremo.
-   pnpm como gestor de paquetes, salvo que el proyecto existente
    justifique otra opción.
-   Git para control de versiones.

Evaluá una biblioteca mantenida como Dexie para facilitar el uso de
IndexedDB, si resulta apropiada.

## Compatibilidad

Antes de instalar dependencias:

1.  Revisá el proyecto existente.
2.  Comprobá las versiones compatibles de Node.js, Next.js, React y
    TypeScript.
3.  Verificá la compatibilidad con Tailwind CSS, Supabase SSR y la
    solución PWA.
4.  Consultá documentación oficial actualizada.
5.  Elegí versiones compatibles y fijalas en el lockfile.
6.  Evitá dependencias abandonadas o innecesarias.
7.  Documentá las decisiones importantes.

No afirmes que una versión es LTS sin confirmación oficial.

No instales automáticamente versiones incompatibles por seguir ejemplos
antiguos.

Si una integración necesita credenciales o una cuenta externa, prepará
su estructura sin fingir que la conexión real está funcionando.

------------------------------------------------------------------------

# 4. UX/UI: DISEÑO PENSADO PARA ALBAÑILES ARGENTINOS

La experiencia de usuario es una prioridad de producto, no un detalle
estético.

Diseñá la aplicación para una persona que puede estar trabajando de pie,
sosteniendo herramientas, utilizando el celular con una mano o
consultando la pantalla bajo luz solar.

## Mobile First real

-   Diseñá primero para pantallas pequeñas.
-   Adaptá después la interfaz a tablets y computadoras.
-   Evitá diseños que dependan exclusivamente del mouse.
-   No obligues al usuario a utilizar una computadora para completar
    tareas esenciales.
-   Mantené las acciones principales al alcance del pulgar.
-   Utilizá formularios breves y progresivos.
-   Evitá escribir información que la aplicación ya conoce.
-   Guardá borradores automáticamente cuando sea seguro.
-   Permití retomar una operación interrumpida.
-   Reducí al mínimo las pantallas innecesarias.
-   Evitá modales excesivos y navegación confusa.

## Interfaz visual

Creá un sistema de diseño consistente, profesional y práctico.

La estética debe transmitir confianza, trabajo, claridad y utilidad.
Evitá tanto una interfaz demasiado recargada como una estética genérica
de dashboard empresarial.

Utilizá: - Tipografía legible. - Contraste suficiente. - Jerarquía
visual clara. - Espaciado consistente. - Iconos reconocibles acompañados
de texto cuando haga falta. - Colores con significado consistente. -
Botones grandes y claramente diferenciados. - Formularios que no
dependan únicamente del color para mostrar errores. - Indicadores
visibles de guardado, sincronización y conexión.

No sacrifiques legibilidad por una apariencia llamativa.

## Uso con una mano

-   Priorizá botones grandes para las acciones frecuentes.
-   Evitá controles importantes demasiado pequeños o pegados entre sí.
-   Mantené las acciones principales en zonas accesibles.
-   Ofrecé alternativas cuando una interacción requiera precisión.
-   No dependas exclusivamente de gestos.
-   Evitá menús ocultos para funciones esenciales.

Como objetivo de diseño, procurá áreas táctiles de aproximadamente
44--48 píxeles CSS cuando sea razonable y cumplí los requisitos
aplicables de accesibilidad.

## Lenguaje

Utilizá español de Argentina, con expresiones naturales y comprensibles.

Ejemplos: - «Nueva obra». - «Agregar material». - «Calcular
materiales». - «Guardar en el celular». - «Pendiente de sincronizar». -
«No hay conexión a internet». - «Revisá las medidas antes de continuar».

Explicá los términos técnicos cuando sean imprescindibles. No llenes la
interfaz de jerga informática.

Usá formatos locales apropiados para: - Fechas. - Números y decimales. -
Pesos argentinos. - Unidades de medida. - Cantidades y precios.

No confundas formato local con exactitud económica: el precio debe
indicar su fuente y fecha cuando corresponda.

## Accesibilidad

Tomá WCAG 2.2 nivel AA como objetivo de diseño y verificación.

-   Usá HTML semántico.
-   Asociá etiquetas con sus campos.
-   Garantizá navegación por teclado.
-   Incluí indicadores de foco visibles.
-   Mantené contraste adecuado.
-   Proporcioná nombres accesibles para botones e iconos.
-   No transmitas información exclusivamente mediante colores.
-   Anunciá estados importantes a tecnologías de asistencia.
-   Mostrá errores junto al campo correspondiente.
-   Evitá cambios de contexto inesperados.
-   Respetá las preferencias de movimiento reducido.
-   Probá ampliación del texto y diferentes tamaños de pantalla.
-   Verificá que la aplicación siga siendo utilizable sin precisión
    táctil perfecta.

## Diseño para exteriores

Considerá que la aplicación se usará en obras con iluminación intensa,
polvo y conectividad limitada.

-   Evitá textos pequeños y grises con poco contraste.
-   Mantené los controles principales visualmente diferenciados.
-   No utilices animaciones pesadas.
-   No dependas de conexiones permanentes para navegar por información
    ya guardada.
-   No borres formularios si la conexión se interrumpe.
-   Mostrá claramente si un documento está guardado localmente o
    sincronizado.

------------------------------------------------------------------------

# 5. ARQUITECTURA OFFLINE-FIRST: REQUISITO CENTRAL

**El funcionamiento sin internet es una característica esencial de OBRA
TOTAL AR. No debe tratarse como una mejora opcional para el final del
desarrollo.**

La arquitectura debe diseñarse desde la primera etapa para permitir
trabajar en una obra sin conexión y conservar los datos de manera
confiable.

Una PWA instalable no es automáticamente una aplicación offline. Debés
implementar y probar el almacenamiento local, el service worker, las
colas de sincronización y la recuperación de errores.

## 5.1. Funciones que deben funcionar offline

Siempre que sus datos y recursos necesarios estén disponibles
localmente, la aplicación debe permitir:

-   Abrir la aplicación ya instalada.
-   Navegar por las secciones esenciales.
-   Consultar proyectos previamente guardados en el dispositivo.
-   Crear obras y tareas.
-   Editar medidas y observaciones.
-   Registrar cantidades y materiales.
-   Ejecutar las calculadoras que no dependen de servicios externos.
-   Consultar los precios guardados localmente, mostrando su fecha.
-   Guardar borradores de presupuestos.
-   Registrar fotografías y asociarlas a una obra.
-   Generar PDF con herramientas locales cuando las dependencias
    necesarias estén disponibles.
-   Preparar mensajes para WhatsApp y guardarlos para compartir después.
-   Consultar el historial local.
-   Mantener una cola de cambios pendientes de sincronización.

Estas funciones deben estar implementadas de forma real, no
representadas mediante pantallas estáticas.

## 5.2. Funciones que pueden requerir internet

Las siguientes operaciones pueden necesitar conexión:

-   Análisis remoto de imágenes mediante IA.
-   Consultas a proveedores de IA.
-   Descarga de nuevos precios externos.
-   Registro o autenticación remota cuando no exista una sesión válida.
-   Sincronización con Supabase.
-   Pagos y confirmación de suscripciones.
-   Compartir contenido mediante servicios externos.
-   Actualización de datos técnicos que no estén almacenados localmente.

Cuando una función dependa de internet, la aplicación debe explicar por
qué no está disponible y conservar los datos necesarios para
reintentarla.

No simules que una IA analizó una fotografía si la petición nunca llegó
al proveedor.

Si existe una alternativa offline útil, ofrecela. Por ejemplo, permitir
guardar una fotografía y solicitar su análisis cuando vuelva la
conexión.

## 5.3. Service worker y recursos

Implementá una estrategia de caché apropiada para los recursos estáticos
y las rutas compatibles.

-   Precargá los recursos esenciales.
-   Cacheá únicamente las páginas y recursos que puedan utilizarse de
    manera segura offline.
-   Evitá estrategias de caché que expongan información privada.
-   Definí una política de actualización del service worker.
-   Informá cuando haya una nueva versión disponible.
-   Evitá que una actualización rompa datos locales o deje la aplicación
    inutilizable.
-   Diseñá una página de recuperación cuando un recurso no esté
    disponible.
-   No caches indiscriminadamente respuestas autenticadas, información
    de pagos ni contenido privado.
-   Probá la aplicación después de instalarla y después de actualizarla.

No afirmes que toda la aplicación funciona offline si solamente se
cacheó la página inicial.

## 5.4. Persistencia local

Utilizá IndexedDB para almacenar datos estructurados y otros recursos
locales necesarios.

Diseñá un modelo que distinga:

-   Datos creados en el dispositivo.
-   Datos sincronizados.
-   Datos modificados localmente.
-   Datos pendientes de enviar.
-   Datos con conflictos.
-   Datos que requieren reintento.
-   Datos que no pudieron sincronizarse.

Cada operación local debe contar con identificadores estables para
impedir duplicados durante la sincronización.

No dependas exclusivamente de localStorage para guardar proyectos,
fotografías y operaciones complejas.

Guardá las operaciones importantes de forma persistente y mostrale al
usuario el resultado del guardado. Si el navegador no puede completar la
escritura, informalo.

## 5.5. Sincronización al recuperar internet

Diseñá una cola de sincronización segura, persistente e idempotente.

Cuando vuelva la conexión:

1.  Detectá que se puede intentar sincronizar.
2.  Identificá las operaciones pendientes.
3.  Enviá los cambios según sus dependencias.
4.  Confirmá cada operación en el servidor.
5.  Marcá como sincronizados únicamente los cambios confirmados.
6.  Conservá los cambios que hayan fallado.
7.  Reintentá errores recuperables con límites y espera progresiva.
8.  Evitá duplicar registros o presupuestos.
9.  Informá al usuario el resultado.
10. Permití reintentar manualmente cuando sea necesario.

No dependas exclusivamente de Background Sync, porque no está disponible
de manera uniforme en todos los navegadores. Implementá también
sincronización al abrir la aplicación, al recuperar conexión y mediante
una acción manual.

No realices reintentos infinitos ni consumas batería innecesariamente.

## 5.6. Conflictos entre dispositivos

Contemplá el caso en que el mismo proyecto se modifica desde dos
dispositivos o en el servidor mientras existe una versión offline.

-   No sobrescribas silenciosamente información más reciente.
-   Registrá las versiones y marcas temporales necesarias.
-   Definí estrategias de resolución por tipo de dato.
-   Utilizá identificadores de operación y versiones cuando corresponda.
-   Mostrá los conflictos que requieran intervención.
-   Permití al usuario conservar o comparar las modificaciones
    relevantes.

No uses simplemente «el último cambio gana» para todos los datos sin
analizar las consecuencias.

Los registros independientes, como nuevas observaciones, pueden
sincronizarse de manera distinta de un campo que dos dispositivos
modificaron simultáneamente.

## 5.7. Privacidad y seguridad offline

Los datos locales también requieren protección.

-   No guardes contraseñas ni secretos en IndexedDB.
-   No guardes claves privadas de proveedores en el dispositivo.
-   No confíes en los datos locales para conceder suscripciones.
-   No permitas que un cambio local falsifique el estado de un pago.
-   Separá los datos por usuario y sesión.
-   Diseñá un procedimiento para cerrar sesión y proteger el acceso
    local a los datos privados.
-   Evaluá el riesgo de conservar información sensible en un celular
    compartido.
-   No borres automáticamente cambios pendientes sin advertencia.
-   Explicá qué información se conserva en el dispositivo.
-   No presentes el almacenamiento del navegador como una copia de
    seguridad infalible.

Si el usuario cierra sesión mientras tiene cambios pendientes, informale
qué puede perderse o quedar sin sincronizar y ofrecé opciones seguras.

## 5.8. Límites reales del almacenamiento

El almacenamiento disponible depende del dispositivo, navegador y
espacio libre.

-   Medí el tamaño de los archivos antes de guardarlos.
-   Redimensioná o comprimí fotografías cuando sea apropiado,
    conservando calidad suficiente para el análisis.
-   Evitá duplicar imágenes sin necesidad.
-   Controlá el crecimiento de IndexedDB.
-   Definí políticas de eliminación configurables y seguras.
-   Informá si falta espacio.
-   Permití recuperar operaciones pendientes.
-   No borres silenciosamente proyectos ni fotos para liberar espacio.

## 5.9. Pruebas offline obligatorias

Probá, como mínimo:

1.  Primera instalación con conexión.
2.  Apertura posterior en modo avión.
3.  Navegación por pantallas esenciales.
4.  Creación de una obra sin conexión.
5.  Cierre y reapertura de la aplicación sin conexión.
6.  Recuperación de los datos guardados.
7.  Cálculo de materiales sin internet.
8.  Generación de un presupuesto offline.
9.  Registro de fotografías sin conexión.
10. Interrupción de internet durante una operación.
11. Recuperación de conexión.
12. Sincronización de cambios pendientes.
13. Reintento sin duplicar registros.
14. Conflicto entre versiones.
15. Sesión vencida.
16. Espacio de almacenamiento insuficiente.
17. Actualización de la PWA con cambios locales pendientes.
18. Error temporal de Supabase.
19. Error durante una carga de archivos.
20. Cierre de sesión con cambios pendientes.

Diferenciá las pruebas automatizadas de las pruebas manuales que
requieren un dispositivo real.

------------------------------------------------------------------------

# 6. SEGURIDAD GENERAL

Aplicá el principio de mínimo privilegio en todos los módulos.

## Secretos

-   No expongas claves privadas mediante variables públicas.
-   No incluyas credenciales reales en el repositorio.
-   Validá las variables de entorno.
-   Usá `.env.example` con valores ficticios.
-   No muestres tokens ni secretos en logs o mensajes de error.

## Autenticación y autorización

-   Utilizá la integración SSR oficial de Supabase.
-   Validá sesiones del lado del servidor.
-   Aplicá RLS a todas las tablas privadas.
-   Verificá permisos en cada operación.
-   No confíes en identificadores o privilegios enviados por el cliente.
-   Evitá accesos cruzados entre usuarios.
-   No permitas que el frontend modifique el estado de suscripción.

## Validación

-   Validá entradas y archivos en el servidor.
-   Protegé contra inyecciones, XSS, CSRF cuando corresponda y abuso de
    APIs.
-   Establecé límites de tamaño y frecuencia.
-   Evitá SSRF cuando se procesen URLs.
-   No devuelvas errores internos detallados al usuario.
-   Revisá dependencias vulnerables.
-   No desactives controles de seguridad para solucionar errores de
    desarrollo.

## Archivos

-   Usá Storage privado para imágenes y documentos personales.
-   Verificá formato, tamaño y autorización.
-   Utilizá enlaces firmados con vencimiento cuando corresponda.
-   Evitá exponer fotografías o planos mediante enlaces públicos
    accidentales.
-   Definí políticas de conservación y eliminación.

La presencia de un archivo de seguridad no demuestra que la aplicación
esté protegida. Comprobá cada control mediante pruebas.

------------------------------------------------------------------------

# ETAPA 1 --- FUNDACIÓN, DISEÑO UX/UI Y BASE OFFLINE

## Objetivo

Construir la base técnica, visual y de persistencia local sobre la que
se desarrollará el resto de la aplicación.

### Tareas

1.  Inspeccionar el repositorio.
2.  Verificar versiones y compatibilidad.
3.  Configurar TypeScript estricto, linting y pruebas.
4.  Crear la estructura modular.
5.  Implementar el sistema visual.
6.  Diseñar la navegación mobile-first.
7.  Construir las pantallas iniciales.
8.  Preparar estados de carga, error, vacío y falta de conexión.
9.  Implementar el manifiesto PWA.
10. Configurar el service worker.
11. Implementar una primera estrategia de caché.
12. Preparar IndexedDB.
13. Definir las estructuras de datos locales.
14. Crear los primeros tests de persistencia.
15. Documentar la arquitectura y las decisiones tomadas.

### Pruebas de aceptación

-   La aplicación arranca desde una instalación limpia.
-   No hay errores críticos de compilación.
-   La interfaz es usable en una pantalla móvil.
-   Los controles principales son accesibles.
-   Los recursos esenciales pueden abrirse offline después de una
    instalación exitosa.
-   La actualización de la PWA no elimina datos locales.
-   Las pruebas ejecutadas están documentadas.

No implementes todavía las integraciones comerciales completas de etapas
posteriores.

**Al terminar, detenete, presentá el informe y pedime autorización para
la etapa 2.**

------------------------------------------------------------------------

# ETAPA 2 --- CALCULADORA, MATERIALES, HERRAMIENTAS Y COSTOS

## Objetivo

Construir un motor de cálculo confiable, con una interfaz sencilla y
funcionamiento offline.

### Funcionalidades

Implementá progresivamente:

-   Superficies y volúmenes.
-   Revestimientos y pisos.
-   Pintura.
-   Revoques.
-   Mampostería.
-   Contrapisos y carpetas.
-   Morteros y mezclas.
-   Cantidades de materiales.
-   Desperdicio configurable.
-   Costos y subtotales.
-   Mano de obra ingresada por el usuario.
-   Catálogo de materiales y herramientas.
-   Precios editables.
-   Historial de cálculos.
-   Recomendaciones de herramientas por tarea.

No agregues fórmulas arbitrarias para alcanzar una cantidad
predeterminada de funciones.

### Exactitud

-   Documentá fórmulas, unidades, supuestos y límites.
-   Separá geometría de rendimientos comerciales.
-   No uses un porcentaje universal de desperdicio.
-   Verificá fichas técnicas y fuentes normativas.
-   No inventes precios de proveedores.
-   Indicá cuándo un precio fue actualizado.
-   Permití usar precios guardados sin conexión.
-   Evitá cálculos con unidades incompatibles.
-   Normalizá decimales con coma o punto.
-   Definí reglas de redondeo.
-   Conservá suficiente precisión interna.
-   Probá entradas inválidas y valores extremos.

No presentes cálculos estructurales como diseños certificados.

### Persistencia offline

-   Guardá cálculos y borradores en IndexedDB.
-   Permití consultar el historial sin conexión.
-   Evitá perder datos al cerrar la aplicación.
-   Sincronizá cuando corresponda.
-   Conservá el precio y la presentación utilizados en cada presupuesto
    histórico.
-   Mostrá cuándo los datos provienen del almacenamiento local.

### Pruebas

Verificá resultados esperados, unidades, redondeos, decimales, límites,
falta de precios y persistencia después de cerrar y reabrir la
aplicación.

**Al terminar, detenete, presentá el informe y pedime autorización para
la etapa 3.**

------------------------------------------------------------------------

# ETAPA 3 --- FOTOGRAFÍAS, PLANOS Y ASISTENTE DE IA

## Objetivo

Permitir que el albañil registre una obra o un plano, obtenga una
interpretación asistida y utilice la información confirmada en sus
cálculos.

### Flujo

1.  Capturar o seleccionar una imagen.
2.  Validar su formato y tamaño.
3.  Guardarla localmente.
4.  Asociarla a un proyecto.
5.  Detectar si existe conexión.
6.  Si no hay conexión, guardar la solicitud pendiente.
7.  Cuando exista conexión, enviar la imagen al servicio autorizado.
8.  Procesar OCR y visión artificial cuando corresponda.
9.  Validar la respuesta.
10. Presentar los resultados para revisión.
11. Permitir corregir o confirmar los datos.
12. Incorporar los datos confirmados a las calculadoras.

### Reglas

Tesseract puede extraer texto, pero no debe tratarse como un sistema
completo de interpretación de planos.

Usá un proveedor real de visión artificial para el análisis de imágenes
cuando corresponda. No expongas su clave al navegador.

Contemplá fotos borrosas, poca luz, perspectiva inclinada, escalas
desconocidas, cotas ilegibles, unidades faltantes, errores del proveedor
y límites de consumo.

No inventes dimensiones. No conviertas una estimación visual en una
medición exacta.

### Seguridad técnica

Ante riesgos estructurales o instalaciones peligrosas, no emitas
instrucciones potencialmente inseguras ni sustituyas una inspección
profesional.

### Pruebas

-   Imagen válida e inválida.
-   Imagen guardada offline.
-   Solicitud pendiente sin conexión.
-   Recuperación de conexión.
-   Respuesta de IA inválida.
-   API caída.
-   Reintentos sin duplicar solicitudes.
-   Confirmación y corrección de medidas.
-   Protección de fotografías privadas.

**Al terminar, detenete, presentá el informe y pedime autorización para
la etapa 4.**

------------------------------------------------------------------------

# ETAPA 4 --- SUPABASE, USUARIOS, OBRAS Y SINCRONIZACIÓN

## Objetivo

Implementar la persistencia remota, las cuentas y la sincronización
segura entre dispositivos.

### Funcionalidades

-   Registro e inicio de sesión.
-   Recuperación de acceso.
-   Perfiles.
-   Obras y tareas.
-   Materiales y precios.
-   Cálculos e historial.
-   Fotografías y documentos.
-   Presupuestos.
-   Registro de sincronización.

### Base de datos

Diseñá migraciones versionadas, claves foráneas, restricciones, índices
y políticas RLS.

No guardes importes como números de punto flotante cuando se necesite
precisión monetaria.

Definí las relaciones entre proyectos, usuarios, documentos y cálculos.

### Sincronización

-   Implementá una cola persistente de cambios.
-   Usá identificadores estables.
-   Procesá operaciones de forma idempotente.
-   No marques un cambio como sincronizado hasta confirmarlo.
-   Reintentá fallos recuperables.
-   Detectá conflictos entre dispositivos.
-   No sobrescribas silenciosamente cambios concurrentes.
-   Conservá los cambios pendientes cuando el usuario cierre sesión.
-   Permití recuperar errores de sincronización.
-   Mostrá claramente el estado de cada operación.

### Seguridad

Probá accesos con usuarios diferentes. Un usuario nunca debe acceder a
obras, fotografías o documentos privados de otro.

### Pruebas

-   Registro y sesión.
-   Proyecto creado offline y sincronizado después.
-   Edición desde dos dispositivos.
-   Sesión vencida.
-   Supabase temporalmente inaccesible.
-   Reintento sin duplicados.
-   Acceso cruzado bloqueado por RLS.
-   Cierre de sesión con cambios pendientes.
-   Conflictos y recuperación.

**Al terminar, detenete, presentá el informe y pedime autorización para
la etapa 5.**

------------------------------------------------------------------------

# ETAPA 5 --- MERCADO PAGO, SUSCRIPCIONES Y CONTROL DE ACCESO

## Objetivo

Integrar el sistema comercial sin comprometer la seguridad ni la
consistencia de los datos.

### Funcionalidades

-   Planes mensuales, trimestrales, semestrales y anuales cuando estén
    soportados por la modalidad elegida.
-   Checkout.
-   Confirmación de pagos.
-   Webhooks.
-   Control de acceso.
-   Cancelaciones y renovaciones.
-   Historial de suscripción.
-   Manejo de pagos rechazados.

### Reglas

-   Verificá la documentación oficial vigente de Mercado Pago.
-   No confíes en redirecciones del navegador como prueba de pago.
-   Validá las notificaciones.
-   Consultá los estados oficiales cuando corresponda.
-   Procesá eventos de forma idempotente.
-   No sumes días de suscripción por cada webhook.
-   No habilites funciones pagas con estados no confirmados.
-   Conservá el historial de operaciones.
-   No permitas que el cliente cambie su propio plan o privilegios.
-   No borres los proyectos de un usuario porque su suscripción haya
    vencido.

### Funcionamiento offline

Las operaciones de pago requieren conexión. Si el usuario está offline:

-   No simules un pago.
-   No alteres la suscripción localmente.
-   Mostrá un mensaje claro.
-   Conservá los datos que el usuario estaba utilizando.
-   Permití retomar el flujo cuando vuelva la conexión.

La aplicación puede permitir consultar información local, pero no debe
confiar en una copia offline para autorizar privilegios comerciales.

### Pruebas

Probá pagos aprobados, rechazados, pendientes, duplicados,
cancelaciones, renovaciones y eventos fuera de orden en entornos de
prueba.

**Al terminar, detenete, presentá el informe y pedime autorización para
la etapa 6.**

------------------------------------------------------------------------

# ETAPA 6 --- ROBUSTEZ, ACCESIBILIDAD, PERFORMANCE Y LANZAMIENTO

## Objetivo

Verificar la integración completa de la aplicación, resolver problemas
pendientes y preparar una publicación controlada.

### Pruebas integrales

Probá los recorridos completos:

1.  Crear una obra.
2.  Guardarla sin internet.
3.  Cerrar y reabrir la PWA offline.
4.  Calcular materiales.
5.  Registrar fotografías.
6.  Generar un presupuesto.
7.  Recuperar conexión.
8.  Sincronizar los cambios.
9.  Abrir la obra desde otro dispositivo.
10. Confirmar que no existan duplicados.
11. Verificar permisos.
12. Comprobar el acceso según la suscripción.
13. Recuperarse de errores de red y servicios externos.

### Performance

-   Evitá JavaScript innecesario.
-   Reducí el tamaño de los recursos.
-   Optimizá imágenes.
-   Cargá funciones pesadas cuando sean necesarias.
-   Evitá consultas duplicadas.
-   Paginá listados extensos.
-   Revisá índices de la base de datos.
-   Evitá bloqueos prolongados de la interfaz.
-   Reducí consumo de batería y datos móviles.
-   Medí el rendimiento en un dispositivo móvil real.

Utilizá Lighthouse y otras herramientas adecuadas cuando estén
disponibles. Revisá accesibilidad, rendimiento, buenas prácticas y PWA
sin tratar una puntuación automática como garantía de calidad.

### Accesibilidad

Revisá navegación por teclado, contraste, áreas táctiles, formularios,
foco, lector de pantalla y estados de sincronización.

### Pruebas offline finales

Repetí las pruebas en modo avión y con conexión intermitente. Verificá
que los cambios sobrevivan al cierre y reapertura de la aplicación y que
las actualizaciones no eliminen datos pendientes.

### Seguridad final

-   Revisá RLS.
-   Revisá los secretos.
-   Revisá los permisos de archivos.
-   Revisá los webhooks.
-   Revisá las dependencias.
-   Revisá los errores expuestos al usuario.
-   Revisá la sincronización y sus conflictos.
-   Documentá riesgos pendientes.

### Despliegue

Documentá configuración, variables de entorno, migraciones, credenciales
de prueba, despliegue, recuperación y copias de seguridad según las
capacidades reales de los servicios contratados.

No ejecutes cambios destructivos en producción sin autorización.

**Al terminar, detenete y presentame el informe final. No publiques la
aplicación en producción ni realices operaciones comerciales reales sin
mi autorización explícita.**

------------------------------------------------------------------------

# 7. CATÁLOGO DE PRUEBAS Y CALIDAD

A lo largo de las seis etapas, mantené pruebas automatizadas y manuales.

Incluí escenarios de:

-   Usuario nuevo.
-   Usuario con varios proyectos.
-   Sesión vencida.
-   Acceso desde distintos dispositivos.
-   Conexión interrumpida.
-   Sincronización duplicada.
-   Conflictos de edición.
-   Almacenamiento local insuficiente.
-   Imagen ilegible.
-   API de IA caída.
-   Precio ausente.
-   Unidades incompatibles.
-   Cálculo inválido.
-   PDF con datos incompletos.
-   Pago rechazado.
-   Webhook duplicado.
-   Usuario que intenta acceder a datos ajenos.
-   Actualización de la PWA con cambios pendientes.

No fijes un número arbitrario de tests como objetivo de calidad. Cada
prueba debe comprobar un comportamiento concreto y tener un resultado
esperado.

Mantené separados los tests unitarios, los de integración y los de
extremo a extremo.

Los mocks sirven para pruebas controladas, pero no demuestran que una
integración real funcione.

------------------------------------------------------------------------

# 8. ORGANIZACIÓN DEL CÓDIGO Y DOCUMENTACIÓN

Usá una estructura modular semejante a:

-   `src/app/`
-   `src/components/`
-   `src/features/calculator/`
-   `src/features/vision/`
-   `src/features/projects/`
-   `src/features/assistant/`
-   `src/features/budgets/`
-   `src/features/billing/`
-   `src/features/offline/`
-   `src/lib/`
-   `src/lib/security/`
-   `src/lib/validation/`
-   `src/types/`
-   `supabase/migrations/`
-   `tests/`
-   `docs/`

Adaptá esta estructura al repositorio existente. No dupliques módulos
innecesariamente.

Documentá: - Arquitectura. - Modelo de datos. - Estrategia offline. -
Reglas de sincronización. - Conflictos. - Integraciones externas. -
Seguridad. - Fórmulas. - Pruebas. - Despliegue. - Limitaciones.

------------------------------------------------------------------------

# 9. CRITERIOS DE TERMINACIÓN

La aplicación solo podrá considerarse candidata a publicación cuando:

-   Las seis etapas hayan sido implementadas y revisadas.
-   El usuario haya aprobado cada etapa.
-   Las pruebas pertinentes hayan pasado.
-   Las limitaciones estén documentadas.
-   La aplicación funcione en dispositivos móviles reales.
-   Las funciones offline estén verificadas en modo avión.
-   Los datos sobrevivan al cierre y reapertura.
-   La sincronización sea recuperable y no duplique operaciones.
-   Los permisos de usuarios estén protegidos.
-   Los cálculos tengan fórmulas y pruebas documentadas.
-   Los pagos estén validados en el entorno correspondiente.
-   Las integraciones críticas hayan sido probadas realmente.
-   La accesibilidad y la performance hayan sido revisadas.
-   Exista documentación suficiente para instalar y mantener el
    proyecto.

Diferenciá siempre:

-   Implementado.
-   Probado automáticamente.
-   Probado manualmente.
-   Validado en dispositivo real.
-   Validado con servicio externo real.
-   Pendiente de credenciales.
-   Pendiente de revisión profesional.
-   No implementado.

No afirmes que una auditoría de seguridad es completa por ejecutar un
escáner. No afirmes que una aplicación está lista para producción si
quedan riesgos críticos sin resolver.

------------------------------------------------------------------------

# 10. INSTRUCCIÓN INICIAL OBLIGATORIA

Comenzá únicamente con la **ETAPA 1**.

Primero inspeccioná el repositorio y presentame un diagnóstico inicial,
un plan de implementación y los criterios de aceptación de esa etapa.

Después implementá solamente la etapa 1, ejecutá las pruebas
correspondientes, corregí los errores y presentame el informe.

Terminá preguntándome:

**«¿Probaste la etapa 1 y autorizás que avance a la etapa 2?»**

Después de esa pregunta, detené el trabajo y esperá mi respuesta.

No comiences la etapa 2 bajo ninguna circunstancia hasta recibir mi
aprobación explícita.

**La prioridad de OBRA TOTAL AR es construir una herramienta útil,
rápida, accesible y confiable para albañiles argentinos, especialmente
en obras donde no hay internet. La calidad se demuestra con pruebas
reales, no con la cantidad de código generado.**
