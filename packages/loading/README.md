## Loading 加载

### 使用指南

在 index.json 中引入组件
```json
"usingComponents": {
  "van-loading": "path/to/vant-weapp/dist/loading/index"
}
```

### 代码演示

#### Circular

```html
<van-loading />
<van-loading color="#fff" />
```

#### Spinner

```html
<van-loading type="spinner" />
<van-loading type="spinner" color="#fff" />
```

### API

| 参数 | 说明 | 类型 | 默认值 |
|-----------|-----------|-----------|-------------|
| color | 颜色 | `String` | `#c9c9c9` |
| type | 类型，可选值为 `spinner` | `String` | `circular` |
| size | 大小 | `String` | `30px` |

### 外部样式类

| 类名 | 说明 |
|-----------|-----------|
| custom-class | 根节点样式类 |

### 更新日志

| 版本 | 类型 | 内容 |
|-----------|-----------|-----------|
| 0.0.1 | feature | 新增组件 |
