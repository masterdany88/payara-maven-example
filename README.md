# Payara Micro Maven Plugin Example

The [payara-micro-maven-plugin](https://github.com/payara/ecosystem-maven/tree/master/payara-micro-maven-plugin)
does not come with a bare minimum example.

## Usage

Bundle an application:

    mvn install payara-micro:bundle

Run the bundled application:

    java -jar target/payara-maven-helloworld-1.0-SNAPSHOT-microbundle.jar

Test the running application at http://localhost:8080/helloworld

Start the application without bundling:

    mvn package payara-micro:start

Test the running application at http://localhost:8080/payara-maven-helloworld-1.0-SNAPSHOT/helloworld