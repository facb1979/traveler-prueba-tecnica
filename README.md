# traveler-prueba-tecnica
☕🚀 Prueba Técnica Traveler




⚡ A continuación se explican los artefactos que componen la prueba técnia - Rental Cars


💡 1. Diagrama de Contexto.
En este diagrama se presentan los módulos principales que debe tener la solución de e-commerce a construir para Rental Cars.
Ubicación: diagramas/1. Contexto.

💡 2. Diagrama de Arquitectura Limpia.
En este diagrama se presentan las capas en las que se plantea dividir la arquitectura de software de la solución a construir. 
Se basa en una arquitectura hexagonal, con 3 capas Infraestructura -> Casos de Uso -> Dominio (Negocio). Esto aplica tanto para 
la parte Front como para la parte Backend.
Ubicación: diagramas/2. Clean-ARQ.

💡 3. Diagrama de Clases.
En este diagrama se presentan las clases y paquetes a nivel general/genérico para ir organizando el código de la solución. 
Ubicación: diagramas/3. Clases.

💡 4. Organización del Código Fuente.
En este diagrama se la distribución de directorios para organizar el código fuente, según lo planteado para la arquitectura limpia. 
Ubicación: diagramas/4. Codigo.

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
