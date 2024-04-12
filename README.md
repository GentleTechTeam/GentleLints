# GentleLints
[![License](https://img.shields.io/badge/license-MIT-blue.svg)](LICENSE)

GentleLints is a comprehensive lint rule package designed for Flutter and Dart projects. It provides a curated set of lint rules to ensure code consistency, readability, and maintainability across your Flutter and Dart codebases.

## Features:

- **Consistency**: Establishes consistent coding standards across your Flutter and Dart projects.
- **Readability**: Promotes code clarity and readability by enforcing best practices and style conventions.
- **Maintainability**: Helps in writing maintainable code by identifying potential issues and enforcing coding guidelines.

## Installation and usage

1. Add lint_rules_flutter_dart as a dependency in your pubspec.yaml file:

    ```yaml
    dependencies:
      gentle_lints:
        git:
          url: git@github.com:GentleTechTeam/GentleLints.git
    ```

2. Run `flutter pub get` to fetch the package from the Git repository and add it to your project.

3. Create analysis_options.yaml file
    ```
    include: package:gentle_lints/analysis_options.yaml
    ```

    See the dartanalyzer executing the lint checks in you favorite editor.

## License

This project is licensed under the [MIT License](LICENSE).

## Contact

- Author: Gentle Tech Team
- Email: gentletechteam@gmail.com
- Website: [gentletech.net](gentletech.net)






