## Descripción del Problema
El Metropolitano requiere un sistema integral para administrar y optimizar sus operaciones de transporte, mantenimiento de flota y gestión de estaciones. Actualmente, se manejan múltiples componentes como rutas, vehículos, estaciones, conductores y transacciones de tarjetas cada uno con datos críticos como horarios, estados técnicos, ubicaciones y saldos. Sin embargo, la falta de centralización dificulta la coordinación de mantenimientos preventivos y correctivos de buses, la asignación eficiente de conductores a rutas, el monitoreo en tiempo real de estaciones y la gestión de tarjetas. 
## Requerimientos Funcionales
Registrar información básica de los conductores (DNI, nombres, licencia y actividad). 

Gestionar las rutas:  

Origen y final de la ruta. 

Tipo del servicio 

Horarios establecidos 

Parada en estaciones 

Asociar a los viajes con sus especificaciones (Chofer, ruta, vehiculo) 

Almacenar el historial de viajes realizados 

Validar las tarjetas a usar como medio de pago 

Programar viajes 

Generar reportes de rutas más usadas, estaciones donde hay más aglomeración de personas, etc.
## Entidades Identificadas
Chofer: Información básica del chofer. 

Vehículo: Información básica del vehículo. 

Viaje: Viajes realizados por los choferes. 

Ruta: Dirección preestablecida para cada viaje. 

Tipo de servicio: Servicios ofrecidos. 

Estación: Estación donde paran los vehículos. 

Tarjeta: Medio de pago 

Validación: Para monitorear transacciones. 
## Tablas y Campos Relevantes

1. Tabla Chofer: Contiene la información básica de todos los choferes. 

Nombre 

DNI 

Licencia 

Estado 

2. Tabla Vehiculos: Contiene la información de la flota de vehículos del metropolitano. 

Placa 

Marca 

Modelo 

Tipo 

Capacidad 

3. Tabla Viaje: Contiene la información de todos los viajes realizados. 

Hora de salida 

Hora de llegada 

4. Tabla Ruta: Información de la ruta de todos los viajes 

Origen 

Destino 

Días de servicio 

Hora de inicio 

Hora final 

Horarios 

Dirección 

5. Tabla de servicios: Registra los servicios brindados. 

Nombre del servicio 

6. Estación 

Nombre 

Distrito 

Tipo 

Ubicación 

7. Validación: Se monitorea las transacciones realizadas 

Tipo de pago 

Monto 

Fecha y hora de transacción 

8. Tarjeta: Se registro de actividades de la tarjeta 

Número 

Tipo 

Saldo 

Estado 

Fecha de emisión 

Desafíos: 

Asignación de buses hacia las estaciones: El metropolitano debe de ser un medio de transporte rápido y debe de actuar con ideas para solucionar el problema de buses excesivamente llenos con la finalidad de mejorar la experiencia del cliente. 

Seguimiento de choferes: Es crucial que se pueda monitorear a los choferes, ya que si estos no cuentan con licencia permitida, será un problema legal que tendrá que afrontar la empresa. 

Optimización de recursos: Es crucial poder tomar decisiones estratégicas para planificar las rutas a establecer, teniendo en cuenta las estaciones con mayor aglomeración de personas, horas punta, etc. 

Seguimiento de transacciones: Es crucial tener en cuenta el número de transacciones realizadas en cada estación con la finalidad de establecer más paradas en dichas estaciones.  

Beneficios Esperados: 

Rutas optimizadas, menos retrasos, flotas de vehículos mejor distribuidas. 

Facilitar la toma de decisiones estratégicas basadas en los datos que se puedan extraer de la BD. 

Mejor control y seguimiento de los vehículos. 

Incrementar la satisfacción de los clientes. 

 
