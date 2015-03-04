This is example showing how to use Koofr Java SDK in your Maven project.

# Create JAR

`
mvn assembly:assembly -DdescriptorId=jar-with-dependencies
`

# Run

`
java -cp target/KoofrExample-0.0.1-SNAPSHOT-jar-with-dependencies.jar info.Main app.koofr.net <USERNAME> <PASSWORD>
`
