# JIGSAW_JAVA11_EXAMPLES_MODULES_MAVEN

dependency must be installed via
mvn clean install

To run after {mvn package} =>                   <calling class>
    java --module-path build -m user/default__.User
                        <build path>    <package name>
                               <module name>

package names in other modules cant be clashes