# How to set up the Google Analytics Contentful extension

To make use of Google Analytics Embed API in Contentful you have to perform two steps:

1. Install the UI-extension
2. Create new Analytics application
3. Configure Analytics application
4. Configure Analytics UI extension

## Install the UI extension

You can install a Contentful UI extension either via the CLI or with the one-click installer directly in the web app.

### Install via Web app (recommended)

Inside of the Contentful web app you can go to "Settings -> Extensions" and follow "Add extension ->
Install from Github". Paste the URL of this extension's discriptor (`https://github.com/stefanjudis/contentful-analytics-ui-extension/blob/master/extension.json`) into the dialog.

![Dialog asking for extension descriptor](./install-from-github.jpg).

This process will set up the UI extension and no further action is needed at this point.

![Configuration of the UI extension](./extension-configuration.jpg).

### Install via CLI

```
$ git clone git@github.com:stefanjudis/contentful-analytics-ui-extension.git
$ cd contentful-analytics-ui-extension
$ npm i
$ npm run create -- --space-id XXX
```

The `npm run create` command uses the [Contentful CLI](https://www.npmjs.com/package/contentful-cli). This approach is recommended when you want to develop this extension.

## Create new Analytics application

## Configure Analytics application

## Configure Analytics UI extension
