![Dart SDK Version](https://badgen.net/badge/Dart/3.4.0/blue)

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

This will ensure you always use the latest version of the lints. If you wish to restrict the lint version, specify a version of `analysis_options.yaml` instead:

```yaml
include: package:better_linter/analysis_options.1.0.0.yaml
```
