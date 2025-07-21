# Botium Toys: Alcance, objetivos y evaluación de riesgos

## Informe

### Alcance y objetivos de la auditoría

**Alcance:**  
El alcance de esta auditoría se define como el programa de seguridad completo de Botium Toys.  
Esto incluye sus activos, como el equipo y dispositivos de los empleados, su red interna y sus sistemas.  
Será necesario revisar los activos que posee Botium Toys, así como los controles y prácticas de cumplimiento que tienen implementados.

**Objetivos:**  
Evaluar los activos existentes y completar la lista de verificación de controles y cumplimiento, para determinar qué controles y mejores prácticas deben implementarse con el fin de mejorar la postura de seguridad de Botium Toys.

---

### Activos actuales

Los activos gestionados por el Departamento de TI incluyen:

- Equipos locales para las necesidades empresariales en oficina.  
- Equipos de los empleados: dispositivos de usuario final (escritorios/portátiles, teléfonos inteligentes), estaciones de trabajo remotas, auriculares, cables, teclados, ratones, estaciones de acoplamiento, cámaras de vigilancia, etc.  
- Productos en tienda disponibles para la venta minorista en el lugar y en línea; almacenados en el almacén adyacente de la empresa.  
- Gestión de sistemas, software y servicios: contabilidad, telecomunicaciones, bases de datos, seguridad, comercio electrónico y gestión de inventarios.  
- Acceso a Internet.  
- Red interna.  
- Retención y almacenamiento de datos.  
- Mantenimiento de sistemas heredados: sistemas obsoletos que requieren monitoreo humano.

---

### Evaluación de riesgos

**Descripción del riesgo**  
Actualmente, la gestión de activos es inadecuada. Además, Botium Toys no tiene implementados todos los controles adecuados y puede que no cumpla completamente con las regulaciones y estándares de EE. UU. e internacionales.

**Mejores prácticas de control**  
La primera de las cinco funciones del Marco de Ciberseguridad del NIST (NIST CSF) es *Identificar*.  
Botium Toys necesitará dedicar recursos para identificar sus activos, a fin de poder gestionarlos adecuadamente.  
También deberán clasificar los activos existentes y determinar el impacto de la pérdida de estos activos, incluyendo los sistemas, en la continuidad del negocio.

**Puntuación de riesgo**  
En una escala del 1 al 10, la puntuación de riesgo es 8, lo cual es bastante alto. Esto se debe a la falta de controles y la no adherencia a las mejores prácticas de cumplimiento.

---

### Comentarios adicionales

El impacto potencial de la pérdida de un activo se clasifica como **medio**, ya que el departamento de TI no sabe exactamente qué activos estarían en riesgo.  
El riesgo para los activos o posibles multas por parte de organismos reguladores es **alto**, debido a que Botium Toys no tiene todos los controles necesarios en funcionamiento y no sigue completamente las mejores prácticas de cumplimiento para mantener los datos críticos privados y seguros.

**Detalles específicos:**

- Actualmente, todos los empleados de Botium Toys tienen acceso a los datos almacenados internamente y pueden acceder a datos de tarjetas de pago y a información personal/sensible de los clientes (PII/SPII).
- No se utiliza cifrado para garantizar la confidencialidad de la información de las tarjetas de crédito de los clientes que se acepta, procesa, transmite y almacena localmente en la base de datos interna de la empresa.
- No se han implementado controles de acceso que garanticen el principio de mínimo privilegio ni la separación de funciones.
- El departamento de TI ha asegurado la **disponibilidad** y ha integrado controles para garantizar la **integridad de los datos**.
- El departamento de TI tiene un **firewall** que bloquea el tráfico según un conjunto de reglas de seguridad adecuadamente definido.
- El **software antivirus** está instalado y es monitoreado regularmente por el departamento de TI.
- El departamento de TI **no ha instalado un sistema de detección de intrusiones (IDS)**.
- **No existen planes de recuperación ante desastres**, ni la empresa tiene copias de seguridad de los datos críticos.
- El departamento de TI ha establecido un plan para **notificar a los clientes de la UE dentro de las 72 horas** en caso de una violación de seguridad. Además, se han desarrollado políticas, procedimientos y procesos de privacidad que se hacen cumplir entre los miembros del departamento de TI y otros empleados para documentar y mantener correctamente los datos.
- Aunque existe una política de contraseñas, sus requisitos son mínimos y **no están alineados con los estándares actuales** de complejidad mínima (por ejemplo, al menos ocho caracteres, combinación de letras y al menos un número; caracteres especiales).
- **No existe un sistema centralizado de gestión de contraseñas** que haga cumplir los requisitos mínimos de la política de contraseñas, lo que a veces **afecta la productividad** cuando empleados/proveedores deben enviar un ticket al departamento de TI para recuperar o restablecer una contraseña.
- Aunque los sistemas heredados son monitoreados y mantenidos, **no existe un cronograma regular** para estas tareas y los métodos de intervención no están claramente definidos.
- La ubicación física de la tienda, que incluye las **oficinas principales, la tienda y el almacén de Botium Toys**, cuenta con **cerraduras adecuadas**, sistema de **vigilancia CCTV actualizado**, y sistemas de **detección y prevención de incendios** en funcionamiento.

