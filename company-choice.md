# Elección de Empresa: TrackFlow

## Empresa Elegida y Justificación
He elegido trabajar con **TrackFlow** para el desarrollo de mi proyecto en el programa de AI Engineering. La  razón principal de mi elección es la atractiva intersección entre el software de inteligencia artificial y la logística del mundo físico transfronterizo. TrackFlow opera con una alta complejidad real al gestionar dos almacenes en países distintos (Estados Unidos y España) bajo infraestructuras tecnológicas completamente fragmentadas. Desarrollar soluciones para esta empresa representa un reto de ingeniería de datos e IA muy concreto, donde cada optimización algorítmica impacta directamente en el movimiento de un paquete real y en la eficiencia operativa global del negocio.

---

## Departamentos con Problemas más Interesantes

1. **🔄 Logística Inversa (Sofía Ramos):** El volumen de devoluciones es masivo (entre el 18% y el 25%) y actualmente depende por completo de la revisión y el criterio subjetivo humano de los operarios. La necesidad de implementar un sistema de inspección asistido por IA que clasifique el estado del producto mediante imágenes (Visión Computacional) es un reto técnico fascinante que combina el procesamiento de datos multimedia con la toma de decisiones automatizada en tiempo real.

2. **📞 Experiencia del Cliente - CX (Valentina Cruz):**
   La gestión de canales fragmentados (WhatsApp, email, teléfono) para atender tanto a marcas B2B como a consumidores B2C genera un cuello de botella crítico, especialmente cuando el 80% de las consultas son repetitivas. Diseñar una infraestructura unificada y una base de conocimientos semántica que funcione 24/7 en un entorno bilingüe es un reto de procesamiento de lenguaje natural (NLP) con un retorno de inversión inmediato y medible.

---

## Reto de Automatización e IA Seleccionado
El reto del *milestone map* que más ganas tengo de construir es el **Agente de CX de primera línea integrado con arquitectura RAG (Retrieval-Augmented Generation)** y un conector unificado de tracking. Este reto me permitirá dominar la orquestación de modelos de lenguaje, el indexado semántico de políticas logísticas complejas y la conexión con APIs externas para resolver problemas críticos de negocio en tiempo real.

---

## Mi idea de Agente de IA

### Propuesta: Agente Inteligente de Soporte y Rastreo (FlowBot)

**¿Qué haría el agente?**
Este agente actuará como la primera línea de defensa en los canales de atención (WhatsApp, email y web). Atenderá de forma autónoma y multilingüe (español e inglés) tanto a los consumidores finales como a las marcas aliadas. El agente entenderá las intenciones del usuario en lenguaje natural, responderá preguntas frecuentes sobre políticas logísticas y resolverá de forma inmediata las dudas de estado de envíos y devoluciones sin necesidad de intervención humana, escalando a un agente real solo los casos complejos o de clientes frustrados.

**¿Qué información necesitaría?**
Para funcionar correctamente, el agente requerirá acceso integrado a tres fuentes de datos:
1. **Endpoint unificado de tracking:** Para consultar en tiempo real el estado real de los paquetes en los 8 transportistas.
2. **Base de conocimiento semántica (RAG):** Un índice con las políticas de envío, tiempos de entrega y normativas de devolución de cada marca.
3. **Historial y datos del cliente:** Para verificar la identidad de quien consulta (mediante su número de pedido, email o teléfono) antes de revelar información sensible.

**¿Qué produciría o desencadenaría?**
* **Respuestas inmediatas:** Mensajes claros con el estado del paquete, links de seguimiento público o instrucciones detalladas para iniciar una devolución.
* **Creación y etiquetado de tickets:** En caso de no poder resolver el problema (por ejemplo, un paquete extraviado), creará un ticket en el sistema unificado con un resumen de la conversación y una etiqueta de **"Análisis de sentimiento: Frustrado"** para que los agentes humanos prioricen el caso.
* **Actualización del CRM:** Dejará un registro automático de la interacción en el perfil unificado del cliente para que el equipo comercial sepa qué dudas o incidencias ha tenido esa cuenta.
