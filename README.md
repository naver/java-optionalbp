# Java Optional Backport

_java-optionalbp_: Java 6/7 compatible minimal backport of java.lang.Optional

## How to Build

```
$ gradle jar
```

## List of files

- `README.md`: this README.
- `LICENSE`: the GNU General Public License Version 2 with Classpath Exception.
- `ASSEMBLY_EXCEPTION`: the OpenJDK Assembly Exception.
- `Optional.java`: the Java class com.naver.java.optionalbp.Optional implementation.
- `build.gradle`: a Gradle script to build a JAR artifact.
- `.gitignore`: see [gitignore(5) man page](https://git-scm.com/docs/gitignore).

This project contains some files from OpenJDK jdk8u mercurial jdk8u/jdk@12544:070118445584f (<http://hg.openjdk.java.net/jdk8u/jdk8u/jdk/file/07011844584f>).

- `LICENSE`, `ASSEMBLY_EXCEPTION`: not modified from the original ones.
- `Optional.java`: modified. (original path: src/share/classes/java/util/Optional.java)

`README.md`, `build.gradle` and `.gitignore` are original work of this project.

## License

Use of _java-optionalbp_ is granted under the GNU General Public License Version 2 with Classpath Exception (GPLv2+CE). See `LICENSE`.

`LICENSE`, `ASSEMBLY_EXCEPTION` is not in the scope of GPLv2+CE; These files are parts of license itself. You can redistribute this project with these files modified (i.e. licensed differently).

The _java-optionalbp_ original works, `README.md`, `build.gradle` and `.gitignore`, are not in the scope of GPLv2+CE. These files are distributed under public domain.

## Trademark notice

Java and OpenJDK are trademarks or registered trademarks of Oracle and/or its affiliates.
