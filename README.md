# 🏥 <span style="color: #e74c3c;">Remanso FarmaTech</span>  
**<span style="color: #2c3e50;">Solución inteligente para la gestión de medicamentos y atención al cliente</span>**

<div align="center">
  <img src="./TRIMESTRE%201/2.%20COMPONENTE%20METODOLOGICO/logo.png" alt="Logo Remanso FarmaTech" width="120" style="border-radius: 8px;" />
</div>

---

## <span style="color: #f59e0b;">📌 Introducción</span>

En la actualidad, la transformación digital se ha convertido en un factor clave para la competitividad y sostenibilidad de las microempresas, especialmente en el sector comercial y farmacéutico. Muchas droguerías pequeñas aún gestionan sus procesos de inventario y ventas de forma manual, lo que genera dificultades en el control de productos, pérdidas por vencimientos y limitaciones en la atención al cliente.

La droguería Remansó no es ajena a esta problemática, ya que opera bajo un modelo tradicional que restringe su crecimiento y eficiencia. Ante esta situación, surge la necesidad de implementar una solución tecnológica que permita optimizar sus procesos internos y mejorar la experiencia de los usuarios.

El presente proyecto, desarrollado en el marco del programa de **Tecnología en Análisis y Desarrollo de Software (SENA)**, tiene como propósito el diseño e implementación de una plataforma web denominada **FarmaTech**, orientada a la gestión de inventario y la comercialización de productos a través de una tienda virtual.

Mediante esta solución, se busca automatizar el control de inventarios, facilitar la gestión de pedidos y permitir a los clientes consultar y adquirir productos de manera digital, contribuyendo así a la modernización del negocio y al fortalecimiento de su competitividad en el mercado.

---

## <span style="color: #8b5cf6;">🧩 Nombre del Proyecto</span>

**Desarrollo de un Sistema de Información para la Gestión de Inventario y Ventas en la Droguería Remansó**

**Nombre comercial:**  
**Remanso FarmaTech**

---

## <span style="color: #dc2626;">⚠️ 1. Planteamiento del Problema</span>

La droguería Remansó representa un negocio microempresarial que opera de manera tradicional, donde las ventas se realizan únicamente de forma presencial y el control de inventario se lleva de forma manual o semiautomática. Estas condiciones generan problemas como:

- Dificultad en el control de stock  
- Riesgo de escasez o vencimiento de productos  
- Errores en el registro de ventas  
- Limitaciones en la expansión del negocio  

Además, la ausencia de una plataforma digital impide a los clientes consultar productos, verificar disponibilidad o realizar pedidos en línea, lo que reduce la competitividad frente a grandes cadenas farmacéuticas.

---

## <span style="color: #3b82f6;">❓ 2. Pregunta Problema</span>

¿Cómo desarrollar una plataforma web que permita transformar la gestión de inventario y ventas de la droguería Remansó, optimizando sus procesos administrativos y ampliando su alcance comercial?

---

## <span style="color: #059669;">📖 3. Justificación</span>

El desarrollo de **Remanso FarmaTech** responde a la necesidad de implementar una solución tecnológica que contribuya a la modernización de la droguería Remansó, mejorando el control de inventarios, reduciendo errores manuales y optimizando la atención al cliente.

Desde el enfoque formativo del SENA, este proyecto permite aplicar competencias en:

- Análisis de requerimientos  
- Diseño de bases de datos  
- Desarrollo de aplicaciones web  
- Arquitectura cliente-servidor  
- Integración de APIs (pasarela de pago)  
- Seguridad y validación de datos  

Asimismo, fortalece la transformación digital de una microempresa, mejorando su competitividad y sostenibilidad.

---

## <span style="color: #10b981;">🎯 4. Objetivo General</span>

Desarrollar un sistema web para la droguería Remansó que permita gestionar el inventario y las ventas en línea, optimizando los procesos administrativos y mejorando la atención al cliente.

---

## <span style="color: #10b981;">🎯 5. Objetivos Específicos</span>

- Diseñar el modelo de datos para productos, inventario y pedidos  
- Desarrollar una interfaz web intuitiva para la compra de productos  
- Implementar un módulo administrativo  
- Integrar una pasarela de pago en modo sandbox  
- Implementar un sistema de alertas (compras y stock bajo)  

---

## <span style="color: #6366f1;">📦 6. Alcance del Proyecto</span>

El sistema permitirá:

- Control de inventario en tiempo real  
- Registro y gestión de productos  
- Generación de pedidos  
- Organización eficiente de la información  
- Apoyo en la toma de decisiones  

Está dirigido principalmente al personal administrativo, pero también permitirá interacción con clientes.

---

## <span style="color: #ef4444;">🚫 7. Limitaciones</span>

### 7.1 Alcance Funcional Incluido

- ✔ Aplicación web responsive  
- ✔ Registro e inicio de sesión  
- ✔ Catálogo de productos  
- ✔ Carrito de compras  
- ✔ Integración de pagos (sandbox)  
- ✔ Panel administrativo  
- ✔ Alertas de stock y pedidos  
- ✔ Base de datos relacional  

---

### 7.2 Exclusiones del Alcance

- ❌ Aplicación móvil nativa  
- ❌ Integración con EPS  
- ❌ Facturación electrónica DIAN  
- ❌ Venta de medicamentos controlados  
- ❌ Integración con ERP externos  

---

## ⚙️ 8. Requerimientos Funcionales

| ID | Requerimiento |
|----|-------------|
| RF-01 | Registro de usuarios |
| RF-02 | Inicio de sesión |
| RF-03 | Consulta de productos |
| RF-04 | Búsqueda de productos |
| RF-05 | Carrito de compras |
| RF-06 | Generación de pedidos |
| RF-07 | Procesamiento de pagos |
| RF-08 | Actualización de inventario |
| RF-09 | Gestión de productos (CRUD) |
| RF-10 | Notificaciones de pedidos y stock |

---

## ⚙️ 9. Requerimientos No Funcionales

| ID | Requerimiento |
|----|-------------|
| RNF-01 | Seguridad mediante autenticación y HTTPS |
| RNF-02 | Disponibilidad del sistema ≥ 95% |
| RNF-03 | Tiempo de respuesta ≤ 3 segundos |
| RNF-04 | Interfaz amigable (usabilidad) |
| RNF-05 | Compatibilidad con navegadores |
| RNF-06 | Escalabilidad del sistema |
| RNF-07 | Mantenibilidad (arquitectura modular) |

---

## 🏗️ 10. Tecnologías Sugeridas

- **Frontend:** Next.js / React  
- **Backend:** Node.js + Express  
- **Base de datos:** MySQL / PostgreSQL  
- **Pagos:** Wompi / Mercado Pago (sandbox)  

---

## 🚀 11. Impacto Esperado

- Mejor control del inventario  
- Reducción de pérdidas  
- Mayor eficiencia operativa  
- Incremento en ventas  
- Transformación digital del negocio  

## 🚀 12. Modelo BPMN

![Modelo BPMN](./TRIMESTRE%201/3.%20BPMN/Modelo%20BPMN.PNG)

### Macroprocesos

![MacroProceso 1](./TRIMESTRE%201/3.%20BPMN/MacroProceso%201.PNG)
![MacroProceso 2](./TRIMESTRE%201/3.%20BPMN/Macroproceso%202.PNG)