## Matriz de Vulnerabilidades Detectadas

| Vulnerabilidad | Origen | Amenaza | Tipo | CID Afectada |
| :--- | :--- | :--- | :--- | :--- |
| **Postit's con contraseñas** | Uso | Cualquiera que los lea tiene acceso a las contraseñas | Físico deriva a lógico | Confidencialidad |
| **Ausencia de SAI** | Diseño | Una subida de tensión o una caída de corriente eléctrica apaga todo repentinamente | Físico deriva en lógico | Disponibilidad |
| **Servidor principal/impresión expuesto en mesa** | Diseño | Robo, manipulación no autorizada, daños accidentales o desconexión física del servidor por estar en un área común | Físico deriva a lógico | Confidencialidad, Integridad y Disponibilidad |
| **Carpeta compartida accesible a clientes en el servidor interno** | Diseño / Implementación | Alguien acceder a datos confidenciales internos, modificar archivos o colar malware en la red local | Lógico | Confidencialidad e Integridad |
| **Documentación sensible/planos expuestos en mesas y estanterías** | Uso | Personas no autorizadas (visitantes, clientes, personal externo) pueden visualizar información confidencial de proyectos (*shoulder surfing*) | Físico | Confidencialidad |
| **Cableado y regletas desorganizadas en el suelo** | Implementación / Uso | Desconexión accidental de equipos/servidor por tropezón o fallo eléctrico por tirones de cable | Físico deriva a lógico | Disponibilidad |
| **Monitores orientados hacia zonas de paso o ventanasa** | Diseño | Clientes o visitantes pueden visualizar información confidencial o pantallas activas mientras caminan por la oficina | Físico | Confidencialidad |
| **Falta de bloqueo automático de sesión en las estaciones de trabajo** | Uso | Un tercero puede interactuar con la sesión abierta de un usuario cuando este se ausenta de su puesto | Lógico | Confidencialidad e Integridad |
| **Ausencia de trituradora de papel para destrucción segura** | Uso | Filtración de datos confidenciales al desechar borradores o planos impresos directamente en papeleras comunes | Físico | Confidencialidad |
| **Impresión centralizada de gran formato sin autenticación/pull printing** | Configuración | Documentos planos o proyectos impresos quedan expuestos en las bandejas de los plotters sin supervisión del propietario | Físico | Confidencialidad |
| **Uso de red Wi-Fi o local sin segmentación de invitados** | Configuración / Diseño | Dispositivos de clientes o móviles personales pueden interceptar tráfico local o escanear puertos de los equipos corporativos | Lógico | Confidencialidad e Integridad |
| **Gestión centralizada de impresoras desde un SO cliente** | Diseño / Configuración | Si el equipo portátil falla o se reinicia por actualización, se interrumpe el servicio de impresión de toda la oficina | Lógico | Disponibilidad |
| **Ausencia de un sistema de copias de seguridad aislado** | Diseño | Infección por ransomware o fallo de disco en el servidor/portátil provocaría la pérdida irrecuperable de proyectos | Lógico | Disponibilidad e Integridad |
