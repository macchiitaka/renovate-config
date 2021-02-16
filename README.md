# renovate-config-macchiitaka

A sharable Renovate config for macchiitaka.

## Usage

- `renovate.json`

```json
{
  "extends": [
    "github>macchiitaka/renovate-config",
    ":assignAndReview(GITHUB_USERNAME)"
  ]
}
```

## Settings

See the settings in [package.json](https://github.com/macchiitaka/renovate-config/blob/main/package.json) and [Configuration Options](https://renovatebot.com/docs/configuration-options/) in Renovate Docs

## License

MIT License
