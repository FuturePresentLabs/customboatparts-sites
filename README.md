# customboatparts-sites

Monorepo containing two Hugo landing sites:

- `sites/seattlecustomboatparts.com`
- `sites/floridacustomerboatparts.com`

Shared theme lives in `themes/landing`.

## Local dev

```bash
# Seattle
cd sites/seattlecustomboatparts.com
hugo server

# Florida
cd ../floridacustomerboatparts.com
hugo server
```

## Build

```bash
cd sites/seattlecustomboatparts.com && hugo
cd ../floridacustomerboatparts.com && hugo
```
