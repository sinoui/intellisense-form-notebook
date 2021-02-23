# 字段基础说明

## 字段

通过字段来设计表单。从左侧选择一个字段拖动至中间表单设计界面，在右侧配置字段属性。

![image-20210219141750687](./images/formDesign1.png)

## 复制/删除

选中已添加的字段，可以在字段右上角对其进行复制/删除的操作。`字段属性会连同字段一起被复制。`

![image-20210219141952626](images/formDesign2.png)

## 字段属性

**字段属性是字段的基础信息，可以设置字段的标题、描述信息、格式、默认值、校验、布局等；不同类型的字段具有不同的属性，如单选按钮组字段可以设置选项属性，日期选择字段可以设置日期格式属性；

### 标题

指该字段的名称，其默认值为字段类型名称，`标题必须填写`，标题的编写有助于成员更好的识别需要填报的内容。

### 字段描述

可以输入文字，表示对该字段的解释或说明。

### 字段类型

支持互相切换字段类型的字段有：

- 单行文本、多行文本和数字支持互相切换字段类型
- 复选框组和单选按钮组支持互相切换字段类型

### 数据格式

在单行文本字段中，系统预设的数据格式，起到字段校验的作用。目前可以选择的格式包括：「无格式」、「电话号码」、「手机号」、「邮箱地址」、「身份证号」、「邮政编码」；如选择手机号，必须输入11位数字才能提交数据。

### 默认值

指用户在访问表单时，该字段的默认显示值。部分字段可设置自定义、公式、创建人、创建人部门、当天、当前时间。

- 自定义即预设好一个固定的值
- 公式具体操作方法见文档中的公式
- 创建人即为当前操作人名称
- 创建人部门即为当前操作人所在的部门名称
- 当天即为当前日期的年月日
- 当前时间即为当前时间的年月日 时分

### 前缀

指用户在访问表单时，该字段的开始位置固定显示的字符。

支持显示前缀的字段类型有：

- 单行文本
- 多行文本
- 数字

### 后缀

指用户在访问表单时，该字段的末尾位置固定显示的字符。

支持显示后缀的字段类型有：

- 单行文本
- 多行文本
- 数字

### 校验规则

指该字段的校验。部分字段可设置必填、最小长度、最大长度、只显示正整数、小数位数、限定范围。

### 布局

指该字段的布局方式。部分字段可选择的的布局方式有整行、1/2行、1/3行、1/4行、2/3行、3/4行。

### 待办标题

整个表单中只允许有一个字段被设置为`待办标题`。设置为`待办标题`的字段，在流程流转过程中，该字段的值作为已办、待办列表数据项的标题。