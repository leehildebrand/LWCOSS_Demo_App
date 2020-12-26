# conference-app

Here will be some information about the app.

## How to start?

Get the object and data they talk about in the trail (see description for link) set up.

If you don't have:

1. The creds right in the .env file for your SF instance
2. The object and data it expects...
   ... It won't work.

If you don't have NPM in there yet...
`npm install`
Then to get a local server running...
`npm run watch`

The source files are located in the [`src`](./src) folder. All web components are within the [`src/client/modules`](./src/modules) folder. The folder hierarchy also represents the naming structure of the web components. The entry file for the custom Express configuration can be found in the ['src/server'](./src/server) folder.
