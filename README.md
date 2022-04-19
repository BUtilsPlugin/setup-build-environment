# Setup Build Environment

This is a
small [GitHub Composite Action](https://docs.github.com/en/actions/creating-actions/creating-a-composite-action)
for reducing boilerplate in our ci.


## Usage

```yaml
- name: Setup Build Environment
  uses: BUtilsPlugin/setup-build-environment@main
  with:
    jdk: 'temurin' # This is the default value
    jdk-version: '17' # This is the default value
```
