[![Test](https://github.com/snow-actions/composite-action-template/actions/workflows/test.yml/badge.svg)](https://github.com/snow-actions/composite-action-template/actions/workflows/test.yml)

# Create a Composite Action

Click the `Use this template` to bootstrap the creation of a [composite action](https://docs.github.com/en/actions/creating-actions/creating-a-composite-action).:rocket:

This template includes tests, a validation workflow and versioning guidance.

Learn how to use this template at [Wiki](https://github.com/snow-actions/composite-action-template/wiki).

## Usage

See [action.yml](action.yml)

### Basic

```yml
steps:
  - uses: snow-actions/composite-action-template@v1.0.0
```

### Optional

```yml
steps:
  - uses: snow-actions/composite-action-template@v1.0.0
    with:
      who-to-greet: Your name
```
