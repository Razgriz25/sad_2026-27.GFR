# Informe de auditoría de vulnerabilidades 

## 1. Contexto y alcance
Se ha analizado un informe completo conteniendo los elementos expuestos de una maquina MetaSploitable2 incluyendo, puertos, configuraciones, servicios, vulnerabilidades o versiones desactualizadas.  
Con el propósito de entender y comprender los diferentes tipos de vulnerabilidades y sus caracteristicas

## 2. Metodología
Se ha realizado un Basic Network Scan en Nessus con la dirección IPv4 de MetaSploitable 2, el escaneo ofrece un informe completo con todas las vulnerabilidades detectadas en la maquina

## 3. Resumen de resultados
| Vulnerabilidad | Severidad / CVSS | Origen | Descripción |
| :--- | :--- | :--- | :--- |
| Canonical Ubuntu Linux SEoL | Crítica / 10.0 | Configuración / Gestión de obsolescencia | El servidor está ejecutando **Ubuntu Linux 8.04**, una versión cuyo soporte de seguridad finalizó en mayo de 2013. Al estar en estado *Security End of Life* (SEoL), Canonical ya no publica parches ni actualizaciones de seguridad para este sistema. |
| Samba Badlock Vulnerability | High / 7.5 | Diseño de protocolos / Implementación de software | Un atacante mediante un ataque Man-in-the-Middle (MitM) puede interceptar el tráfico de red y forzar la degradación del nivel de autenticación (*downgrade*), lo que le permite ejecutar llamadas arbitrarias en la red Samba, modificar datos sensibles de seguridad en Active Directory o desactivar servicios críticos. |
| SSL Version 2 and 3 Protocol Detection | Critical / 9.8 | Configuración de seguridad / Criptografía obsoleta | El servidor está usando sistemas de seguridad antiguos y defectuosos (SSL 2.0 y SSL 3.0) para proteger la información que envía y recibe. Un atacante en la misma red podría interceptar la conexión, romper esa protección antigua y leer o modificar los datos privados (como contraseñas o información confidencial) que viajan entre los usuarios y el servidor. |


## 4. Conclusión
La maquina analizada, en el estado actual, es un activo de altisimo riesgo para la seguridad del dato y digital para cualquier tipo de uso, desde el rango personal al comercial y empresarial, bajo ningún concepto sería recomendable mantener en funcionamiento de esta maquina sin cambios estructurales y significativos en el equipo, su configuración y software.
