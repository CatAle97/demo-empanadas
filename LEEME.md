# Demo — Empanadas Doña Rosa

Sistema de demostración para la reunión del **lunes 3 de agosto de 2026**.

## Cómo abrirlo

Doble clic en `index.html`. Se abre en el navegador. No necesita internet ni instalar nada.

**PIN de acceso:**
- Cajera → `1234`
- Dueño → `4321` (aquí está el stock, los reportes y la configuración)

## Importante

- **Negocio ficticio.** Ningún dato es real.
- **No está conectado a ninguna base de datos.** Todo vive en este navegador. No puede tocar los datos de Bob's ni de ningún otro sistema.
- Para dejarlo como nuevo antes de la reunión: **Dueño → Config → 🔄 Reiniciar demostración**.

---

## Guion sugerido (7 minutos)

### 1. Abrir con el problema, no con el sistema
> "¿Ella hoy cómo sabe cuántas cajas le quedan? ¿Cuenta a fin de día?"

Deja que conteste. El sistema se vende solo después de esa respuesta.

### 2. Vender una empanada — entrar como **Cajera** (1234)
- Cliente: cualquier nombre
- Marcar **🥡 Llevar**
- Tocar **Empanada de Carne** → agregar → cobrar

### 3. El momento clave — entrar como **Dueño** (4321) → **Stock**

Muestra que bajó **solo**:

| Insumo | Bajó |
|---|---|
| Masa de empanada | 1 |
| Carne molida | 80 gr |
| Cebolla | 30 gr |
| Servilleta | 1 |
| **Bolsa de papel** | **1** |
| **Etiqueta** | **1** |

> "No descontó la empanada nomás. Descontó la bolsa y la etiqueta que se fueron con ella."

### 4. El detalle que cierra la venta

Vende la **misma** empanada pero en **🍽️ Mesa**.

> "Mira: la servilleta sí se gastó, la bolsa no. Porque el que come acá no se lleva bolsa. El sistema sabe la diferencia."

Ese detalle es el que no tiene ningún sistema genérico.

### 5. Las alertas ya están puestas a propósito

En Stock verá dos avisos en rojo esperándolo:
- **Queso** — 0.8 kg (mínimo 1)
- **Caja x6** — 15 unidades (mínimo 20)

> "Esto le avisa antes de quedarse sin cajas un sábado a las 8 de la noche."

### 6. Cerrar con el dinero — **Dashboard**

Gastos fijos del mes cargados (alquiler, luz, sueldo) y cuánto necesita vender por día para cubrirlos.

> "No es solo para controlar stock. Es para saber si el mes le cierra."

---

## Si pregunta "¿y esto cuánto cuesta?"

No improvises un precio en la reunión. Respuesta segura:

> "Depende de qué tanto quieras. Déjame ver bien qué vende y te paso una propuesta con dos opciones."

Ganas tiempo y evitas anclarte a un número bajo.

## Si pregunta "¿esto ya funciona o es una maqueta?"

Es honesto decir: **funciona de verdad, está corriendo ahora mismo.** Lo que falta es cargarle SUS productos y SUS insumos, que es cuestión de horas, no de meses.

---

## Ajustar datos en vivo

Si te dice "yo vendo X a S/Y", puedes cambiarlo delante de él:

**Dueño → Config → 🍳 Recetas de productos** → ahí se crean productos, se editan precios y se arma qué insumo consume cada uno.

Que te vea hacerlo en 30 segundos vale más que cualquier promesa.
