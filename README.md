# mini-custom-by-jayne
一些用来测试的微信小程序自定义控件

``$ npm install mini-custom-by-jayne``

``$ npm install``

``$ npm run build``

###使用

####card

index.json
```
  "usingComponents": {
    "card": "mini-custom-by-jayne/component/card"
  }
```
index.wxml

```angularjs
<card title="这是一个自定义组件" description="这是一个自定义组件。这是一个自定义组件。这是一个自定义组件。"></card>
```
####custom button
index.json
```
  "usingComponents": {
    "card": "mini-custom-by-jayne/component/customButton"
  }
```
index.wxml
```angularjs
 <custom-button buttonName="这是一个按钮"></custom-button>
```
