# Jar Ejecutable con Gradle
Código fuente de ejemplo para la entrada del blog [Jar Ejecutable con Gradle](https://www.hermanbarrantes.dev/jar-ejecutable-con-gradle/).

## Compilación

Copiando dependencias

```shell
$ ./gradlew :copy:build
$ java -jar copy/build/libs/copy.jar
```

Usando [Gradle Java Plugin](https://docs.gradle.org/current/userguide/java_plugin.html)

```shell
$ ./gradlew :example:build
$ java -jar example/build/libs/example.jar
```

Usando la tarea propia

```shell
$ ./gradlew :task:fatJar
$ java -jar task/build/libs/task-all.jar
```

Usando [Gradle Shadow Plugin](https://imperceptiblethoughts.com/shadow/)

```shell
$ ./gradlew :plugin:build
$ java -jar plugin/build/libs/plugin-all.jar
```

