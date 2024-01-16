# analysis_options_tbs
The set of rules that encourage good coding practices for applications

## Getting Started

To add the package, analysis_options_tbs, to an project:

1. Depend on it
   - Add `analysis_options_tbs` under `dev_dependencies` in the `pubspec.yaml` file.

2. Install it
   - From the terminal: Run `flutter pub get`.

3. Import it
   - Add a corresponding include statement in the YAML code.

## Usage

To use the analysis options, add the following dev dependency in your `pubspec.yaml` file:

```yaml
dev_dependencies:
  analysis_options_tbs: 
    git:
      url: https://github.com/BhoomiPatel007/analysis_options_tbs.git
```


Add the following line in your analysis_options.yaml file:

```yaml
include: package:analysis_options_tbs/analysis_options.yaml
```
