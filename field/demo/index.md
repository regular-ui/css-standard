## 示例
### 基本形式

对于`<input>`、`<select>`和`<textarea>`三个表单控件，可以使用`.u-input`、`.u-select`和`.u-textarea`来美化。

<div class="m-example"></div>

```html
<input class="u-input" placeholder="请输入">
<select class="u-select">
    <option>请选择</option>
    <option>选项1</option>
    <option>选项2</option>
    <option>选项3</option>
</select>
<textarea class="u-textarea">这是一段文字。</textarea>
```

### 尺寸扩展

<div class="m-example"></div>

```html
<input class="u-input u-input-sm" value="Small">
<input class="u-input" value="Normal">
<input class="u-input u-input-lg" value="Large">

<p></p>

<select class="u-select u-select-sm">
    <option>Small</option>
    <option>选项1</option>
    <option>选项2</option>
    <option>选项3</option>
</select>
<select class="u-select">
    <option>Normal</option>
    <option>选项1</option>
    <option>选项2</option>
    <option>选项3</option>
</select>
<select class="u-select u-select-lg">
    <option>Large</option>
    <option>选项1</option>
    <option>选项2</option>
    <option>选项3</option>
</select>
```

### 宽度扩展

<div class="m-example"></div>

```html
<input class="u-input u-input-smw" value="Small Width">
<input class="u-input" value="Normal Width">
<input class="u-input u-input-lgw" value="Large Width">
```

### 颜色扩展

<div class="m-example"></div>

```html
<input class="u-input u-input-success" value="Success" placeholder="请输入">
<input class="u-input u-input-warning" value="Warning" placeholder="请输入">
<input class="u-input u-input-error" value="Error" placeholder="请输入">
```

### 禁用

<div class="m-example"></div>

```html
<input class="u-input" value="Disabled" disabled>
<select class="u-select" disabled>
    <option>Disabled</option>
    <option>选项1</option>
    <option>选项2</option>
    <option>选项3</option>
</select>
<textarea class="u-textarea" disabled>Disabled</textarea>
```

### 白板

添加`.u-*-blank`类可以使表单控件的样式特别简化。

<div class="m-example"></div>

```html
<input class="u-input u-input-blank" value="Blank">
<select class="u-select u-select-blank">
    <option>Blank</option>
    <option>选项1</option>
    <option>选项2</option>
    <option>选项3</option>
</select>
<textarea class="u-textarea u-textarea-blank">Blank</textarea>
```
