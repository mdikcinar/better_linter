![Dart SDK Version](https://badgen.net/badge/Dart/3.9.0/blue)

## Usage

To use the lints, add as a dev dependency in your `pubspec.yaml`:

```yaml
dev_dependencies:
  better_linter:
    git:
      url: git@github.com:mdikcinar/better_linter.git
      ref: master
```

Then, add an include in `analysis_options.yaml`:

```yaml
include: package:better_linter/analysis_options.yaml
```