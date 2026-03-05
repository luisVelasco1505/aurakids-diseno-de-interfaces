# Design System - AuraKids

## 1. Design Tokens
* **Color Principal:** #4A90E2 (Azul Confianza - para padres)
* **Color Secundario:** #7ED321 (Verde Bienestar - para niños)
* **Color de Error:** #D0021B (Rojo Alerta - límites excedidos)
* **Tipografía:** Quicksand (Redondeada y legible)
* **Espaciados:** Small (8px), Medium (16px), Large (32px)

## 🎨 Prototipo en Figma enlace
https://www.figma.com/design/LkMizphHQtS0vSCjbQjRYh/tokems?node-id=0-1&t=FagDxFJiC2lDISrW-1
<img width="1100" height="740" alt="image" src="https://github.com/user-attachments/assets/787da0f9-5a87-4529-af26-f95c26cafbc2" />


## 2. Pattern Library (Componentes)
---
# 1. Botones (Buttons)
Componentes de interacción principal con jerarquía visual clara.

* **Botón Primario (Solid):** Rectángulo gris oscuro con esquinas redondeadas (**10px**) y texto blanco centrado. Uso: *Registrarse*, *Configurar recordatorio*.
* **Botón de Rol (Pill Button):** Bordes totalmente redondeados (píldora). Uso: Selección de perfil (*Padre/Madre* vs. *Niño/a*).
* **Botón de Acción Secundaria:** Versión reducida del botón primario. Uso: Acciones dentro de tarjetas como *Agregar reto*.
* **Text Link:** Texto simple subrayado. Uso: Navegación alterna (*¿Ya tienes cuenta?*).

---

# 2. Formularios y Entradas 
Elementos para la captura de datos y configuración de límites.

| Componente | Descripción | Uso |
| :--- | :--- | :--- |
| **Campo Estándar** | Fondo gris claro y bordes suavizados. | Nombre, Correo, Contraseña. |
| **Input con Icono** | Campo que integra un icono de cámara a la izquierda. | Carga de foto de perfil. |
| **Área de Texto** | Campo amplio para escritura libre. | Sección "Estado emocional". |
| **Selector de Tiempo** | Bloques oscuros para definir rangos horarios. | Configuración de acuerdos (ej. 9:00 PM). |

---

# 3. Tarjetas y Contenedores 
Estructuras para organizar la información en el Dashboard.

* **Indicator Card (Dashboard):** Tarjeta blanca redondeada con icono circular, título (ej. "Sueño/Descanso") y enlace "Ver más".
* **Alert Card:** Contenedor crítico que agrupa icono, estado (ej. "Riesgo Alto") y descripción del evento.
* **Resource Card:** Cuadrícula con área para ilustración y título descriptivo. Uso: *Recursos educativos*.

---

# 4. Navegación y Menús 
Estructura constante para el flujo del usuario.

* **Tab Bar (Global):** Barra inferior fija con 4 iconos y etiquetas: *Inicio, Alertas, Acuerdos y Perfil*.
* **Top Bar (Header):** Incluye flecha de retroceso (izquierda), título de sección centrado e icono de campana (derecha).

---

# 5. Componentes Especializados
Elementos diseñados específicamente para la experiencia AuraKids.

* **Mood Selector:** Fila de 6 iconos gestuales (caritas) con etiquetas: *Feliz, Emocionado, Enfadado, Neutral, Preocupado, Triste*.
* **Progress Tracker:** Sistema de iconos de estrellas para marcar el cumplimiento de metas (ej. "2 de 5 días").
* **Infographic Block:** Bloques con iconos de seguridad (escudo) para la sección de *Transparencia*.

---------------
#Link del prototipo en el cual nos basamos para el PATTER LIBRARY 
* https://www.figma.com/design/ZdJWcUtmy8PLkOEzwDMFw0/wireframes-AuraKids--copia-?node-id=0-1&p=f
* <img width="1340" height="849" alt="image" src="https://github.com/user-attachments/assets/3f8056ec-b18c-4e0c-b98e-b1c1388eade0" />
<img width="356" height="721" alt="image" src="https://github.com/user-attachments/assets/6ec10758-0f0f-4107-81d7-8494381d1ed2" />


## 3. Reglas del Sistema
* Los botones de "Bloqueo" siempre deben ser rojos.
* No usar más de 2 fuentes distintas en una misma pantalla.
* Las tarjetas deben tener una sombra suave (shadow-sm) para dar profundidad.
