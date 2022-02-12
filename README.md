# spectral-custom-function-example

This is an example of using hosted Spectral rulesets with custom functions.

## Usage

Warning example:

```
echo '{"greeting": {"message": "nope"}}' | spectral lint \
  -r https://raw.githubusercontent.com/kevinswiber/spectral-custom-function-example/main/ruleset.yaml
```

Passing example:

```
echo '{"greeting": {"message": "hello"}}' | spectral lint \
  -r https://raw.githubusercontent.com/kevinswiber/spectral-custom-function-example/main/ruleset.yaml
```

## License

MIT
