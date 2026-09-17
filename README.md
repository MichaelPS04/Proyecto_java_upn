# Proyecto_java_upn 
# integrantes 
- Parra Sebastian Michael Bleyd 
- Barbudo Chavarria Mathias Benjamin
- Deyanira Antonella Soto Mamani

## Problematica del negocio 
En la actualidad, muchas barberías y salones de belleza gestionan sus reservas de forma manual a través de cuadernos, mensajes de WhatsApp o llamadas telefónicas. Este modelo de trabajo tradicional genera tres problemas principales en el día a día del negocio:
1. **Cruce de horarios y duplicidad de citas:** Al no contar con una validación en tiempo real, se asignan múltiples clientes al mismo especialista o en la misma hora, afectando la experiencia del usuario.
2. **Falta de control en los ingresos reales:** El cálculo manual del dinero recaudado por servicios, comisiones y descuentos especiales (como los de clientes frecuentes) incrementa la probabilidad de errores humanos y pérdidas financieras al cierre de caja.
3. **Suboptimización del personal:** No se visualiza con claridad qué estilistas o barberos tienen tiempos muertos, impidiendo una distribución eficiente de la carga de trabajo diaria.

Para solucionar esto, se propone el desarrollo de un sistema automatizado bajo el paradigma de la Programación Orientada a Objetos (POO), que centralice y valide las reservas de citas, gestione los servicios y calcule de manera exacta los flujos económicos.

## Objetivos
* **Objetivo General:** Desarrollar un sistema de gestión y control de citas aplicable a salones de belleza y barberías que optimice el proceso de reserva y automatice la facturación de servicios utilizando Java y principios de programación orientada a objetos.
* **Objetivos Específicos:**
  * Implementar el encapsulamiento y la abstracción mediante clases (`Servicio`, `Cita`, `Especialista`) para proteger los datos críticos del negocio (como precios y estados de pago).
  * Desarrollar una funcionalidad lógica que valide y procese pagos aplicando reglas de negocio automatizadas, como descuentos por fidelidad de clientes frecuentes.
  * Establecer un flujo de trabajo colaborativo en Git y GitHub que permita la integración de código mediante ramas independientes y revisiones de código cruzadas (*Pull Requests*).

## Tecnologias
Para el diseño, desarrollo y control de versiones del proyecto se emplean las siguientes herramientas:
* **Java:** Lenguaje de programación principal elegido por su sólido soporte para la Programación Orientada a Objetos (POO). Permite estructurar el negocio mediante clases independientes, métodos encapsulados y tipos de datos estrictos para el manejo financiero y lógico del sistema.
* **GitHub:** Plataforma de alojamiento en la nube utilizada para centralizar el repositorio del equipo. Facilita la administración de roles como colaboradores, el seguimiento del avance del proyecto y la validación de nuevas funcionalidades mediante herramientas de *Code Review* en los *Pull Requests*.
* **Git:** Sistema de control de versiones distribuido utilizado localmente por cada integrante. Permite el aislamiento de tareas mediante la creación de ramas de trabajo individuales (`feature-branches`), asegurando que las modificaciones de código o documentación se realicen sin alterar la rama principal (`main`) hasta ser aprobadas.
* **Visual Studio Code:** Entorno de desarrollo ligero y modular configurado con extensiones de Java (*Extension Pack for Java*). Se utiliza como el editor de código principal para escribir el programa, compilar el código fuente y depurar errores, además de contar con una terminal integrada para ejecutar los comandos de Git de manera eficiente.
