<img src="https://github.com/arago/hiro-graph-js/blob/master/logo.png" alt="HIRO Graph JS" width="800px" />

# HIRO Graph Javascript Libraries

These libraries are for interacting with the HIRO Graph API. For full details of the API see the [HIRO Graph Docs](https://docs.hiro.arago.co/hiro/current/developer/hiro-graph-api/).

## Packages

All the packages here are available on npm. Check the [packages](packages/) directory for the full list.

Each package maintains it's own documentation:

 - [`hiro-graph-client`](/packages/hiro-graph-client/)
 - [`hiro-graph-codecs`](/packages/hiro-graph-codecs/)
 - [`hiro-graph-gremlin`](/packages/hiro-graph-gremlin/)
 - [`hiro-graph-implicit-oauth`](/packages/hiro-graph-implicit-oauth/)
 - [`hiro-graph-lucene`](/packages/hiro-graph-lucene/)
 - [`hiro-graph-orm`](/packages/hiro-graph-orm/)
 - [`hiro-graph-orm-mappings`](/packages/hiro-graph-orm-mappings/)
 - [`hiro-graph-redux`](/packages/hiro-graph-redux/)

## Development

To work on these packages, a tool called `lerna` is used. To get up and running:

```
$ npm install
$ npm run lerna -- bootstrap
```
