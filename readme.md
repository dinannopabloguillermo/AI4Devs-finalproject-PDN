## Índice

0. [Ficha del proyecto](#0-ficha-del-proyecto)
1. [Descripción general del producto](#1-descripción-general-del-producto)
2. [Arquitectura del sistema](#2-arquitectura-del-sistema)
3. [Modelo de datos](#3-modelo-de-datos)
4. [Especificación de la API](#4-especificación-de-la-api)
5. [Historias de usuario](#5-historias-de-usuario)
6. [Tickets de trabajo](#6-tickets-de-trabajo)
7. [Pull requests](#7-pull-requests)

---

## 0. Ficha del proyecto

### **0.1. Tu nombre completo:**
Pablo Guillermo Di Nanno

### **0.2. Nombre del proyecto:**
WeatherTrack

### **0.3. Descripción breve del proyecto:**

> Aplicación multiplataforma para la observación de índices y variables meteorológicas.

### **0.4. URL del proyecto:**

> Puede ser pública o privada, en cuyo caso deberás compartir los accesos de manera segura. Puedes enviarlos a [alvaro@lidr.co](mailto:alvaro@lidr.co) usando algún servicio como [onetimesecret](https://onetimesecret.com/).

### 0.5. URL o archivo comprimido del repositorio

> Puedes tenerlo alojado en público o en privado, en cuyo caso deberás compartir los accesos de manera segura. Puedes enviarlos a [alvaro@lidr.co](mailto:alvaro@lidr.co) usando algún servicio como [onetimesecret](https://onetimesecret.com/). También puedes compartir por correo un archivo zip con el contenido


---

## 1. Descripción general del producto

> Describe en detalle los siguientes aspectos del producto:

### **1.1. Objetivo:**

> El propósito de weathertrack es proveer un ecosistema centralizado e inteligente para la monitorización y análisis de variables meteorológicas, adaptándose dinámicamente a la complejidad requerida por el usuario. El sistema soluciona la fragmentación de la información climática ofreciendo una experiencia multiplataforma escalable: democratiza el acceso a datos instantáneos para el público general, optimiza la toma de decisiones del sector agrícola mediante proyecciones, y habilita la investigación científica profunda mediante el análisis de acumulados históricos y fenómenos macroclimáticos

### **1.2. Características y funcionalidades principales:**

> La plataforma basa su funcionamiento en un sistema de roles estructurado en tres niveles de profundidad analítica, orquestados por agentes inteligentes:  
- Nivel 1 - Público General (Visión Instantánea):
    - Monitorización en tiempo real de variables meteorológicas básicas.  
    - Interfaz gráfica simplificada e intuitiva.  
- Nivel 2 - Sector Agrícola/Productivo (Análisis y Predicción):
    - Paneles interactivos con índices meteorológicos elaborados. 
    - Modelos de predicción a corto y mediano plazo para soporte en tareas operativas.  
- Nivel 3 - Académico/Investigación (Datos Complejos y Acumulados):
    - Cálculo y visualización de índices avanzados asociados a acumulados temporales (heladas, precipitaciones, niveles de humedad de suelos, radiación solar).  
    - Seguimiento y evaluación de fenómenos macroclimáticos (ej. índice ENO).  
    - Acceso profundo a las bases de datos climáticas para consultas históricas y comparativas.  
Funcionalidades Transversales (Core Agéntico y Arquitectura):
    - Skills de Ingesta: Agentes autónomos dedicados a la recolección, validación y normalización de datos provenientes de la red de sensores.  
    - Subagentes de Cálculo: Procesamiento asíncrono para derivar los índices complejos de los Niveles 2 y 3 sin afectar el rendimiento de la aplicación.

### **1.3. Diseño y experiencia de usuario:**

> Proporciona imágenes y/o videotutorial mostrando la experiencia del usuario desde que aterriza en la aplicación, pasando por todas las funcionalidades principales.

### **1.4. Instrucciones de instalación:**
> Documenta de manera precisa las instrucciones para instalar y poner en marcha el proyecto en local (librerías, backend, frontend, servidor, base de datos, migraciones y semillas de datos, etc.)

---

## 2. Arquitectura del Sistema

### **2.1. Diagrama de arquitectura:**
> Usa el formato que consideres más adecuado para representar los componentes principales de la aplicación y las tecnologías utilizadas. Explica si sigue algún patrón predefinido, justifica por qué se ha elegido esta arquitectura, y destaca los beneficios principales que aportan al proyecto y justifican su uso, así como sacrificios o déficits que implica.


### **2.2. Descripción de componentes principales:**

> Describe los componentes más importantes, incluyendo la tecnología utilizada

### **2.3. Descripción de alto nivel del proyecto y estructura de ficheros**

> Representa la estructura del proyecto y explica brevemente el propósito de las carpetas principales, así como si obedece a algún patrón o arquitectura específica.

### **2.4. Infraestructura y despliegue**

> Detalla la infraestructura del proyecto, incluyendo un diagrama en el formato que creas conveniente, y explica el proceso de despliegue que se sigue

### **2.5. Seguridad**

> Enumera y describe las prácticas de seguridad principales que se han implementado en el proyecto, añadiendo ejemplos si procede

### **2.6. Tests**

> Describe brevemente algunos de los tests realizados

---

## 3. Modelo de Datos

### **3.1. Diagrama del modelo de datos:**

> Recomendamos usar mermaid para el modelo de datos, y utilizar todos los parámetros que permite la sintaxis para dar el máximo detalle, por ejemplo las claves primarias y foráneas.


### **3.2. Descripción de entidades principales:**

> Recuerda incluir el máximo detalle de cada entidad, como el nombre y tipo de cada atributo, descripción breve si procede, claves primarias y foráneas, relaciones y tipo de relación, restricciones (unique, not null…), etc.

---

## 4. Especificación de la API

> Si tu backend se comunica a través de API, describe los endpoints principales (máximo 3) en formato OpenAPI. Opcionalmente puedes añadir un ejemplo de petición y de respuesta para mayor claridad

---

## 5. Historias de Usuario

> Documenta 3 de las historias de usuario principales utilizadas durante el desarrollo, teniendo en cuenta las buenas prácticas de producto al respecto.

**Historia de Usuario 1**

**Historia de Usuario 2**

**Historia de Usuario 3**

---

## 6. Tickets de Trabajo

> Documenta 3 de los tickets de trabajo principales del desarrollo, uno de backend, uno de frontend, y uno de bases de datos. Da todo el detalle requerido para desarrollar la tarea de inicio a fin teniendo en cuenta las buenas prácticas al respecto. 

**Ticket 1**

**Ticket 2**

**Ticket 3**

---

## 7. Pull Requests

> Documenta 3 de las Pull Requests realizadas durante la ejecución del proyecto

**Pull Request 1**

**Pull Request 2**

**Pull Request 3**

