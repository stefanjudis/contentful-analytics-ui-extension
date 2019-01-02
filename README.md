# Contentful Analytics UI-extension

> Access Google Analytics data right in Contentful

![Analytics extension embeddedin Contentful interface](./screenshot.jpg)

## Getting started

To to authorize the Google Analytics API several steps are needed. Head to the [SETUP.md](./setup/index.md) for all the instructions. :)

## Functionality

Every Contentful UI extension runs in an iframe inside of the Contentful web application. This extension loads the url [contentful-analytics.netlify.com](https://github.com/stefanjudis/contentful-analytics-ui-extension/blob/master/extension.json#L5) to make the OAuth flow working with Google APIs

## Features

- [x] Log into Google Analytics
- [x] Select date range
- [x] Select day/week/month dimension
- [ ] Make url path generation more flexible
- [ ] Make more metrics accessible
- [ ] Store last settings in LocalStorage

## Licence

MIT
