# 设置节点负责人

> 节点负责人为在此节点接收数据并进行处理的人。

`选中节点` ==> `基础属性` ==> `负责人`，点击`设置负责人`按钮，可选范围有`组织架构`、`角色`、`成员`。（**需要注意的是：同一节点负责人只能选择一种类型，不能三种类型混选。**）

![设置节点负责人](./images/add-node-director.png)

## 组织架构

当我们在设置节点负责人选择“组织架构”时，则选中的组织机构下的所有人都会成为此节点负责人。（**需要注意的是：组织机构下的所有人指的是直属人员，不包括其子部门下的人员。**）

![节点负责人_部门](./images/add-node-director_dept.png)

## 角色

当我们在设置节点负责人选择“角色”时，则拥有此角色的所有人都会成为此节点负责人。

![节点负责人_角色](./images/add-node-director_role.png)

如图中所示，演示部门下所有拥有“处长”角色的人员都会成为此节点的负责人。如果想要严格限制范围，可以在选择“角色”后，设置“业务角色负责人所在部门范围”。

![节点负责人_角色_部门范围](./images/add-node-director_role_dept.png)

上图配置完成后，“处长审批”节点的负责人范围就会限定为`公文处下拥有处长角色的人员`。

## 成员

同上面`组织架构`和`角色`相同，当我们选定成员以后，被选定的成员都拥有此节点的操作权限。

## 动态设置节点负责人

除了直接设置节点负责人外，我们还可以基于`表单字段负责人`属性动态设置节点负责人。此时，节点负责人来源于表单中的用户选择字段。

![动态设置节点负责人](./images/add-node-director_dynamic.png)

如图中设置，表单中部门领导字段中所选的人员会成为此节点的负责人。

## 设置规则

- 如果要用`动态设置节点负责人`的特性，则必须首先设置节点负责人，否则流程提交过程中会提示`找不到下一节点负责人`
- 在流程流转过程中，只有表单字段负责人范围符合节点负责人范围且表单负责人字段有值时，数据才会发送给表单字段负责人。若表单字段负责人没值，发送时，需要手松选择参与者。
