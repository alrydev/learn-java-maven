# learn-java-maven
run this command to generate a new Maven project: <br/> <br/>
mvn archetype:generate -DgroupId=com.alridiputra -DartifactId=book-catalog -DarchetypeArtifactId=maven-archetype-quickstart -DarchetypeVersion=1.4 -DinteractiveMode=false
<br/> <br/>
``` mvn archetype ```
generate is a command used in Maven, a build automation tool for Java projects, to generate a new Maven project based on a specified archetype.

The ``` -DgroupId ``` option sets the group identifier for the generated project. In this case, it is set to com.alridiputra.

The ``` -DartifactID ``` option sets the artifact identifier for the generated project. In this case, it is set to book-catalog.

The ``` -DarchetypeArtifactID ``` option sets the archetype artifact identifier for the archetype to be used. In this case, it is set to maven-archetype-quickstart, which is a simple archetype that creates a basic Maven project structure with a single Java class.

The ``` -DarchetypeVersion ``` option sets the version of the archetype to be used. In this case, it is set to 1.4.

The ``` -DinteractiveMode=false ``` option disables the interactive mode of Maven, which means that Maven will use the default values for any options that are not specified on the command line.

