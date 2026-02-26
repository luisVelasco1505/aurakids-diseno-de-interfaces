# Etapa 1 – Análisis del Sistema

## Nombre del Proyecto
AuraKids – Aplicación de Control Parental y Bienestar Digital

---

## Integrantes
- Luis Olmedo Velasco Chate
- Allison Valentina Garcia Camacho
- Daniel Alejandro Perez Nieto


---

## Problema que se quiere resolver

En la actualidad, los niños y adolescentes tienen acceso constante a dispositivos móviles, lo que ha incrementado los riesgos asociados al uso excesivo de pantallas, exposición a contenido inapropiado y afectaciones en el bienestar emocional y físico.

Muchos padres no cuentan con herramientas claras y accesibles que les permitan monitorear y acompañar el uso digital de sus hijos de manera preventiva y educativa.

AuraKids busca ofrecer una solución móvil que permita gestionar el control parental desde un enfoque de bienestar, promoviendo hábitos digitales saludables y fortaleciendo la comunicación familiar.

---

## Usuarios del Sistema

### Usuario Primario
Padre, madre o tutor legal.
- Edad aproximada: 25–50 años.
- Nivel tecnológico: Medio.
- Necesidad principal: Supervisar y establecer reglas de uso digital.

### Usuario Secundario
Niño, niña o adolescente.
- Edad aproximada: 6–15 años.
- Necesidad principal: Comprender sus hábitos digitales y participar en acuerdos familiares.

---

## Entrada – Proceso – Salida del Sistema

### Entrada
- Registro de usuarios.
- Configuración de acuerdos y reglas.
- Datos de uso del dispositivo.
- Registro emocional del menor.

### Proceso
- Análisis del tiempo de uso.
- Comparación con reglas establecidas.
- Generación de indicadores de bienestar.
- Detección de posibles riesgos digitales.

### Salida
- Alertas.
- Reportes visuales.
- Indicadores de bienestar.
- Recomendaciones educativas.
- Notificaciones al tutor.

---

## Alcance del Sistema

### Incluye
- Registro y autenticación de usuarios.
- Gestión de perfiles familiares.
- Configuración de acuerdos de uso.
- Visualización de indicadores.
- Sistema de alertas.
- Registro emocional básico.
- Recursos educativos digitales.

### No Incluye
- Bloqueo avanzado a nivel sistema operativo.
- Integración directa con redes sociales externas.
- Sistema de pagos.
- Inteligencia artificial predictiva avanzada.

---

## Arquitectura de la Información

El sistema se estructura en cinco módulos principales dentro de una navegación inferior (Bottom Navigation):

1. Inicio (Dashboard)
2. Alertas
3. Acuerdos
4. Recursos
5. Perfil

### Jerarquía del Contenido

- Nivel 1: Navegación principal (menú inferior).
- Nivel 2: Secciones internas (indicadores, lista de alertas, acuerdos).
- Nivel 3: Pantallas de detalle (detalle de indicador, configuración de regla).

---

## Patrones de Navegación

- Bottom Navigation.
- Navegación jerárquica (Inicio → Detalle).
- Botón de retroceso (Back).
- Scroll vertical.
- Tarjetas como acceso a información detallada.

---

## Patrones de Interacción

- Botones Call To Action (CTA).
- Formularios con validación.
- Toggle switches para activar/desactivar reglas.
- Modales de confirmación.
- Notificaciones tipo alerta.
- Retroalimentación visual tras acciones del usuario.

---

## Sistema Operativo Considerado

El diseño se desarrollará bajo lineamientos de Android (Material Design), considerando:

- Uso de Bottom Navigation.
- Uso de botones flotantes (FAB) cuando aplique.
- Jerarquía clara de acciones principales.
- Retroalimentación inmediata mediante mensajes tipo Snackbar.

---

## Fidelidad del Prototipo

Los wireframes desarrollados corresponden a baja fidelidad, en blanco y negro, sin uso de imágenes reales ni colores, con el fin de centrar el análisis en la estructura, jerarquía y arquitectura de la información.
