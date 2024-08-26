# Sistema de Control de Acceso mediante Reconocimiento Facial

## Descripción del Proyecto

El objetivo de este proyecto es desarrollar una solución de control de acceso basada en reconocimiento facial con los siguientes requisitos funcionales:

## Requisitos Funcionales

- **Reconocimiento de Personas:**  
  El sistema deberá contar con un Raspberry Pi y una cámara, y ser capaz de reconocer a una persona. Cuando la persona sea reconocida y tenga acceso permitido, se deberá abrir una puerta de acceso.

- **Alta de Nuevos Usuarios:**  
  El sistema deberá ser capaz de dar de alta a un usuario nuevo.

- **Alertas de Intentos de Acceso Fallidos:**  
  El sistema deberá ser capaz de generar alertas de forma automática por correo electrónico cuando se produzcan intentos de acceso fallidos consecutivos en un período corto de tiempo. El número de accesos fallidos consecutivos y dicho período de tiempo deberán ser configurables.

## Interfaz de Usuario

El sistema deberá contar con una interfaz de usuario que incluya:

- **Dashboard:**  
  Muestra los datos de accesos tanto correctos como fallidos de las últimas 24 horas.

- **Visualización de Datos Históricos:**  
  Una interfaz para visualizar, ya sea como gráfico o como tabla, los datos históricos. Los usuarios deberán poder consultar cualquier fecha de datos históricos y agrupar los datos por hora, día y mes.

- **Estadísticas:**  
  Una interfaz para ver estadísticas como mínimos, máximos, promedio, mediana y desviación estándar para cualquier rango de fechas.
