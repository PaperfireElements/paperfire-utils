[![Published on webcomponents.org](https://img.shields.io/badge/webcomponents.org-published-blue.svg?style=flat-square)](https://www.webcomponents.org/element/PaperfireElements/paperfire-utils)

# \<paperfire-utils\>

A collection of firebase helpers. Requires firebase to have been initialized and available.

<!--
```
<custom-element-demo>
  <template>
    <link rel="import" href="firebase-diconnect.html">
    <link rel="import" href="firebase-once.html">
    <next-code-block></next-code-block>
  </template>
</custom-element-demo>
```
-->
```html
<pre>This isn't using live data yet</pre>
<firebase-disconnect path="demo/paperfire-utils/disconnect" update-online="onlineObject" update-disconnect="offlineObject"></firebase-disconnect>
<firebase-once path="demo/paperfire-utils/once" exists="{{exists}}"></firebase-once>
```

## Install the Polymer-CLI

First, make sure you have the [Polymer CLI](https://www.npmjs.com/package/polymer-cli) installed. Then run `polymer serve` to serve your element locally.

## Viewing Your Element

```
$ polymer serve
```

## Running Tests

```
$ polymer test
```

Your application is already set up to be tested via [web-component-tester](https://github.com/Polymer/web-component-tester). Run `polymer test` to run your application's test suite locally.
