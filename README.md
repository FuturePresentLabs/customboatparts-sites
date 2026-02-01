# customboatparts-sites

Monorepo containing two Hugo landing sites:

- `sites/seattlecustomboatparts.com`
- `sites/floridacustomerboatparts.com`

Shared theme lives in `themes/landing`.

## TODO

- Set the real contact email (replace `CONTACT_EMAIL` in each site config).
- Decide hosting per site (Netlify/Vercel/S3+CloudFront/etc.) and wire each domain to the correct build output.

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
