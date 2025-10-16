
# 对象不支持“XXX”属性或方法

----

| Language | Message                                                                             |
|----------|-------------------------------------------------------------------------------------|
| 简体中文 | 对象不支持“XXX”属性或方法                                                         |
|          | 对象不支持“XXX”属性或方法                                                         |
| 繁体中文 | 物件沒有支援這個屬性或方法 'XXX'                                                    |
| 英文     | Object doesn't support property or method 'XXX'                                     |
|          | Uncaught TypeError: Cannote read property 'XXX' of null                             |
| 韩文     | 개체가 'XXX' 속성이나 메서드를 지원하지 않습니다.                                   |
| 日文     | オブジェクトは 'XXX' プロパティまたはメソッドをサポートしていません。               |
| 匈牙利文 | Az objektum nem támogatja a következő tulajdonságot vagy metódust: 'XXX'         |
| 西班牙文 | El objeto no acepta la propiedad o el método 'XXX'                                 |
| 法文     | L’objet ne gère pas la propriété ou la méthode « XXX »                         |
| 意大利文 | L'oggetto non supporta la proprietà o il metodo 'XXX'                              |
| 土耳其文 | Nesne, 'XXX' özelliğini veya yöntemini desteklemez                                  |
| 波兰文   | O objeto não oferece suporte à propriedade ou método 'XXX'                        |
| 德文     | Das Objekt unterstützt die Eigenschaft oder Methode "XXX" nicht                    |
| 荷兰文   | De eigenschap of methode XXX wordt niet ondersteund door dit object                 |
| 俄文     | Объект не поддерживает свойство или метод "XXX" |


## 案例

| 异常字段 | 值                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                         |
|----------|--------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|
| Message  | プロパティ 'noded' の値を取得できません: オブジェクトは Null または未定義です。                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                            |
| URL      | https://auth.alipay.com/login/index.htm]                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                   |
| File     | [https://assets.alipay.com/??...,static/ar/arale.dom-1.1.js,...](https://assets.alipay.com/??static/ar/arale.array-1.1.js,static/ar/arale.hash-1.0.js,static/ar/arale.string-1.0.js,static/ar/arale.dom-1.1.js,static/ar/arale.event-1.1.js,static/ar/arale.uri-1.0.js,static/ar/arale.http-1.1.js,static/ar/alipay.http-1.1.js,static/ar/arale.tmpl-1.0.js,static/ar/arale.aspect-1.0.js,static/ar/arale.class-1.0.js,static/ar/aralex.base-1.1.js,static/ar/aralex.validator-1.1.js,static/ar/aralex.classicvalidator-1.1.js,static/ar/alipay.placeholder-1.0.js,static/ar/alipay.localstorage-1.0.js,authcenter/authcenter.main-1.7.js) |
| Line     | 747                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                        |

相关代码

<!-- start-line=746; -->
```javascript
this._shandlers[this._shandlers.length]=h},getParentItem:function(ele){return $($(ele).parent("."+this.itemClass))
},getExplain:function(ele){var parent=this.getParentItem(ele);return $$("."+this.notifyClass,parent)[0]||$($D.toDom('<div class="'+this.notifyClass+'"></div>')).inject(parent,"bottom")
},_supportPlaceholder:function(){var i=document.createElement("input");return"placeholder" in i
```


----

| 异常字段 | 值                                                    |
|----------|-------------------------------------------------------|
| Message  | 物件沒有支援這個屬性或方法 'msSiteModeCreateJumplist' |
| URL      | https://www.alipay.com/                               |
| File     | https://www.alipay.com/                               |
| Line     | 8                                                     |

相关代码：

```javascript
window.external.msSiteModeCreateJumplist("担保交易");
```

## 相关异常


## 参考
