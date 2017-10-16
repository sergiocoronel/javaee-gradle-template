# javaee-gradle-template
Template of a jee project using gradle: ear, ejb, war. JSF.



EJB - Example of common dependencies: guava, gson, pdfbox, hibernate wildfly provided, local dependencies, etc.

WAR - JSF: Principal frameworks and libraries: Primefaces, Omnifaces, primefaces themes, apache commons, etc.

EAR - Gradle configured to generate the following structure (most relevant part):

      EAR
      -EJB.jar
      -WAR.war
         -WEB-INF/lib
      -lib (Ejb dependencies)



