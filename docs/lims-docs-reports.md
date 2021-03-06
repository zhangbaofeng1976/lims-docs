---
id: docs-reports
title: 报告管理
sidebar_label: 报告管理
---

### 功能说明

该模块包括如下功能：
- **报告列表** 检验报告与样品一一对应

### 角色权限

| 角色 | 权限 | 说明 |
| --- | --- | --- |
| 报告编辑人  | 报告列表、编辑报告  |  / |
| 报告审核人  | 报告列表、审核报告  |  / |
| 授权签字人  | 报告列表、签发报告  |  / |
| 报告打印人员  | 报告列表、打印报告  |  / |



## 1.报告列表

#### 功能说明

- **生成报告** 生成检测报告
- **编辑报告** 编辑检测报告，支持电子签名、电子签章（包括资质章、公章）
- **审核报告** 对检验报告进行审核，支持电子签名

- **签发报告** 签发检验报告出厂签发，支持电子签名

- **打印报告** 打印检验报告，支持批量打印


#### 操作页面

![报告列表页面]( "报告列表页面")

#### 页面元素

| 页面元素 | 元素类型| 说明 | 是否必填 |
| --- | --- | --- | --- |
|   |   |   | √  |
|   |   |   | √  |
|   |   |   | √  |


### 操作说明

操作路径：{工作台（2.0）}-->{报告管理}-->{报告列表}。

**1)生成报告** 

**(1)生成单个样品报告** 点击待生成检测报告样品记录右端的[检测报告]，弹出[生成检测报告对话框]()，执行[生成报告操作]()。

**(2)批量生成多个样品报告** 操作步骤如下：

**第一步** 选择需要生成报告的样品

**第二步** 点击【检测报告】，弹出[生成检测报告对话框]()，执行[生成报告操作]()。

**2)编辑报告** 点击待编辑检测报告记录右端的【操作】-->【编辑报告】，弹出[编辑检测报告对话框]()，执行[编辑报告操作]()。


**3)审核报告** 点击待编辑检测报告记录右端的【操作】-->【审核报告】，弹出[审核检测报告对话框]()，执行[审核报告操作]()。

**4)签发报告** 点击待签发检测报告记录右端的【操作】-->【签发报告】，弹出[签发检测报告对话框]()，执行[签发报告操作]()。

**5)查看报告** 点击待打印检测报告记录右端的【操作】-->【查看报告】，弹出[查看检测报告页面]()。
![报告列表-查看报告信息页面](http://datmfiles.ebookchain.org/1JmKIDViU65LES-%E6%A3%80%E6%B5%8B%E6%8A%A5%E5%91%8A%E7%AE%A1%E7%90%86-%E6%9F%A5%E7%9C%8B%E6%89%93%E5%8D%B0%E6%A3%80%E6%B5%8B%E6%8A%A5%E5%91%8A%E6%93%8D%E4%BD%9C%E9%A1%B5%E9%9D%A2.png "查看报告信息页面")

**6)打印报告** 在[查看检测报告页面]()中点击【文件】-->【打印】，弹出[打印检测报告对话框]()，执行[打印报告操作]()。

### 注意事项
## 2.生成报告


#### 操作页面

![报告列表-生成报告操作页面](http://datmfiles.ebookchain.org/1JmqDZeifqoLES-%E6%A3%80%E6%B5%8B%E6%8A%A5%E5%91%8A%E7%AE%A1%E7%90%86-%E7%94%9F%E6%88%90%E6%A3%80%E6%B5%8B%E6%8A%A5%E5%91%8A%E6%93%8D%E4%BD%9C%E9%A1%B5%E9%9D%A2.png "生成报告操作页面")
#### 页面元素


| 页面元素 | 元素类型| 说明 | 是否必填 |
| --- | --- | --- | --- |
|      |    |     |     |
|      |    |     |     |
|      |    |     |     |
|      |    |     |     |

#### 操作说明

操作步骤如下：


| 步骤 | 描述| 备注 |是否必须 | 
| ------ | --- | --- |--- |
| 第一步 |  勾选并确认需要生成检测报告的样品  |     |  √ |  
| 第二步 | 选择报告模板    |     |  √ |    
| 第三步 | 点击【生成报告】    |     | √  |  


## 3.编辑报告


#### 操作页面

![报告列表-编辑报告信息页面](http://datmfiles.ebookchain.org/1JmwjfD9QgpLES-%E6%A3%80%E6%B5%8B%E6%8A%A5%E5%91%8A%E7%AE%A1%E7%90%86-%E7%BC%96%E8%BE%91%E6%A3%80%E6%B5%8B%E6%8A%A5%E5%91%8A%E6%93%8D%E4%BD%9C%E9%A1%B5%E9%9D%A2.png "编辑报告信息页面")
#### 页面元素


| 页面元素 | 元素类型| 说明 | 是否必填 |
| --- | --- | --- | --- |
|      |    |     |     |
|      |    |     |     |
|      |    |     |     |
|      |    |     |     |

#### 操作说明

操作步骤如下：

| 步骤 | 描述| 备注 |是否必须 | 
| ------ | --- | --- |--- |
| 第一步 | 选择报告模板，点击【更换模板】    |     | × |  
| 第二步 | [编辑报告信息]()   |     |  √ |    
| 第三步 | 选择报告审核人   |     | √  |   
| 第四步 | 点击【编辑人签字】，弹出录入密码对话框，录入密码，点击【确定】    |     | √  | 

>***注意：编辑人签字需要上传个人签章***
## 4.审核报告

#### 功能说明

- **审核通过** 没有问题，审核通过
- **审核驳回** 填写有问题，需要审核驳回到{报告编辑}，再由报告编辑人修改后重新提交审核。

#### 操作页面

![报告列表-审核报告信息页面](http://datmfiles.ebookchain.org/1JmFth5QlsfLES-%E6%A3%80%E6%B5%8B%E6%8A%A5%E5%91%8A%E7%AE%A1%E7%90%86-%E5%AE%A1%E6%A0%B8%E6%A3%80%E6%B5%8B%E6%8A%A5%E5%91%8A%E6%93%8D%E4%BD%9C%E9%A1%B5%E9%9D%A2.png "审核报告信息页面")
#### 页面元素


| 页面元素 | 元素类型| 说明 | 是否必填 |
| --- | --- | --- | --- |
|      |    |     |     |
|      |    |     |     |
|      |    |     |     |
|      |    |     |     |

#### 操作说明

 **1）审核通过** 操作步骤如下：

| 步骤 | 描述| 备注 |是否必须 | 
| ------ | --- | --- |--- |
| 第一步 | 选择报告签发人    |     |  √ |  
| 第二步 | 点击【审核人签字】，弹出录入密码对话框，录入密码 |     | √  |   
| 第三步 | 点击【确定】返回{检测报告列表}  |     | √  |  

 **2）审核驳回** 操作步骤如下：

| 步骤 | 描述| 备注 |是否必须 | 
| ------ | --- | --- |--- |
| 第一步 | 点击【驳回】，弹出驳回原因录入对话框，输入驳回原因   |     |  √ |  
| 第二步 | 点击【确定】{返回检测列表} |     |  √ |    


## 5.签发报告

#### 功能说明

- **签发通过** 没有问题，审核通过
- **签发驳回** 有问题，需要驳回到{报告审核}，再由{报告审核}驳回到{报告编辑}，再由报告编辑人修改后重新提交审核。

#### 操作页面

![报告列表-签发报告信息页面](http://datmfiles.ebookchain.org/1JmIyrhqYdpLES-%E6%A3%80%E6%B5%8B%E6%8A%A5%E5%91%8A%E7%AE%A1%E7%90%86-%E7%AD%BE%E5%8F%91%E6%A3%80%E6%B5%8B%E6%8A%A5%E5%91%8A%E6%93%8D%E4%BD%9C%E9%A1%B5%E9%9D%A2.png "签发报告信息页面")
#### 页面元素


| 页面元素 | 元素类型| 说明 | 是否必填 |
| --- | --- | --- | --- |
|      |    |     |     |
|      |    |     |     |
|      |    |     |     |
|      |    |     |     |

#### 操作说明

 **1）签发通过** 操作步骤如下：

| 步骤 | 描述| 备注 |是否必须 | 
| ------ | --- | --- |--- |
| 第一步 | 点击【授权人签字】，弹出录入密码对话框，录入密码    |     |  √ |  
| 第二步 | 点击【确定】返回{检测报告列表}    |     |  √ |    

 **2）签发驳回** 操作步骤参照[审核驳回]()  


## 6.打印报告

#### 功能说明

- **切换打印类型** 通过选择打印机类型（PDF虚拟打印机或实物打印机）实现。
- **打印PDF文件** 打印为PDF格式电子文件。
- **打印纸质报告** 打印为纸质报告

#### 操作页面

![报告列表-打印报告信息页面](http://datmfiles.ebookchain.org/1JmOqcBOm1JLES-%E6%A3%80%E6%B5%8B%E6%8A%A5%E5%91%8A%E7%AE%A1%E7%90%86-%E6%89%93%E5%8D%B0%E6%A3%80%E6%B5%8B%E6%8A%A5%E5%91%8A%E6%93%8D%E4%BD%9C%E9%A1%B5%E9%9D%A2.png "打印报告信息页面")
#### 页面元素


| 页面元素 | 元素类型| 说明 | 是否必填 |
| --- | --- | --- | --- |
|      |    |     |     |
|      |    |     |     |
|      |    |     |     |
|      |    |     |     |

#### 操作说明

**1)切换打印类型** 操作步骤如下：

| 步骤 | 描述| 备注 |是否必须 | 
| ------ | --- | --- |--- |
| 第一步 | 点击【更改...】,弹出[选择打印机对话框]()。    |     |  √ |  
| 第二步 | 点击需要的打印机，返回到[打印报告信息页面]()。   |     |  √ | 

**2)打印PDF文件** 操作步骤如下：

| 步骤 | 描述| 备注 |是否必须 | 
| ------ | --- | --- |--- |
| 第一步 | [切换打印类型]() ,选择PDF虚拟打印机   |     |  × |  
| 第二步 | 点击【保存】返回{检测报告列表}    |     |  √ | 

**3)打印纸质报告** 操作步骤如下：

| 步骤 | 描述| 备注 |是否必须 | 
| ------ | --- | --- |--- |
| 第一步 | [切换打印类型]() ,选择纸质打印机   |     |  × |  
| 第二步 | 点击【打印】返回{检测报告列表}    |     |  √ | 

## 7.常见问题

  1.超级用户在报告编辑环节为什么不能选择报告审核人？
  
  **答：** 
  
  原因分析：报告审核人与报告编辑人不能是同一个人，需要选择另外有报告审核权限的人。
  
  解决方案：与系统管理人员联系，将报告审核权限授权给有资质的人。