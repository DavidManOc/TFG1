# TFG1

Trabajo fin de curso David Manzanero (2º DAM 2023)
//-------------------------------------------------------------------------------------
Introducción:

  - Wheather status permite comparar permite comparar el tiempo entre 2 localidades distintas.
  - Aplicación desarrollada para aplicaciones Android.
  - Posibles usos: 
      *Periodo vacacional. 
      *Planificación actividades al aire libre. 
      *Selección de una ubicación contreta. 
      *etc.

//-------------------------------------------------------------------------------------
Idea del proyecto: 
    Se me ocurrió un día revisando los ejercicios de Acceso a Datos, ya que en clase hicimos un ejercicio de 
    obtener los datos meteorológicos (de la AEMET) del día siguiente de una ciudad concreta.

//-------------------------------------------------------------------------------------
Desarrollo del proyecto:
  - Requisitos funcionales:
      *Registro / logeo usuario
      *Función de comparación
      *Guardar comparaciones
      *Revisar Historial de comparaciones

  - Requisito no funcional:
      *Proyecto adaptable a diversos dispositivos, de forma horizontal y vertical
      
  - Modelo Entidad-Relación:
      *Usuario: Atributos -> (ID, Nombre, Email*, PassWord*)
      *Búsqueda: Atributos -> ()
      
      * -> Opcional
      
      El atributo Búsqueda tiene una relación reflexiva porque una comparación           siempre se tiene que hacer por 2 búsquedas. 
      
      El usuario realiza comparaciones.
      
      La comparación se compone de 2 búsquedas.
    
  - Diagrama de clases:
      *Clase Base de Datos -> 
      *Clase Usuario ->
      *Clase Historial ->
      *Clase Comparación ->
      *Clase Búsqueda -> 
