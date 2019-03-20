## Demo Application

This NativeScript app was created using NativeScript CLI
``5.3.0-2019-03-20-13061`

It uses the `"useLegacyWorkflow": false` setting in
[nsconfig.json](nsconfig.json) in order to force webpack.

The application opens, crashes, and the CLI just hangs there.

To reproduce:

```
$ yarn install
$ yarn test ios
```
