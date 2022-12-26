# traveler-prueba-tecnica
☕🚀 Prueba Técnica Traveler




⚡ A continuación se explican los artefactos que componen la prueba técnia - Rental Cars


💡 Diagrama de Contexto.
En este diagrama se presentan los módulos principales que debe tener la solución de e-commerce a construir para Rental Cars.
Ubicación: diagramas/1. Contexto.

💡 Diagrama de Arquitectura Limpia.
En este diagrama se presentan las capas en las que se plantea dividir la arquitectura de software de la solución a construir. 
Se basa en una arquitectura hexagonal, con 3 capas Infraestructura -> Casos de Uso -> Dominio (Negocio). Esto aplica tanto para 
la parte Front como para la parte Backend.
Ubicación: diagramas/2. Clean-ARQ.

💡 Diagrama de Clases.
En este diagrama se presentan las clases a nivel general para ir organizando el código de la solución. 
Se basa en una arquitectura hexagonal, con 3 capas Infraestructura -> Casos de Uso -> Dominio (Negocio). Esto aplica tanto para 
la parte Front como para la parte Backend.
Ubicación: diagramas/2. Clean-ARQ.

🏁 How To Start
Install Java 11: brew cask install corretto
Set it as your default JVM: export JAVA_HOME='/Library/Java/JavaVirtualMachines/amazon-corretto-11.jdk/Contents/Home'
Clone this repository: git clone https://github.com/CodelyTV/java-ddd-skeleton.
Bring up the Docker environment: make up.
Execute some Gradle lifecycle tasks in order to check everything is OK:
Create the project JAR: make build
Run the tests and plugins verification tasks: make test
Start developing!

☝️ How to update dependencies
Gradle (releases): ./gradlew wrapper --gradle-version=WANTED_VERSION --distribution-type=bin

💡 Related repositories
