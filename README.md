# jquery.core.upload 上传组件

jquery.core.upload  是一款轻量级上传插件,支持无刷新上传。


### 快速开始

```js
<script src="http://s1.vued.vanthink.cn/d0e218489f6c/jquery.core.upload.min.js"></script>
// AMD
define(['jquery.core.upload'],function(){

  ...
})

$(.btn).CoreUpload({
  extensions: [],
  actionToSubmitUpload: "",
  maximumSize: 1024,
  enableMaximumSize: false,
  enableButton: false,
  enableDrag: false,
  inputOfFile: 'file',
  loadingObj: '',
  uploadingFun: function() {

  }

})


```

[Angular Version](https://github.com/Vanthink-UED/angular.core.upload)
