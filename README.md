# Decentraland Avatar Assets

This repository contains the supporting assets for avatars in the Decentraland world. Please check https://github.com/decentraland/wearables-migration to publish this changes into the Content Servers.

## Getting Started

First, install and run the tests to verify that your system is ready to work with assets:

```
yarn install
make compile
make test && make catalog
```

## Pipeline

`make catalog` generates a new version of all the asset packs under the `assets` folder. All the files are stored in the `dist` folder, separated by asset pack.

### AWS

Use `UPLOAD_BUCKET_NAME` for the name of the bucket. Using `content-assets.decentraland.org` for production.
