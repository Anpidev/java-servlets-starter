
# 🌐 Java Servlets Starter

Proyecto introductorio de desarrollo web en **Java EE** enfocado en el funcionamiento básico de los **Java Servlets**, ciclo de vida de peticiones HTTP (`GET`/`POST`), configuración del descriptor de despliegue (`web.xml`) y entrega de contenido estático y dinámico.

---

## 📌 Contenido del Proyecto

* **Servlets (`com.pruebas`):** Controladores para el procesamiento de peticiones HTTP, manejo de parámetros y generación de respuestas dinámicas (`Servlet001`, `Servlet002`, `Servlet003`).
* **Vistas Estáticas:** Página web de inicio (`Hola.html`) integrada en el directorio raíz de la aplicación web.
* **Descriptor de Despliegue (`web.xml`):** Configuración de mapeo de rutas (*servlet-mapping*), páginas de bienvenida (*welcome-file-list*) y parámetros de inicialización.

---

## 📂 Estructura del Proyecto

```text
WebPrueba1/
├── src/
│   └── main/
│       ├── java/
│       │   └── com/
│       │       └── pruebas/
│       │           ├── Servlet001.java     # Controlador y manejo de peticiones
│       │           ├── Servlet002.java     # Procesamiento y respuestas HTTP
│       │           └── Servelt003.java     # Lógica adicional de prueba
│       └── webapp/
│           ├── Hola.html                   # Página HTML estática de bienvenida
│           ├── META-INF/
│           │   └── MANIFEST.MF
│           └── WEB-INF/
│               └── web.xml                 # Configuración de Servlets y mappings

```

---

## 🛠️ Tecnologías Utilizadas

* **Lenguaje:** Java (Java SE / Java EE)
* **Tecnología Web:** Java Servlets API (HttpServlet)
* **Frontend:** HTML5
* **Herramientas de desarrollo:** Eclipse IDE for Enterprise Java and Web Developers (Eclipse WTP)

---

## 🚀 Despliegue y Ejecución

### Requisitos Previos

* **Java Development Kit (JDK):** Versión 8, 11 o superior.
* **Servidor de Aplicaciones / Contenedor de Servlets:** [Apache Tomcat](https://tomcat.apache.org/) (v9 o v10 recomendado) o WildFly.
* **IDE:** Eclipse IDE para Java EE, IntelliJ IDEA Ultimate o NetBeans.

### Pasos para ejecutar en Eclipse:

1. **Importar el proyecto:**
* Abre Eclipse y ve a `File -> Import... -> General -> Existing Projects into Workspace`.
* Selecciona el directorio `WebPrueba1`.


2. **Configurar el servidor:**
* En la pestaña **Servers**, añade tu instancia local de **Apache Tomcat**.
* Asocia el proyecto al servidor mediante clic derecho en Tomcat -> **Add and Remove...** -> Añade `WebPrueba1`.


3. **Arrancar la aplicación:**
* Inicia el servidor Tomcat (**Start**).
* Abre tu navegador y navega a:
```text
http://localhost:8080/WebPrueba1/Hola.html

```


* Accede a los diferentes Servlets mapeados a través de las URLs configuradas en el archivo `web.xml`.




