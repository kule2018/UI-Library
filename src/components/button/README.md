> 常用的操作按钮。

#### 具体使用
```html
<!-- 不同尺寸 -->
<fat-button class="btn" size="mini">超小按钮</fat-button>

<!-- 插入不同图标 -->
<fat-button class="btn">
    <fat-icon name="done"/>确定
</fat-button>

<!-- 不同类型 -->
<fat-button class="btn" type="success">success</fat-button>

<!-- 禁用状态 -->
<fat-button class="btn" type="primary" disabled>primary</fat-button>
```

#### Attributes 属性

参数 | 说明 | 类型 | 可选值 | 默认值
--- | --- | --- | --- | ---
size | button尺寸类型 | String | mini, small, medium, large | medium
type | button形式类型 | String | primary, success, warning, error, text, normal | normal
disabled | 是否禁用状态	 | boolean | - | false

#### Events 事件

事件名称 | 说明 | 回调函数参数
--- | --- | --- | 
onClick | 当点击button时触发 | -