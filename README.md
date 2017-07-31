# Rise Bakery

This repository contains the shopify theme for rise.

## Installation

*Install shopify theme kit*

```bash
curl -s https://raw.githubusercontent.com/Shopify/themekit/master/scripts/install | sudo python
```

*Get an API password*

Log in to shopify admin, navigate to `Apps` => `Private apps` => `Generate API credentials`. Ensure you select `Theme templates and assets` and `Script tags in your store's theme template files` with `Read and Write` access. Hit save and copy the generated password.

*Setup theme kit with Rise's theme*

The below outputs a `config.yml` in the current directory, which is ignored by git. Theme kit uses this to sync with the shopify store.

```bash
theme configure --password=[your-api-password] --store=rise-bakery.myshopify.com] --themeid=176467657
```

## Download latest theme from shopify

```Bash
theme download
```

## Watch mode

```bash
theme watch
```

## Updating the theme in Development

```bash
theme replace
```

## Updating the theme on Production

```bash
theme replace --allenvs
```