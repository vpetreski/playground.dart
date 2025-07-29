# Dart Playground

https://dart.dev/docs

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
  - [Records](https://dart.dev/language/records)
  - [Collections](https://dart.dev/language/collections)
  - [Generics](https://dart.dev/language/generics)
  - [Typedefs](https://dart.dev/language/typedefs)
  - [Type System](https://dart.dev/language/type-system)
- Patterns
  - [Overview & Usage](https://dart.dev/language/patterns)
  - [Pattern Types](https://dart.dev/language/pattern-types)
  - [Applied Tutorial](https://codelabs.developers.google.com/codelabs/dart-patterns-records)
- Control Flow
  - [Loops](https://dart.dev/language/loops)
  - [Branches](https://dart.dev/language/branches)
  - [Error Handling](https://dart.dev/language/error-handling)
- [Functions](https://dart.dev/language/functions)
- [Metadata](https://dart.dev/language/metadata)
- [Libraries & Imports](https://dart.dev/language/libraries)
- Classes & Objects
  - [Classes](https://dart.dev/language/classes)
  - [Constructors](https://dart.dev/language/constructors)
  - [Methods](https://dart.dev/language/methods)
  - [Extend a class](https://dart.dev/language/extend)
  - [Mixins](https://dart.dev/language/mixins)
  - [Enumerated Types](https://dart.dev/language/enums)
  - [Extension Methods](https://dart.dev/language/extension-methods)
  - [Extension Types](https://dart.dev/language/extension-types)
  - [Callable Objects](https://dart.dev/language/callable-objects)
- Class Modifiers
  - [Overview & Usage](https://dart.dev/language/class-modifiers)
  - [Class modifiers for API maintainers](https://dart.dev/language/class-modifiers-for-apis)
  - [Class modifiers reference](https://dart.dev/language/modifier-reference)
- Concurrency
  - [Overview](https://dart.dev/language/concurrency)
  - [Asynchronous Programming](https://dart.dev/language/async)
  - [Isolates](https://dart.dev/language/isolates)
- [Null Safety...](https://dart.dev/language/null-safety)

## Core Libraries

- [Overview](https://dart.dev/libraries/libraries)
- [dart:core](https://dart.dev/libraries/dart-core)
- [dart:async](https://dart.dev/libraries/dart-async)
- [dart:math](https://dart.dev/libraries/dart-math)
- [dart:convert](https://dart.dev/libraries/dart-convert)
- [dart:io](https://dart.dev/libraries/dart-io)
- [dart:js_interop](https://dart.dev/interop/js-interop)
- [Iterable Collections](https://dart.dev/libraries/collections/iterables)
- Asynchronous Programming
  - [Tutorial](https://dart.dev/libraries/async/async-await)
  - [Futures and error handling](https://dart.dev/libraries/async/futures-error-handling)
  - [Using Streams](https://dart.dev/libraries/async/using-streams)
  - [Creating Streams](https://dart.dev/libraries/async/creating-streams)

## Effective Dart