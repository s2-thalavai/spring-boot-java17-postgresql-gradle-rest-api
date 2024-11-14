
# spring-boot-java17-postgresql-gradle-rest-api

Spring Boot Java17 PostgreSQL REST API


### Getting Started


        PS E:\git\s2-thalavai\spring-boot-java17-postgresql-gradle-rest-api> ./gradlew

            > Task :help

            Welcome to Gradle 8.10.2.

            To run a build, run gradlew <task> ...

            To see a list of available tasks, run gradlew tasks

            To see more detail about a task, run gradlew help --task <task>

            To see a list of command-line options, run gradlew --help

            For more detail on using Gradle, see https://docs.gradle.org/8.10.2/userguide/command_line_interface.html

            For troubleshooting, visit https://help.gradle.org

            BUILD SUCCESSFUL in 1s
            1 actionable task: 1 executed 

        PS E:\git\s2-thalavai\spring-boot-java17-postgresql-gradle-rest-api>


------------------------------------------------------------


PS E:\git\s2-thalavai\spring-boot-java17-postgresql-gradle-rest-api> ./gradlew tasks

> Task :tasks

------------------------------------------------------------
Tasks runnable from root project 'spring-boot-java17-postgresql-gradle-rest-api'
------------------------------------------------------------

Application tasks
-----------------
bootRun - Runs this project as a Spring Boot application.
bootTestRun - Runs this project as a Spring Boot application using the test runtime classpath.

Build tasks
-----------
assemble - Assembles the outputs of this project.
bootBuildImage - Builds an OCI image of the application using the output of the bootJar task
bootJar - Assembles an executable jar archive containing the main classes and their dependencies.
build - Assembles and tests this project.
buildDependents - Assembles and tests this project and all projects that depend on it.
buildNeeded - Assembles and tests this project and all projects it depends on.
classes - Assembles main classes.
clean - Deletes the build directory.
jar - Assembles a jar archive containing the classes of the 'main' feature.
resolveMainClassName - Resolves the name of the application's main class.
resolveTestMainClassName - Resolves the name of the application's test main class.
testClasses - Assembles test classes.

Build Setup tasks
-----------------
init - Initializes a new Gradle build.
updateDaemonJvm - Generates or updates the Gradle Daemon JVM criteria.
wrapper - Generates Gradle wrapper files.

Documentation tasks
-------------------
javadoc - Generates Javadoc API documentation for the 'main' feature.

Help tasks
----------
buildEnvironment - Displays all buildscript dependencies declared in root project 'spring-boot-java17-postgresql-gradle-rest-api'.
dependencies - Displays all dependencies declared in root project 'spring-boot-java17-postgresql-gradle-rest-api'.
dependencyInsight - Displays the insight into a specific dependency in root project 'spring-boot-java17-postgresql-gradle-rest-api'.
dependencyManagement - Displays the dependency management declared in root project 'spring-boot-java17-postgresql-gradle-rest-api'.
help - Displays a help message.
javaToolchains - Displays the detected java toolchains.
outgoingVariants - Displays the outgoing variants of root project 'spring-boot-java17-postgresql-gradle-rest-api'.
projects - Displays the sub-projects of root project 'spring-boot-java17-postgresql-gradle-rest-api'.
properties - Displays the properties of root project 'spring-boot-java17-postgresql-gradle-rest-api'.
resolvableConfigurations - Displays the configurations that can be resolved in root project 'spring-boot-java17-postgresql-gradle-rest-api'.
tasks - Displays the tasks runnable from root project 'spring-boot-java17-postgresql-gradle-rest-api'.

Verification tasks
------------------
check - Runs all checks.
test - Runs the test suite.

Rules
-----
Pattern: clean<TaskName>: Cleans the output files of a task.
Pattern: build<ConfigurationName>: Assembles the artifacts of a configuration.

To see all tasks and more detail, run gradlew tasks --all

To see more detail about a task, run gradlew help --task <task>

BUILD SUCCESSFUL in 1s
1 actionable task: 1 executed


PS E:\git\s2-thalavai\spring-boot-java17-postgresql-gradle-rest-api>


------------------------------------------------------------



PS E:\git\s2-thalavai\spring-boot-java17-postgresql-gradle-rest-api> ./gradlew bootRun

> Task :bootRun

  .   ____          _            __ _ _
 /\\ / ___'_ __ _ _(_)_ __  __ _ \ \ \ \
( ( )\___ | '_ | '_| | '_ \/ _` | \ \ \ \
 \\/  ___)| |_)| | | | | || (_| |  ) ) ) )
  '  |____| .__|_| |_|_| |_\__, | / / / /
 =========|_|==============|___/=/_/_/_/

 :: Spring Boot ::                (v3.3.5)

2024-11-14T17:42:34.683+05:30  INFO 8652 --- [spring-boot-java17-postgresql-gradle-rest-api] [  restartedMain] Java17PostgresqlGradleRestApiApplication : Starting SpringBootJava17PostgresqlGradleRestApiApplication using Java 17.0.2 with PID 8652 (E:\git\s2-thalavai\spring-boot-java17-postgresql-gradle-rest-api\build\classes\java\main started by s2tha in E:\git\s2-thalavai\spring-boot-java17-postgresql-gradle-rest-api)
2024-11-14T17:42:34.683+05:30  INFO 8652 --- [spring-boot-java17-postgresql-gradle-rest-api] [  restartedMain] Java17PostgresqlGradleRestApiApplication : No active profile set, falling back to 1 default profile: "default"
2024-11-14T17:42:34.763+05:30  INFO 8652 --- [spring-boot-java17-postgresql-gradle-rest-api] [  restartedMain] .e.DevToolsPropertyDefaultsPostProcessor : Devtools property defaults active! Set 'spring.devtools.add-properties' to 'false' to disable
2024-11-14T17:42:34.763+05:30  INFO 8652 --- [spring-boot-java17-postgresql-gradle-rest-api] [  restartedMain] .e.DevToolsPropertyDefaultsPostProcessor : For additional web related logging consider setting the 'logging.level.web' property to 'DEBUG'
2024-11-14T17:42:35.585+05:30  INFO 8652 --- [spring-boot-java17-postgresql-gradle-rest-api] [  restartedMain] o.s.b.w.embedded.tomcat.TomcatWebServer  : Tomcat initialized with port 8080 (http)
2024-11-14T17:42:35.585+05:30  INFO 8652 --- [spring-boot-java17-postgresql-gradle-rest-api] [  restartedMain] o.apache.catalina.core.StandardService   : Starting service [Tomcat]
2024-11-14T17:42:35.585+05:30  INFO 8652 --- [spring-boot-java17-postgresql-gradle-rest-api] [  restartedMain] o.apache.catalina.core.StandardEngine    : Starting Servlet engine: [Apache Tomcat/10.1.31]
2024-11-14T17:42:35.636+05:30  INFO 8652 --- [spring-boot-java17-postgresql-gradle-rest-api] [  restartedMain] o.a.c.c.C.[Tomcat].[localhost].[/]       : Initializing Spring embedded WebApplicationContext
2024-11-14T17:42:35.636+05:30  INFO 8652 --- [spring-boot-java17-postgresql-gradle-rest-api] [  restartedMain] w.s.c.ServletWebServerApplicationContext : Root WebApplicationContext: initialization completed in 873 ms
2024-11-14T17:42:35.870+05:30  INFO 8652 --- [spring-boot-java17-postgresql-gradle-rest-api] [  restartedMain] o.s.b.d.a.OptionalLiveReloadServer       : LiveReload server is running on port 35729
2024-11-14T17:42:35.886+05:30  INFO 8652 --- [spring-boot-java17-postgresql-gradle-rest-api] [  restartedMain] o.s.b.w.embedded.tomcat.TomcatWebServer  : Tomcat started on port 8080 (http) with context path '/'
2024-11-14T17:42:35.902+05:30  INFO 8652 --- [spring-boot-java17-postgresql-gradle-rest-api] [  restartedMain] Java17PostgresqlGradleRestApiApplication : Started SpringBootJava17PostgresqlGradleRestApiApplication in 1.485 seconds (process running for 1.77)
<==========---> 80% EXECUTING [9s]
> :bootRun
Terminate batch job (Y/N)? y
PS E:\git\s2-thalavai\spring-boot-java17-postgresql-gradle-rest-api>


------------------------------------------------------------


PS E:\git\s2-thalavai\spring-boot-java17-postgresql-gradle-rest-api> ./gradlew build
OpenJDK 64-Bit Server VM warning: Sharing is only supported for boot loader classes because bootstrap classpath has been appended

BUILD SUCCESSFUL in 6s
7 actionable tasks: 4 executed, 3 up-to-date
PS E:\git\s2-thalavai\spring-boot-java17-postgresql-gradle-rest-api>


------------------------------------------------------------
