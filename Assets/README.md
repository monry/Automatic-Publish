# Automatic Publish

## Installation

### Use Command Line

```bash
upm add package dev.monry.automatic-publish
```

Note: `upm` command is provided by [this repository](https://github.com/upm-packages/upm-cli).

### Edit `Packages/manifest.json`

```jsonc
{
  "dependencies": {
    // (snip)
    "dev.monry.automatic-publish": "[latest version]", 
    // (snip)
  },
  "scopedRegistries": [
    {
      "name": "Unofficial Unity Package Manager Registry",
      "url": "https://upm-packages.dev",
      "scopes": [
        "dev.monry"
      ]
    }
  ]
}
```

## Usages

* 
