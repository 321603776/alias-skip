# vue-alias-skip

> vs code的vue项目插件，@别名路径一键跳转，支持js文件和vue文件

## 使用方法

鼠标移动到路径上，按住`ctrl`并单击就会跳转

## 配置项
> 配置项可以写入`settings.json`中，来扩展插件的能力

- 路径映射，`/`表示项目根目录，示例
```
    "alias-skip.mappings": {
        "@":"/src"  // 默认只有`@`映射，映射到`/src`，你可以添加更多映射
        // ...更多映射关系
    }
```

- 可缺省后缀名的文件列表，以下文件不需要写后缀名
```
    "alias-skip.allowedsuffix": ["js","vue","jsx","ts"]  // 默认有这四项
```

- 判断项目根目录的依据，默认为package.json，即存在该文件的目录为项目根目录

```
    "alias-skip.rootpath": "package.json"
```

## 效果图
![效果图](https://doc.lihuiwang.net/img/xiaoguotu.gif)