# plugin-dnx-assume

This is a one-cli plugin that adds extra assume role entry command to the CLI.


## Configuration

```yaml
# one.yaml
plugins:
  dnx-assume:
    source: https://github.com/DNXLabs/plugin-dnx-assume/archive/master.tar.gz
    parameters:
      aws-role: <redact>
      aws-account-id: <redact>
```

## Usage

```bash
one dnx-assume
```

## Author

Managed by [DNX Solutions](https://github.com/DNXLabs).

## License

Apache 2 Licensed. See [LICENSE](https://github.com/DNXLabs/plugin-dnx-assume/blob/master/LICENSE) for full details.