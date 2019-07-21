# artifacts
mvn-repo br.com.cafebinario


## use repository with Maven:

  <repositories>
  ...
  
		<repository>
			<id>mvn-repo</id>
			<url>https://raw.github.com/JimSP/artifacts/master</url>

			<releases>
				<enabled>true</enabled>
			</releases>

			<snapshots>
				<enabled>true</enabled>
			</snapshots>
		</repository>
    
  ...
	</repositories>


  ## use repository with Gradle:

  repositories {
  ...
  
		maven {
      		url 'https://raw.github.com/JimSP/artifacts/master'
    	}
  
  ...
	}


# Catalog
  
## Maven

  <dependency>
			<groupId>br.com.cafebinario</groupId>
			<artifactId>logger-annotation</artifactId>
			<version>1.0.0-RELEASE</version>
  </dependency>


## Gradle

    dependencies {
		  compile 'br.com.cafebinario:logger-annotation:1.0.0-RELEASE'
	  }
