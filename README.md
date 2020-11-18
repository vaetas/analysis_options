# Strict Analysis Options

Lint options used in my projects.

## Usage

Include this project in your `pubspec.yaml` file:

```yaml
dev_dependencies:
  analysis_options:
    git: https://github.com/vaetas/analysis_options.git
```

Then create an analysis_options.yaml file in the root of your project and put the following line inside:

```yaml
include: package:analysis_options/analysis_options.yaml
```

## Thanks

This package uses [very_good_analysis](https://github.com/VeryGoodOpenSource/very_good_analysis) as a base.