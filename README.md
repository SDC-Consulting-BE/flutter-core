# SDC Consulting - Flutter Core

This package contains a set of predefined and pre-styled widgets and utilities to easily setup new projects.

# Getting started

To start using the package, simply add this repo to your pubspec.yaml:

```yaml
dependencies:
  flutter_core:
    git:
      url: https://github.com/SDC-Consulting-BE/flutter-core
      ref: 'main'
```

Subsequently, there are a couple of steps required for the complete experience:

### Fonts

To use the predefined font, add the following to the pubspec.yaml file:

```yaml
flutter:
  fonts:
    - family: base
      fonts:
        - asset: packages/flutter_core/fonts/base/thin.ttf
          weight: 100
        - asset: packages/flutter_core/fonts/base/thinItalic.ttf
          weight: 100
          style: italic
        - asset: packages/flutter_core/fonts/base/light.ttf
          weight: 300
        - asset: packages/flutter_core/fonts/base/lightItalic.ttf
          weight: 300
          style: italic
        - asset: packages/flutter_core/fonts/base/regular.ttf
          weight: 400
        - asset: packages/flutter_core/fonts/base/italic.ttf
          weight: 400
          style: italic
        - asset: packages/flutter_core/fonts/base/medium.ttf
          weight: 500
        - asset: packages/flutter_core/fonts/base/mediumItalic.ttf
          weight: 500
          style: italic
        - asset: packages/flutter_core/fonts/base/bold.ttf
          weight: 700
        - asset: packages/flutter_core/fonts/base/boldItalic.ttf
          weight: 700
          style: italic
```

### Analysis options

To make use of the predefined analysis_options, create the analysis_options.yaml file and add the following line:

```yaml
include: package:flutter_core/analysis_options/analysis_options.yaml
```

The imported file contains additional instructions should they be necessary.

# Usage

For a list of the available widgets and utilities I refer you to the component library. [*TODO: insert link*]

### Setup

WIP