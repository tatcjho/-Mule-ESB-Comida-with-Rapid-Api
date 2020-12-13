# Implementación de Mule con Rapi Api

## ¿Qué es Mule ESB?
Mule, el motor de tiempo de ejecución de Anypoint Platform, es un bus de servicio empresarial (ESB) ligero basado en Java y una plataforma de integración que permite a los desarrolladores conectar aplicaciones de forma rápida y sencilla, lo que les permite intercambiar datos. Permite una fácil integración de los sistemas existentes, independientemente de las diferentes tecnologías que utilicen las aplicaciones, incluidos JMS, Web Services, JDBC, HTTP y más. El ESB se puede implementar en cualquier lugar, puede integrar y organizar eventos en tiempo real o por lotes, y tiene conectividad universal.

## Ventajas
Las ventajas de usar mule son:
* Creación y alojamiento de servicios: exponga y aloje servicios reutilizables, utilizando el ESB como un contenedor de servicios ligero
* Mediación de servicios: proteja los servicios de los formatos y protocolos de mensajes, separe la lógica empresarial de la mensajería y habilite llamadas de servicio independientes de la ubicación
* Enrutamiento de mensajes: enrute, filtre, agregue y vuelva a secuenciar los mensajes según el contenido y las reglas
* Transformación de datos: intercambie datos en distintos formatos y protocolos de transporte

	

## ¿Qué es Rapi Api?

RapidAPI, el mercado de API más grande del mundo, es utilizado por más de un millón de desarrolladores para buscar, probar y conectarse a miles de API, todo con una sola cuenta, clave de API y SDK.

Encuentre las API que necesita para su proyecto, incruste la API en su aplicación y realice un seguimiento del uso de todas sus API a través de un solo panel. Si crea una API, use RapidAPI para ponerla a disposición de más de 1 millón de desarrolladores que ya utilizan nuestro Marketplace.

## Implementación
Nuestro proyecto trata sobre la creación de un sistema distribuido en la web, bajo arquitectura SOA, en el que se implemente un proceso de negocio , el mismo que deberá implicar a un mínimo de tres proveedores de distintos servicios, el cual se ejemplificará en la creación de un sistema distribuido bajo la arquitectura de SOA que permitirá a un usuario poderse registrar, loguear y posteriorimente elegir servicios que le pueda ayudar a crear una cita perfecta, en este caso tiene que escoger por la decoración, música y comida, de esta manera permitirá enviar una invitación a su cita con todos los campos seleccionados. Cabe recalcar, que esta aplicación se desarrollo en base al confinamiento y la preservación del distanciamiento social que se ve evidenciado por el COVID-19. 

Utilizamos la api de  Edamam Food and Grocery Database API Documentation puesto que estaba en categoría free y era la que más nos beneficiaba en cuanto a una base de datos de alimentos. 

### API Edamam Food and Grocery Database API Documentation
Su API le proporciona herramientas para encontrar datos de nutrición y dieta para alimentos genéricos, alimentos envasados ​​y comidas de restaurante. Además, emplea NLP (procesamiento de lenguaje natural) que permite la extracción de entidades alimentarias a partir de texto no estructurado. Casos de uso cubiertos: busque un alimento por palabra clave, nombre del alimento o código de barras / UPC Búsqueda de información nutricional para un alimento determinado, incluidos: macro y micronutrientes, etiquetas de alérgenos, etiquetas de estilo de vida y salud Busque un alimento por cantidad de nutrientes dada para 28 Nutrientes Búsqueda de alimentos dentro de una marca determinada Con el contexto de registro de alimentos integrado, permite solicitudes de PNL para chat bots y contadores de calorías de lenguaje natural.

## PASOS 

#### PASO 1: 
##### Instalación de AnypointStudio: https://www.mulesoft.com/lp/dl/studio
Posterior a la descarga, se instala normalmente seleccionando donde queremos nuestro carpeta de trabajo  y abrimos. 




