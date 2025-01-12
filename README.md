# Ecomart 🏢

Ecomart es una aplicación desarrollada en **Java** utilizando **Spring Boot**. Este proyecto se creó con **Spring Initializr** y hace uso de **Spring AI** y la API de OpenAI para implementar funcionalidades basadas en inteligencia artificial. 🤖

## Propósito del Proyecto 🚀
El objetivo principal de **Ecomart** es explorar el uso de inteligencia artificial para desarrollar aplicaciones modernas. Este proyecto incluye:
- 🌐 Generación automática de productos.
- 🔄 Clasificación de productos.
- 🖼️ Generación de imágenes relacionadas con los productos.

## Estructura del Proyecto 🔬
El proyecto sigue la estructura típica de Spring Boot:

```
Ecomart
|— src
   |— main
       |— java
           |— com.aluracursos.ecomart
               |— Controller
                   |— CategorizadorDeProductosController.java
                   |— GeneradorDeImagenesController.java
                   |— GeneradorDeProductosController.java
               |— EcomartApplication.java
       |— resources
           |— static
           |— templates
           |— application.properties
|— test
|— target
|— .gitignore
|— HELP.md
|— mvnw
|— mvnw.cmd
```

### Principales Componentes 🔧
- **Controladores:**
  - `CategorizadorDeProductosController`: Controlador para la clasificación de productos.
  - `GeneradorDeImagenesController`: Controlador para la generación de imágenes mediante IA.
  - `GeneradorDeProductosController`: Controlador para la creación de nuevos productos.
- **Recursos:** Archivos estáticos, plantillas y configuración de la aplicación.

## Requisitos Previos 🛠️
Antes de ejecutar el proyecto, asegúrate de tener:
- **Java 17** o superior.
- **Maven** configurado en tu sistema.
- Una API Key válida de OpenAI.

## Instalación y Ejecución 🔄
1. Clona este repositorio:
   ```bash
   git clone <URL_DEL_REPOSITORIO>
   ```
2. Navega al directorio del proyecto:
   ```bash
   cd ecomart
   ```
3. Configura tu API Key de OpenAI en el archivo `application.properties`:
   ```properties
   openai.api.key=TU_API_KEY
   ```
4. Compila y ejecuta la aplicación:
   ```bash
   ./mvnw spring-boot:run
   ```

## Tecnologías Utilizadas 💻
- **Java**
- **Spring Boot**
- **Spring AI**
- **OpenAI API**

## Contribuciones 🤝
Si deseas contribuir a este proyecto, sigue estos pasos:
1. Haz un fork del repositorio.
2. Crea una rama para tu función:
   ```bash
   git checkout -b nueva-funcion
   ```
3. Realiza tus cambios y haz un commit:
   ```bash
   git commit -m "Agrega nueva función"
   ```
4. Envía tus cambios al repositorio remoto:
   ```bash
   git push origin nueva-funcion
   ```
5. Crea un Pull Request.

## Licencia 🔒
Este proyecto se distribuye bajo la licencia MIT. Consulta el archivo `LICENSE` para más información.

## Disclaimer ⚠️
Este proyecto forma parte de las prácticas de una estudiante en formación de backend, por lo que se aceptan sugerencias y/o cambios para mejorar el código y la funcionalidad.

---

