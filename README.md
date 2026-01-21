# Carlos Mendoza Jiménez

### 🌱 Actualmente profundizando conocimientos en:
- **Java**
- **PHP**
- **Spring Boot**
- **Kotlin**
- **Jetpack Compose**
- **C# Unity**

# Proyectos personales

## 1. Sistema de manejo de stock para almacenes
Un proyecto desarrollado para gestionar de forma eficiente el inventario de un almacén. Incluye funcionalidades para la entrada y salida de productos, generación de reportes de stock y alertas cuando los niveles de inventario están bajos.

**Tecnologías utilizadas:**
- **Java**
- **SQL**
- **JavaFX**
- **Spring Boot**
- **Maven**

---

## 2. Sistema de Alquiler de Coches
Un proyecto diseñado para gestionar de forma eficiente el alquiler de vehículos. Incluye funcionalidades avanzadas para la administración de clientes y vehículos, así como la gestión de reservas y generación de reportes.

### Características principales:
- **Gestión de vehículos:**
  - Registro de nuevos coches
  - Estado de los vehículos (disponible, alquilado, en mantenimiento)
- **Gestión de clientes:**
  - Alta, baja y modificación de clientes
- **Gestión de reservas:**
  - Creación, actualización y cancelación de reservas
- **Reportes:**
  - Informes de ocupación de flota y estadísticas de uso
- **Alertas:**
  - Notificaciones para devoluciones próximas y mantenimiento de vehículos

### Tecnologías utilizadas:
- **Java:** Lenguaje principal para la lógica de la aplicación
- **SQL:** Base de datos para almacenar información de vehículos, clientes y reservas
- **JavaFX:** Interfaz gráfica amigable y fácil de usar
- **Spring Boot:** Framework para construir el backend con REST API y gestión de servicios
- **Maven:** Herramienta para la gestión de dependencias y construcción del proyecto

### Enlaces:
- [Control de Alquiler de Coches - Repositorio GitHub](https://github.com/TheReaperRK/CarConnect)
- [Presentación en Canva](https://www.canva.com/design/DAGbjsGQslY/aDQfhzQyG52-eK777Mivng/edit?utm_content=DAGbjsGQslY&utm_campaign=designshare&utm_medium=link2&utm_source=sharebutton)
- [Memoria del Proyecto en Google Docs](https://docs.google.com/document/d/1rDW2JKC5IKOYyLZL2HBUOGQDDR4lrDda6XauRIjkXtY/edit?tab=t.0)

  ## 3. AdMe - Foro de anuncios
Un proyecto en Android que toma como finalidad que cualquier persona pueda ofrecer servicios, o descubrir quien los ofrece.

### Características principales:
- **Gestión de anuncios**
  - Publica tus anuncios
  - Consulta los anuncios de otras personas filtrando por categorias y consulta informacion de quien lo ofrece.
  - Edita o borra tus anuncios desde tu perfil de usuario
- **Gestión de usuarios:**
  - Alta, baja y modificación de usuarios, mediante registro y activacion de la cuenta, o de forma dinamica como administrador.
- **Gestión de categorias:**
  - Creación, actualización y eliminación de categorias.
  - funcion de propuesta de categorias por parte de los usuarios
- **Cuenta:**
  - Reestablece tu contraseña mediante token de recuperacion en tu correo electronico
  - recibe informacion cuando un administrador caduque tu contraseña (tambien por correo)
- **Errores:**
  - Gestion de errores en formularios, mala utilizacion de credenciales o bien si el servidor no esta respondiendo.

### Tecnologías utilizadas:
- **Java:** Lenguaje principal para la lógica de la aplicación en el backend.
- **Spring Boot:** Framework para construir el backend con REST API y gestión de servicios.
- **SQL (MySQL):** Base de datos para almacenar información de anuncios, usuarios y categorías.
- **Jetpack Compose:** Framework declarativo de UI para el desarrollo de la interfaz en Android.
- **Kotlin:** Lenguaje utilizado para el desarrollo del frontend en Android.
- **Maven:** Herramienta para la gestión de dependencias y construcción del proyecto.
- **Gradle:** Utilizado para gestionar dependencias y configuración en el frontend de Android.
- **GitLab:** Plataforma para la gestión del código fuente y la integración continua.

## Estructura del Proyecto

- 📂 **AdMe**
  - 📂 **backend** (Java, Spring Boot)
    - 📂 `src/main/java/` (Código fuente del backend)
    - 📂 `src/main/resources/` (Configuraciones y recursos)
    - 📄 `pom.xml` (Gestión de dependencias con Maven)
    - 📄 `application.properties` (Configuración de la base de datos)
  - 📂 **frontend** (Android, Jetpack Compose, Kotlin)
    - 📂 `src/main/java/` (Código fuente del frontend en Kotlin)
    - 📂 `src/main/res/` (Recursos de la aplicación Android)
    - 📄 `build.gradle` (Gestión de dependencias con Gradle)
    - 📄 `AndroidManifest.xml` (Configuración de la aplicación Android)
  - 📄 `README.md` (Este archivo)
  - 📂 `docs/` (Documentación adicional)



### Enlaces:
- [AdMe - Foro de anuncios - Repositorio GitHub](https://github.com/TheReaperRK/AdMe_Project)
- [AdMe - Foro de anuncios - Repositorio GitLab](https://gitlab.com/carlosmendozajimenez/proyect3_group4)

# RoboCrysis - Videojuego 3D tipo shooter de oleadas

**RoboCrysis** es un videojuego desarrollado en Unity con cámara cenital (top-down), estilo shooter/survival. El jugador debe sobrevivir a oleadas de enemigos que aparecen desde distintos puntos del mapa. Un proyecto desarrollado en una semana y media, enfocado a una experiencia directa, rejugable y sin progreso acumulativo.

---

## 🎮 Características principales

### 🔭 Vista 3D cenital
- Estética estilizada y ambientación tecnológica.
- Cámara fija con perspectiva superior para visión estratégica del entorno.

### 🧟‍♂️ Sistema de oleadas
- Enemigos aparecen aleatoriamente desde zonas de spawn definidas.
- Cada oleada es más difícil que la anterior.
- La victoria se alcanza al superar la oleada 10.

### 🤖 Inteligencia artificial enemiga
- Patrullaje y persecución del jugador.
- Acciones: idle, caminar, atacar.
- Al morir, pueden dejar pociones curativas (probabilidad 1/20).

### 🧍‍♂️ Mecánicas del jugador
- Movimiento con teclado (WASD) y apuntado con ratón.
- Disparo con clic izquierdo (pistola única).
- Recolección de pociones para restaurar salud.
- Visión limitada en modo difícil (niebla de guerra).

### 🧩 Gestión de menús e interfaz
- Menú principal, menú de opciones (volumen y dificultad), pausa y pantalla final.
- HUD con vida, kills acumuladas y número de oleada.
- Pantalla de victoria o derrota con resumen de la partida.

---

## 🎮 Controles

- `WASD`: Movimiento  
- `Ratón`: Apuntar  
- `Clic izquierdo`: Disparar  
- `ESC`: Menú de pausa

---

## 🛠️ Tecnologías utilizadas

- **Unity (C#)**: Motor principal del juego.
- **EasyStart Third Person Controller**: Sistema base de movimiento del jugador.
- **AllSkyFree**: Skydomes y cielos HDRI para exteriores.
- **Cyberpunk Material Pack**: Materiales estilizados aplicados a edificios y paredes.
- **Low Poly Pistol Weapon Pack 1**: Modelo del arma principal.
- **PolyRonin**: Modelos low poly para jugador y enemigos.
- **Raptor3D**: Helicóptero decorativo.
- **Sounds (SFX)**: Biblioteca de efectos de disparo, pasos, pociones, etc.
- **TileableBricksWall**: Textura de ladrillo repetible usada en estructuras.

---

## 💾 Requisitos mínimos

- **Sistema Operativo**: Windows 10 / Ubuntu  
- **CPU**: Intel i3 o equivalente  
- **RAM**: 4 GB  
- **GPU**: Gráfica integrada  
- **Espacio en disco**: < 500 MB

---

## 🚀 Instalación

1. Descargar y extraer el archivo `.zip`.
2. Ejecutar el archivo `RoboCrysis.exe`.

---

#### Enlaces:
- [RoboCrysisis - Repositorio GitHub]()
- [RoboCrysisis - Repositorio GitLab](https://gitlab.com/carlosmendozajimenez/robocrysys)
