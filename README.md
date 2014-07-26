## Sample Gradle Project

This is my project files and notes as I followed Dr. William Billingsley's video tutorial at http://www.youtube.com/watch?v=PFyNzkwiMNs.

## Install Gradle

The video does not mention about installing gradle. To install gradle, follow the documentation at http://www.gradle.org/installation. Gradle requires JDK 1.5 or higher.

I use Mac OSX and I prefer to install gradle via homebrew.

```
$ brew update
$ brew install gradle
$ gradle -version

------------------------------------------------------------
Gradle 2.0
------------------------------------------------------------

... (omitted for brevity)
```

### Compile Java source files
```
$ gradle compileJava
```

## Run test
```
$ gradle test
```
