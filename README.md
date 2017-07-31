# Rise Bakery

This repository contains the shopify theme for rise.

## Installation

### Install shopify theme kit*

```bash
curl -s https://raw.githubusercontent.com/Shopify/themekit/master/scripts/install | sudo python
```

### Get an API password

Log in to shopify admin, navigate to `Apps` => `Private apps` => `Generate API credentials`. Ensure you select `Theme templates and assets` and `Script tags in your store's theme template files` with `Read and Write` access. Hit save and copy the generated password.

### Edit config.yml

Edit `config.yml.reference` in this repository with the API password you generated. Name the file `config.yml` but do not delete the `.reference` file.

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