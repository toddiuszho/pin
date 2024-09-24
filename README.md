# pin

`package.json` Explorer CLI

# Requirements

- [bash](https://www.gnu.org/software/bash/) 3.2+
- [jq](https://github.com/jqlang/jq) 1.5+

# Getting Started

CWD to a directory with a `package.json` in it

```shell
pin help
```

## Other Locations

You can do `pin CMD winding/path/to/elsewhere` to get package information in another directory. "elsewhere" can point to either the parent directory _or_ the `package.json` file itself.

### Example

```shell
pin info node_modules/@nestjs/core
```

