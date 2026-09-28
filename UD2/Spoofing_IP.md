# Ataques de suplantación de identidad

## 3. IP spoofing

### Qué es
Es una técnica que consiste en falsificar la dirección IP de origen en los paquetes de datos para hacer creer que provienen de una fuente confiable o de otro sistema.

### Cómo se lleva a cabo


### Qué categoría(s) de amenaza compromete

Vulnera principalmente la Autenticidad, de forma derivada la Integridad y Disponibilidad
El enfoque es engañar al receptor, suplantando la identidad de otro emisor, permitiendo inyectar código bajo el pseudónimo de otro emisor considerado seguro, destruyendo por completo la garantía del origen, ergo, rompe la Autenticidad

### Ejemplo o caso real
Un caso famoso de las primeras veces que se aplicó esta técnica fue el de Kevin Mitnick en 1994. Este quería acceder ilegalmente al ordenador del experto en seguridad Tsutomu Shimomura. Para realizarlo, falsificó la dirección IP de una máquina de confianza que el sistema del atacado reconociera. Dado que el ataque parecía provenir de una dirección IP conocida y confiable, el sistema objetivo no solicitó una contraseña. Kevin no podría recibir respuestas, puesto que iban dirigidas a la máquina real, pero adivinó los códigos de confirmación para completar el protocolo de enlace y tener acceso unidireccional. Esto le permitió extraer datos y acaparar titulares, demostrando los riesgos de confiar únicamente en las direcciones IP.

### Medida de prevención

### Fuente
(si es vuestro ataque asignado: enlace consultado. Si lo habéis completado 
en la puesta en común: "Puesta en común — expuesto por [nombre o grupo]")


## Aplicado a Estudio Torrent

De los cuatro, ¿cuál creéis que sería el más plausible contra Estudio Torrent 
(wifi de oficina, ERP online, disco compartido con clientes)? Razonad la respuesta 
en 3-4 líneas, usando lo que habéis aprendido de los cuatro ataques, no solo del vuestro.
