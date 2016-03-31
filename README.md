# mavenWebAppTest

Universidad EAFIT

Departamento de Informática y Sistemas

Ingeniería de Sistemas

@author Edwin Montoya Munera - emontoya@eafit.edu.co

proyecto de prueba para Build & Deploy de proyectos WebJava en Tomcat con Jenkins.

Tener en cuenta este plugin en el pom.xml para el deploy en un servidor Tomcat 8

	<plugin>
		<groupId>org.apache.tomcat.maven</groupId>
		<artifactId>tomcat7-maven-plugin</artifactId>
		<version>2.2</version>
		<configuration>
			<url>http://localhost:8080/manager/text</url>
			<server>TomcatServer</server>
			<path>/mkyongWebApp</path>
		</configuration>
	</plugin>
