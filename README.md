# jbox2d

Execute o  comando abaixo no raiz deste projeto
`mvn deploy:deploy-file   -Dfile=lib/jbox2d-2.0.1-library-only.jar   -DpomFile=pom.xml   -DgeneratePom=true   -DrepositoryId=github   -Durl=https://maven.pkg.github.com/wpoliveiragit/maven-repository`

# Dependencia no pom
```xml
<dependency>
    <groupId>com.github.wpoliveiragit</groupId>
    <artifactId>jbox2d</artifactId>
    <version>2.0.0</version>
</dependency>
```