# Dart Playground

https://dart.dev/language

- [pubspec.yaml](pubspec.yaml) - project / build file, like `pom.xml` in Java
- [pubspec.lock](pubspec.lock) - dependency lock file, automatically generated
- [bin](bin) - contains the main Dart files
- [playground.dart](bin/playground.dart) - main entry point of the application because it's defined in `pubspec.yaml` as the `main` file
- `dart run` - command to run the Dart application - it will run playground.dart since it's defined as the main file in `pubspec.yaml`, otherwise you can run any Dart file directly with `dart bin/<file>.dart`
- [lib](lib) - contains the library / common / reusable code files
- [test](test) - contains the test files
- [analysis_options.yaml](analysis_options.yaml) - configuration file for the Dart analyzer, used to enforce coding standards and rules

## Language

- [hello.dart](bin/hello.dart) - a simple Dart program that prints "Hello, World!" to the console, run with `dart bin/hello.dart`
- [Variables](https://dart.dev/language/variables)
- [Operators](https://dart.dev/language/operators)
- [Comments](https://dart.dev/language/comments)
- Types
  - [Built-in types](https://dart.dev/language/built-in-types)
