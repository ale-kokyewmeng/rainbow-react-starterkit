## Create Your React App and install Rainbow Web SDK 1.68-beta.1
This sample is using Rainbow Web SDK 1.68-beta.1 which is presented as an ES module. The official 1.68 release will be available very soon.

```
npx create-react-app rainbow-react-starterkit
cd rainbow-react-starterkit
npm i -s rainbow-web-sdk@1.68.0-beta.1
cd public
cp ../node_modules/rainbow-web-sdk/dist-legacy/vendors-sdk.min.js .
```

## Add dependencies to index.html
```html
<head>
...
    <script src="//code.jquery.com/jquery-2.1.3.min.js"></script>
    <script src="//cdn.jsdelivr.net/momentjs/2.15.1/moment-with-locales.min.js"></script>
    <script src="//cdnjs.cloudflare.com/ajax/libs/angular.js/1.7.5/angular.min.js"></script>
    <script src="./vendors-sdk.min.js"></script>
</head>
```
