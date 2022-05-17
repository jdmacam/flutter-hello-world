- Nearly everything is a widget

- Scaffold if a widget which consists of an top app bar and a body

- You can add dependencies (which you can find at [pub.dev](https://pub.dev/)) to the **pubspec.yaml** with the command
> $ flutter pub add package_name

- You can pull packages from the **pubspec.yaml** into your project with the command (auto generates **pubspec.lock** (files with a lost of all packages pulled into the project)
> $ flutter pub get

- type ***'stful'*** in IDE to generate boilerplate code for a stateful widget: a **StatefulWidget** class, and a **State** class which is created by the StatefulWidget class

- In dart, prefixing an identifier with an underscore enforces privacy, and its best practice to for **State** objects to be private

- A **Set** doesnt allot duplicates, while a **List** does