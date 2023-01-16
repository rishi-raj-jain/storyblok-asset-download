# Download all your Assets from Storyblok

> An easy way to download all your assets from Storyblok.

This script will create the first level folder structure you have in Storyblok and downloads the assets accordingly. If you did not added your assets in asset folder they will be downloaded in the root `download` folder of your checked out repository.

## When to run

Since traffic is a paid parameter do not download your assets every hour; If you have a customer that lost their images and you want to download them without downloading them manually this script is for you.

## How to run

1. Install dependencies:

```
npm install
```

2. Add two .env variables:

```bash
# filename: .env

# on your space dashboard
STORYBLOK_SPACE_ID=

# https://www.storyblok.com/docs/management-api/authentication#authentication
STORYBLOK_ACCOUNT_OAUTH_TOKEN=
```

3. Run the script

```
node index.js
```
