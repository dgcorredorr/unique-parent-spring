<p align="center">
  <a href="https://spring.io/projects/spring-boot" target="blank"><img src="https://upload.wikimedia.org/wikipedia/commons/thumb/4/44/Spring_Framework_Logo_2018.svg/2560px-Spring_Framework_Logo_2018.svg.png" width="320" alt="Spring Boot Logo" /></a>
</p>

# **Unique Parent Spring**

## **Descripción**
Este repositorio contiene un proyecto parent para aplicaciones basadas en Spring Boot. Su objetivo es centralizar la configuración de dependencias, plugins y propiedades comunes a los microservicios, facilitando la gestión y actualización de los proyectos que heredan de este parent.

## **Pre-requisitos**
Para clonar y utilizar este proyecto parent, necesitará [Git](https://git-scm.com), [Java 17.0.11](https://www.oracle.com/java/technologies/javase/jdk17-archive-downloads.html), y [Maven](https://maven.apache.org/download.cgi) instalados en su computadora.

Desde su línea de comando:

```bash
# Clonar repositorio
$ git clone https://github.com/dgcorredorr/unique-parent-spring

# Entrar al repositorio local
$ cd unique-parent-spring

# Instalar localmente
$ mvn clean install
```

## **Uso**
Este proyecto está diseñado para ser utilizado como un parent en otros proyectos Maven. Para ello, simplemente incluya la siguiente sección en el `pom.xml` de su proyecto:

```xml
<parent>
    <groupId>com.meli</groupId>
    <artifactId>unique-parent-spring</artifactId>
    <version>1.0.0-SNAPSHOT</version>
</parent>
```

## **Configuración**
Este parent incluye configuraciones predefinidas para:

- **Versiones de dependencias** como Spring Boot, MongoDB Driver, y otras.
- **Plugins de construcción** como Jacoco para cobertura de código y SonarQube para análisis estático.
- **Propiedades comunes** como la versión de Java y codificación de fuente.

## **Autores**
Para cualquier duda o contribución, puede contactar a:

| Operación             | Autor                  | Correo                    |
| --------------------- |------------------------|---------------------------|
| General               | David Corredor Ramírez | dgcorredorr@gmail.com |