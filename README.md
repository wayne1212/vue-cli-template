# Vue Cli Template

vue-cli 3 專案模版

```script
vue create --preset wayne1212/vue-cli-template {{ PROJECT_NAME }}
```
settings.json
```script
{
  // 可以刪除
  "prettier.semi": false,
  "prettier.singleQuote": true,
  // 將預設關閉(會跟eslint衝)
  "vetur.validation.template": false,
  "vetur.validation.script": false,
  "vetur.validation.style": false,
  "editor.formatOnSave": false,
  "javascript.validate.enable": false,
  
  "editor.codeActionsOnSave": {
    "source.fixAll": true
  },
  
  //存檔的fix要搭配下面options/validate
  "eslint.autoFixOnSave": true,
  "eslint.alwaysShowStatus": true,
  "eslint.options": {
    "extensions":[".html",".js",".vue"]
  },
  "eslint.validate": [
    {"language": "html","autoFix": true},
    {"language": "javascript","autoFix": true},
    {"language": "vue","autoFix": true}
  ]
}
```
