## 示例
### 基本形式

<div class="m-example"></div>

```html
<form class="m-form">
    <div class="form_item">
        <label class="form_label">用户名<span class="form_required">&#42;</span>：</label>
        <span class="form_field">
            <input class="u-input">
            <span class="u-tip">4~12个字符，包括字母、数字、下划线</span>
        </span>
    </div>
    <div class="form_item">
        <label class="form_label">设置密码<span class="form_required">&#42;</span>：</label>
        <span class="form_field"><input class="u-input" type="password"></span>
    </div>
    <div class="form_item">
        <label class="form_label">确认密码<span class="form_required">&#42;</span>：</label>
        <span class="form_field"><input class="u-input" type="password"></span>
    </div>
    <div class="form_item">
        <label class="form_label">验证码<span class="form_required">&#42;</span>：</label>
        <span class="form_field">
            <input class="u-input">
            <img src="../img/verifyCode.jpg">
            <a>换一张</a>
        </span>
    </div>
    <div class="form_item">
        <label class="form_field"><input type="checkbox"> 同意“服务条款”和“隐私权保护和个人信息利用政策”</label>
    </div>
    <div class="form_item">
        <span class="form_field"><button class="u-btn u-btn-primary">立即注册</button></span>
    </div>
</form>
```


### 分组

<div class="m-example"></div>

```html
<form class="m-form">
    <fieldset>
        <legend>基本信息</legend>
        <div class="form_item">
            <label class="form_label">姓名<span class="form_required">&#42;</span>：</label>
            <span class="form_field"><input class="u-input"></span>
        </div>
        <div class="form_item">
            <label class="form_label">性别<span class="form_required">&#42;</span>：</label>
            <span class="form_field">
                <span class="u-unitgroup">
                    <label><input type="radio" name="gender"> 男</label>
                    <label><input type="radio" name="gender"> 女</label>
                </span>
            </span>
        </div>
        <div class="form_item">
            <label class="form_label">出生日期：</label>
            <span class="form_field"><input class="u-input"></span>
        </div>
        <div class="form_item">
            <label class="form_label">身份证号码<span class="form_required">&#42;</span>：</label>
            <span class="form_field"><input class="u-input"></span>
        </div>
    </fieldset>
    <fieldset>
        <legend>联系方式</legend>
        <div class="form_item">
            <label class="form_label">手机号码<span class="form_required">&#42;</span>：</label>
            <span class="form_field"><input class="u-input"></span>
        </div>
        <div class="form_item">
            <label class="form_label">易信：</label>
            <span class="form_field"><input class="u-input"></span>
        </div>
        <div class="form_item">
            <label class="form_label">常用邮箱：</label>
            <span class="form_field"><input class="u-input"></span>
        </div>
    </fieldset>
    <fieldset>
        <legend>教育背景</legend>
        <div class="form_item">
            <label class="form_label">最高学历<span class="form_required">&#42;</span>：</label>
            <span class="form_field">
                <select class="u-select">
                    <option>请选择</option>
                    <option>博士</option>
                    <option>硕士</option>
                    <option>本科</option>
                    <option>大专</option>
                </select>
            </span>
        </div>
        <div class="form_item">
            <label class="form_label">毕业院校<span class="form_required">&#42;</span>：</label>
            <span class="form_field"><input class="u-input"></span>
        </div>
        <div class="form_item">
            <label class="form_label">专业<span class="form_required">&#42;</span>：</label>
            <span class="form_field"><input class="u-input"></span>
        </div>
    </fieldset>
</form>
```

### inline

<div class="m-example"></div>

```html
<form class="m-form m-form-inline">
    <div class="form_item">
        <label class="form_label">年级：</label>
        <span class="form_field">
            <select class="u-select">
                <option>三年级</option>
                <option>四年级</option>
                <option>五年级</option>
                <option>六年级</option>
            </select>
        </span>
    </div>
    <div class="form_item">
        <label class="form_label">科目：</label>
        <span class="form_field">
            <select class="u-select">
                <option>数学</option>
                <option>语文</option>
                <option>英语</option>
                <option>物理</option>
                <option>化学</option>
            </select>
        </span>
    </div>
        <div class="form_item">
            <label class="form_label">分数：</label>
            <span class="form_field"><input class="u-input"></span>
        </div>
</form>
```
