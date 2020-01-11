# v23

This is v2 to v3 YAML format converter

you need ``node.JS`` and ``js-yaml`` module installed

go to [nodejs.org](https://nodejs.org/en) to download the latest node.js
after installing node.js add js-yaml module, better globally to have less issues
```
npm install --global js-yaml

```

to convert a `<filename>` use ``./v23.js <filename>``

if you want to have v23 as a command in your shell, do under root permissions
```
npm link
yarn link

```
then you can use ``v23 <filename>`` everywhere
