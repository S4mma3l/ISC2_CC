### Resumen

#### Temas principales

1. **Endurecimiento de sistemas**: El proceso de aplicar configuraciones seguras para reducir la superficie de ataque en hardware, software y sistemas operativos.
    
    - Mejores prácticas incluyen configuraciones basadas en estándares de seguridad y actualizaciones regulares.
2. **Ciclo de vida de los datos**: Desde la creación hasta la destrucción.
    
    - **Crear**: Generar conocimiento tácito.
    - **Almacenar**: Convertir conocimiento en explícito y protegerlo.
    - **Usar**: Modificar o complementar información según su aplicación.
    - **Compartir**: Transferir datos entre usuarios o ubicaciones.
    - **Archivar**: Preservar datos que no se utilizan activamente.
    - **Destruir**: Eliminar datos de forma definitiva cuando ya no son necesarios.
3. **Clasificación y etiquetado**: Identificar la sensibilidad de los datos y asignar niveles de protección.
    
    - **Clasificaciones comunes**:
        - Altamente restringido: Pérdida severa de datos.
        - Moderadamente restringido: Pérdida de competitividad.
        - Sensibilidad baja: Impactos menores.
4. **Cifrado y hashing**:
    
    - **Cifrado simétrico**: Usa una sola clave para cifrar y descifrar.
    - **Cifrado asimétrico**: Utiliza una clave pública y una clave privada.
    - **Hashing**: Garantiza integridad creando un resumen único y no reversible.
5. **Gestion de configuración**:
    
    - **Líneas base**: Niveles mínimos de protección.
    - **Control de cambios**: Revisar y aprobar modificaciones.
    - **Auditorías**: Validar que los cambios cumplan estándares.
6. **Gestion de parches**: Actualizar sistemas para corregir vulnerabilidades.
    
    - **Problemas comunes**: Riesgos de parches defectuosos y entornos de prueba limitados.
7. **Registro y monitoreo**: Captura y revisión de eventos clave en sistemas.
    
    - **Elementos registrados**: Actividades del sistema, intentos de acceso y cambios en configuración.

---

### Glosario

1. **Ciclo de vida de los datos**: Etapas por las que pasan los datos desde su creación hasta su destrucción.
2. **Hashing**: Proceso criptográfico que genera un resumen de datos.
3. **Clave simétrica**: Misma clave para cifrar y descifrar.
4. **Clave asimétrica**: Par de claves (pública y privada) para cifrar y descifrar.
5. **Endurecimiento**: Aplicación de configuraciones seguras.
6. **Línea base**: Nivel mínimo de protección para sistemas o datos.
7. **DLP (Data Loss Prevention)**: Tecnología para prevenir la pérdida de datos.
8. **PCI DSS**: Estándares de seguridad para proteger datos de tarjetas de crédito.

---

### Información para examen

1. **Entender el ciclo de vida de los datos**: Desde su creación hasta su destrucción.
2. **Conocer las diferencias entre cifrado simétrico y asimétrico**.
3. **Aplicar prácticas de gestión de configuración**: Uso de líneas base, auditorías y control de cambios.
4. **Reconocer la importancia del registro y monitoreo**: Detectar y prevenir incidentes.

---

### Examen

#### Preguntas

1. **¿Cuál es el propósito principal del hashing?**
    
    - a) Garantizar confidencialidad.
    - b) Proveer autenticación.
    - c) Garantizar integridad.
    - d) Facilitar el acceso rápido.
    - **Respuesta Correcta:** c) Garantizar integridad.
2. **¿Qué es una línea base de seguridad?**
    
    - a) Un nivel máximo de protección.
    - b) Un nivel mínimo de protección aceptable.
    - c) Un conjunto de controles redundantes.
    - d) Un proceso para destruir datos.
    - **Respuesta Correcta:** b) Un nivel mínimo de protección aceptable.
3. **¿Cuál es una ventaja del cifrado asimétrico sobre el simétrico?**
    
    - a) Más rápido para datos masivos.
    - b) Requiere menos claves para usuarios múltiples.
    - c) No necesita clave privada.
    - d) Garantiza el anonimato completo.
    - **Respuesta Correcta:** b) Requiere menos claves para usuarios múltiples.
4. **¿Qué tecnología previene la pérdida de datos sensibles?**
    
    - a) Hashing.
    - b) DLP.
    - c) PKI.
    - d) IDS.
    - **Respuesta Correcta:** b) DLP.
5. **¿Cuál es un riesgo asociado con la aplicación de parches?**
    
    - a) Aumentar el rendimiento del sistema.
    - b) Introducir vulnerabilidades adicionales.
    - c) Reducir la necesidad de auditorías.
    - d) Evitar el uso de líneas base.
    - **Respuesta Correcta:** b) Introducir vulnerabilidades adicionales.