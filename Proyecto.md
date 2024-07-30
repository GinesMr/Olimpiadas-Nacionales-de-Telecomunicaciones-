

---

# TerraEsphere - Ganador de las Olimpiadas Nacionales de Telecomunicaciones 2024

Este repositorio contiene el proyecto **TerraEsphere**, ganador de las Olimpiadas Nacionales de Telecomunicaciones 2024. Nuestro proyecto aborda problemas críticos relacionados con el Objetivo de Desarrollo Sostenible (ODS) 3: Salud y Bienestar, utilizando tecnologías avanzadas y soluciones innovadoras.

## Descripción del Proyecto

**TerraEsphere** es una esfera innovadora diseñada para medir la calidad del suelo, proporcionando datos esenciales para la agricultura y el medio ambiente. Equipado con sensores para monitorear el pH, la humedad y la temperatura del suelo, TerraEsphere facilita el acceso a información precisa y en tiempo real para mejorar la salud del suelo y optimizar el uso de recursos.

### Problemas Resueltos

Nuestro proyecto se centra en resolver los siguientes problemas relacionados con la salud y el bienestar:

- **Monitoreo de la Calidad del Suelo:** Mejoramos el monitoreo de la calidad del suelo para apoyar prácticas agrícolas sostenibles.
- **Optimización del Uso de Recursos:** Proporcionamos datos precisos para optimizar el uso de recursos como agua y fertilizantes.
- **Salud Ambiental:** Contribuimos a mantener la salud del suelo, lo cual es crucial para la producción de alimentos saludables y el bienestar general del ecosistema.

### Características Principales

- **Sensores de Calidad del Suelo:** Utilizamos sensores para medir pH, humedad y temperatura del suelo.
- **Desarrollo en Arduino:** Utilizamos el lenguaje de programación de la IDE de Arduino para la implementación del sistema de recolección de datos de los sensores.
- **Comunicación Inalámbrica:** Implementamos un módulo inalámbrico EBYTE 2.4GHz nRF24L01+PA+LNA RF de largo alcance para transmitir datos de los sensores.
- **Transmisión de Datos:** Los datos se transmiten a un receptor que envía la información a una base de datos SQL para su almacenamiento y análisis.
- **Energías Renovables:** Utilizamos una placa solar y una batería recargable para alimentar el sistema, promoviendo el uso de energías renovables y la sostenibilidad del proyecto.
- **Conocimientos de Electrónica:** Aplicamos conocimientos de electrónica para el diseño y la implementación del sistema de sensores, comunicación y alimentación.
- **Carcasa Impresa en 3D:** La carcasa de la esfera fue creada utilizando una impresora 3D con un material reciclable basado en maíz, que es no contaminante. Además, la carcasa está diseñada para ser estanca, protegiendo los componentes internos de las condiciones ambientales externas.
- **Modo de Ahorro de Energía:** Implementamos un modo de ahorro de energía en el que la esfera transmite datos cada 15 minutos. Durante este período, los sensores se apagan para conservar energía y prolongar la duración de la batería.
- **Pantalla LCD de Bajo Consumo:** Los datos recolectados se muestran en una pantalla LCD integrada en la esfera, que consume poca energía, permitiendo una visualización directa de la información sobre la calidad del suelo sin necesidad de conexión continua a una fuente de alimentación externa.

### Tecnologías Utilizadas

- **Lenguaje de la IDE de Arduino:** Para la programación de la recolección de datos y la comunicación con los sensores.
- **Múltiples Librerías de Arduino:** Para facilitar la integración y el funcionamiento de los sensores y el módulo inalámbrico.
- **EBYTE nRF24L01+PA+LNA:** Módulo inalámbrico de largo alcance para transmisión de datos.
- **SQL:** Para la gestión y almacenamiento de datos.
- **Placa Solar y Batería Recargable:** Para la alimentación del sistema utilizando energías renovables.
- **Impresión 3D con Material Reciclable:** Carcasa de la esfera impresa en 3D con un material basado en maíz, que es reciclable y no contaminante.
- **Pantalla LCD:** Para la visualización de datos en tiempo real, utilizando una pantalla de bajo consumo para minimizar el impacto en la duración de la batería.

### Sensores Utilizados

- **Sensor de pH:** Para medir la acidez o alcalinidad del suelo.
- **Sensor de Humedad:** Para medir el contenido de agua en el suelo.
- **Sensor de Temperatura:** Para medir la temperatura del suelo.

