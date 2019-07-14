# labo container coc markdownlint

markdownlint dependencies for labo container


###### Table of Contents

- [Requirements](#Requirements)
- [Usage](#Usage)
- [License](#License)

## Requirements

- node


## Usage

clone this repository and `npm install`

```bash
git clone https://github.com/getto-systems/labo-container-coc-markdownlint
npm install
```

edit `efm-langserver/config.yaml`

```yaml
languages:
  markdown:
    lint-command: '/path/to/markdownlint/node_modules/.bin/markdownlint -s'
    lint-stdin: true
    lint-formats:
      - '%f: %l: %m'
```


## License

labo-container-coc-markdownlint is licensed under the [MIT](LICENSE) license.

Copyright &copy; since 2018 shun@getto.systems
