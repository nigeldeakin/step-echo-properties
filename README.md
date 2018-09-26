# step-echo-properties

This step simply echoes its properties 

# Options

- `prop1` (optional) A property that will be echoed
- `prop2` (optional) A property that will be echoed
- `prop3` (optional) A property that will be echoed
- `prop4` (optional) A property that will be echoed
- `prop1` (optional) A property that will be echoed

# Example

```yaml
build:
  ...
  after-steps:
    - nigeldeakin/echo-properties:
        prop1: Hello 
        prop2: World 
```

# Changelog

## 0.0.1

- Initial release

