# 流程操作

![](/articles/mdm/2-/images/image150.png)

## 登录

访问主数据管理系统http://{IP:PORT}/portal/页，进入登录界面，如下图，用“集团管理员”身份登录系统！

![](/articles/mdm/2-/images/image151.png)

## 实体建模

一、打开主数据的“实体建模”功能节点，建立主数据需要的存储的数据表

![](/articles/mdm/2-/images/image152.png)

二、建立一级分类，分类编码不可以使用中文，录入分类名称，选择上级分类（不选则作为一级），排序字段是分类的显示位置，可以根据实际想要显示的位置进行设置。

![](/articles/mdm/2-/images/image153.png)

三、建立实体，新增实体有两种方式，新增和导入，这里使用新增，默认新增的实体已经预置了3个字段-名称、编码、描述，根据实际情况增加字段。

![](/articles/mdm/2-/images/image154.png)

![](/articles/mdm/2-/images/image155.png)

四、选择新增的实体，通过按钮“生成存储&模型”建立实体映射,在弹出框内选择要生成的数据，主数据平台将自动建立存储表。

![](/articles/mdm/2-/images/image156.png)

![](/articles/mdm/2-/images/image157.png)

![](/articles/mdm/2-/images/image158.png)

五、在主数据的存储模型节点可以查看是否建立成功，选择新建的实体，可以修改实体对象属性。

![](/articles/mdm/2-/images/image159.png)

## 主数据编码

进入主数据编码节点，设置主数据编码规则，选择演示分类的演示实体，点击修改，弹出修改对话框，填写规则的编码、规则名称、这里定义时间规则，增加元素类型（使用流水号的方式），完成后进行保存。

![](/articles/mdm/2-/images/image160.png)

![](/articles/mdm/2-/images/image161.png)

## 主数据定义

进入主数据定义节点，新增主数据定义

![](/articles/mdm/2-/images/image162 .png)

一、新增分类，录入目录编码、目录名称，选择上级目录及设置排序。

![](/articles/mdm/2-/images/image163.png)

二、在新增分类下新增主数据，点击新增主数据，在弹出对话框中录入主主数据编码、名称，选择主表为新增的“演示实体”，保存。

![](/articles/mdm/2-/images/image164.png)

![](/articles/mdm/2-/images/image165.png)

三、新增完成后，可以在本界面中对主数据进行进一步的维护。

![](/articles/mdm/2-/images/image166.png)

## 主数据维护

进入主数据维护节点，选择刚才建好的“演示主数据”，在这个节点中可以进行数据的新增、修改、删除等功能。维护的数据将进行存贮。

![](/articles/mdm/2-/images/image167.png)

至此，主数据新增处理完成。


