---
id: docs-orders
title: 合同管理
sidebar_label: 合同管理
---

### 功能说明

该模块包括如下功能：
- **[合同列表](#orders)** 委托合同列表，在委托合同列表中可以对委托合同进行编辑、打印委托合同等操作。
- **[合同登记](#orders/new)** 创建新的委托合同。
- **[合同评审](#orders/review)** 评审已提交的的委托合同。
- **[合同编辑](#orders/reeidt)** 重新编辑驳回的委托合同。
### 角色权限

| 角色 | 权限 | 说明 |
| --- | --- | --- |
| 业务受理员  | 合同列表、合同登记、合同编辑  |  / |
| 合同评审员  | 合同列表、合同评审  |  / |

<html><span id='orders'></span></html>

## 合同列表

#### 功能说明
- **[创建委托合同](#orders/NewOrder)** 受理业务委托时，录入委托合同信息。
- **[ 提交合同评审](#orders/SubmitForContractReview)** 完成委托合同登记后，提交委托合同评审。
- **[ 打印委托合同](#orders/PrintContract)** 根据自定义委托合同模板打印委托合同。
- **[打印样品标签](#orders/PrintSampleLabel)** 根据自定义样品标签模板打印委托合同下样品的样品标签。
#### 操作页面

![合同列表页面](http://datmfiles.ebookchain.org/1J45K3RHDN5LES-%E5%90%88%E5%90%8C%E7%AE%A1%E7%90%86-%E5%90%88%E5%90%8C%E5%88%97%E8%A1%A8.png  "合同列表页面")

#### 页面元素

| 页面元素 | 元素类型| 说明 | 是否必填 |
| --- | --- | --- | --- |
| 委托单编号  | 数据项目  |   | √  |
| 项目名称  | 数据项目  |   | ×  |
| 项目类型  | 数据项目  |   |  √  |
| 委托单位  | 数据项目  |   |  √  |
| 委托日期  | 数据项目  |   |  √  |
| 预计完成日期  | 数据项目  |   | ×  |
| 客户要求日期  | 数据项目  | 加急合同为必填项目  | ×  |
| 当前进度  | 数据项目  |   |  √  |
| 创建  | 操作按钮  | 创建合同  | -  |
| 操作  | 操作按钮  | 操作菜单按钮  | -  |

### 操作说明

操作路径：{工作台（2.0）}-->{合同管理}-->{合同列表}。

<html><span id='orders/NewOrder'></span></html>

  1.  **创建委托合同**  点击【创建】按钮，[录入委托合同基本信息](#orders/new)。

<html><span id='orders/SubmitForContractReview'></span></html>

  2.  **提交合同评审**  
   - **单记录操作** 点击当前委托合同右端【操作】-->【提交审核】，[执行合同评审](#orders/review)。
   - **批量操作** 选择需要提交审核的委托合同，点击【批量提交】按钮，[执行合同评审](#orders/review)。

<html><span id='orders/PrintContract'></span></html>

  3.  **打印委托合同**
   - **单记录操作** 点击当前委托合同右端【操作】-->【打印】，[执行合同打印](#orders/review)。
   - **批量操作** 选择需要提交审核的委托合同，点击【批量提交】按钮，[执行合同打印](#orders/review)。
   

<html><span id='orders/PrintSampleLabel'></span></html>

  4.  **打印样品标签**
   - **单记录操作** 点击当前委托合同右端【操作】-->【打印样品标签】，[执行样品标签打印]()。
   - **批量操作** 选择需要打印样品标签的委托合同，点击【批量打印样品标签】按钮，[执行样品标签打印]()。 
### 注意事项

<html><span id='orders/new'></span></html>

## 合同登记

实验室用户在Web端登录实验室管理系统(LES)后，手工创建委托合同。操作步骤如下表所示：
| 步骤 | 描述| 备注 |是否必须 | 
| --- | --- | --- |--- |
| 第一步     |  [创建合同](#orders/new) | |  √  |  
| 第二步     |  如果需要采样或者抽样，则[登记样品类型信息](#orders/new/SampleTypeInfo)；否则[登记送检样品信息](#orders/new/SampleInfo) ||  √   |    
| 第三步     |  [添加检测项目](#orders/new/AddTestItem) |     | √ |  
| 第四步     |  [提交合同评审](#orders/review/SubmitForContractReview)  |      | × |

<html><span id='orders/new'></span></html>

### 2.1.创建合同
#### 功能说明
- [录入委托单位基本信息](#orders/new/UnitInfo)：合同委托单位的基本信息
- [录入订单信息](#orders/new/OrderInfo)：包括委托业务、合同费用、样品类别及处理方式等信息
- [录入报告信息](#orders/new/ReportInfo)：检验报告相关信息，包括报告语言、数量、领取方式等信息
- [录入时间信息](#orders/new/TimeInfo)：委托合同相关时间信息，包括样品登记日期、客户要求完成日期等信息。
#### 操作页面

<html><span id='orders/new-page'></span></html>

![合同登记-合同基本信息页面](http://datmfiles.ebookchain.org/1J4aOz2ZMOjLES-%E5%90%88%E5%90%8C%E7%AE%A1%E7%90%86-%E5%90%88%E5%90%8C%E7%99%BB%E8%AE%B0-%E5%90%88%E5%90%8C%E5%9F%BA%E6%9C%AC%E4%BF%A1%E6%81%AF.png "合同基本信息页面")
#### 页面元素


| 页面元素 | 元素类型| 说明 | 是否必填 |
| --- | --- | --- | --- |
|      |    |     |     |
|      |    |     |     |
|      |    |     |     |
|  合同进度    |  进度状态  |  使用图形化的方式描述合同当前状态及其进展情况   |   -  |

#### 操作说明

**操作路径一：** 直接进入[创建合同](#orders/new)：{工作台（2.0）}-->{合同管理}-->{合同登记}。

**操作路径二：** 在合同列表中登记：{工作台（2.0）}-->{合同管理}-->{合同列表}-->【创建】。

操作页面，详见[合同基本信息页面](#orders/new-page)。

<html><span id='orders/new/UnitInfo'></span></html>

**1.录入委托单位基本信息**

- 录入方式一：首次录入委托单位信息，平台“客户信息”中**不存在**当前委托单位信息。此时，在编辑框中直接录入信息，点击【保存】按钮，委托单位信息保存到“合同列表”的同时保存到云端“客户信息”。
- 录入方式二：平台“客户信息”中**已存在**当前委托单位信息。操作步骤如下表所示：

| 步骤 | 描述| 备注 |是否必须 | 
| --- | --- | --- |--- |
| 第一步     |  在委托单位编辑框中录入委托单位名称的关键字  | |  √  |  
| 第二步     |  系统会自动根据关键字从“客户信息”检索符合条件的委托单位  |下拉框|  √   |    
| 第三步     |  选择委托单位信息  |     | √ |  
| 第四步     |  系统自动抓取委托单位的联系人、联系电话、联系邮箱、联系地址信息  |  也可修改这些信息   | × |  

>_注意：修改的信息同时会更新到“客户信息”_

<html><span id='orders/new/OrderInfo'></span></html>

**2.录入订单信息**
- 检测领域：不同的检测领域，需要登记的样品信息不同，[样品信息登记模板]()不同。当前版本支持食品检测和环境检测两大领域。
- 来样方式：来样方式，决定是否需要采样或抽样。
- 余样处理方式：包括<授权承检方处置>和<返回客户>，会影响样品处置方式。
>_温馨提醒：检测领域和来样方式决定登记样品信息还是登记样品类型信息_


<html><span id='orders/new/ReportInfo'></span></html>

**3.录入报告信息**

<html><span id='orders/new/TimeInfo'></span></html>

**4.录入时间信息**

**5.保存合同信息**
以上三部分信息录入完成之后，点击【保存】按钮，保存信息到云端。如果需要采样或者抽样，则[登记样品类型信息]()；否则[登记送检样品信息]()。

<html><span id='orders/new/SampleInfo'></span></html>

### 2.2.登记样品信息（无需抽样/采样）

#### 功能说明
- 交接表导入：适用于批量样品信息登记的场景。比如食品抽样、大批量上门送样。
- 手工登记：适用于零散样品信息登记的场景。
#### 操作页面

<html><span id='orders/new/SampleInfo/page'></span></html>

![合同登记-登记样品信息页面](http://datmfiles.ebookchain.org/1J8YGdpbldYLES-%E5%90%88%E5%90%8C%E7%AE%A1%E7%90%86-%E5%90%88%E5%90%8C%E7%99%BB%E8%AE%B0-%E7%99%BB%E8%AE%B0%E6%A0%B7%E5%93%81%E4%BF%A1%E6%81%AF.png "登记样品信息页面")


#### 页面元素


| 页面元素 | 元素类型| 说明 | 是否必填 |
| --- | --- | --- | --- |
|      |    |     |     |
|      |    |     |     |
|      |    |     |     |
|      |    |     |     |

#### 操作说明

样品信息是根据[动态表单](#)自动生成的。样品登记有两种方式，一种交接表导入，一种是手动录入。

- **交接表导入** 委托合同中没有样品时，只显示“交接表导入”方式，此方式可实现快速导入。用户只需要录入样品的最少必要信息，即可导入系统。以快速开展业务流程。在业务流转过程中，再及时补录详细信息。操作步骤如下表所示：

第一步 点击【模板下载】，下载[交接表的excel模板](#orders/new/SampleInfoModel) ；
<html><span id='orders/new/SampleInfoModel'></span></html>

![样品信息导入模板样式](http://datmfiles.ebookchain.org/1J9gXJMwzS8LES-%E5%90%88%E5%90%8C%E7%AE%A1%E7%90%86-%E5%90%88%E5%90%8C%E7%99%BB%E8%AE%B0-%E6%A0%B7%E5%93%81%E4%BF%A1%E6%81%AF%E5%AF%BC%E5%85%A5%E6%A8%A1%E6%9D%BF%E6%A0%B7%E5%BC%8F.png "样品信息导入模板样式")

第二步 在模板中[录入、编辑样品信息]()，保存关闭excel ；

第三步 点击选择文件，选择填写好的excel文件 ；  

第四步 点击【确认导入】即可把样品导入系统 ； 

第五步 导入后显示[系统解析后的数据](#orders/new/SampleInfo) ；
<html><span id='orders/new/SampleInfo'></span></html>

![系统解析后的样品信息数据](http://datmfiles.ebookchain.org/1J9meOCVAs2LES-%E5%90%88%E5%90%8C%E7%AE%A1%E7%90%86-%E5%90%88%E5%90%8C%E7%99%BB%E8%AE%B0-%E7%B3%BB%E7%BB%9F%E8%A7%A3%E6%9E%90%E5%90%8E%E7%9A%84%E6%A0%B7%E5%93%81%E4%BF%A1%E6%81%AF%E6%95%B0%E6%8D%AE.png "系统解析后的样品信息数据")

第六步 点击【确认】按钮后正式导入；

第七步 导入样品后，或者手动创建样品后，将出现“详情表导入”功能，

<html><span id='orders/new/SampleInfo'></span></html>

![样品信息详情表导入功能](http://datmfiles.ebookchain.org/1J9swo1gBTKLES-%E5%90%88%E5%90%8C%E7%AE%A1%E7%90%86-%E5%90%88%E5%90%8C%E7%99%BB%E8%AE%B0-%E6%A0%B7%E5%93%81%E4%BF%A1%E6%81%AF%E8%AF%A6%E6%83%85%E8%A1%A8%E5%AF%BC%E5%85%A5%E5%8A%9F%E8%83%BD.png "导入样品后，或者手动创建样品后，将出现“详情表导入”功能")

第八步 点击【下载模板】下载[样品信息详情的excel模板](#orders/new/SampleAllInfoModel)；详情表样式，根据动态表单由系统自动生成。

<html><span id='orders/new/SampleAllInfoModel'></span></html>

![样品信息详情的excel模板](http://datmfiles.ebookchain.org/1J9tMG4AtUdLES-%E5%90%88%E5%90%8C%E7%AE%A1%E7%90%86-%E5%90%88%E5%90%8C%E7%99%BB%E8%AE%B0-%E6%A0%B7%E5%93%81%E4%BF%A1%E6%81%AF%E8%AF%A6%E6%83%85%E7%9A%84excel%E6%A8%A1%E6%9D%BF.png "样品信息详情的excel模板")

 第九步 把样品详情填写完整，再次进行导入，具体步骤可参照[交接表导入](#)所示第三步到第六步。也可针对各个样品，逐个进行编辑，补充详细信息。

- **手工登记** 在[登记样品信息页面](#orders/new/SampleInfo/page)中，输入样品信息，添加样品，即可完成样品添加。


<html><span id='orders/new/SampleTypeInfo'></span></html>

### 2.3.登记样品类型信息（需要抽样/采样）
#### 功能说明
- Excel模板导入：适用于批量样品类别信息录入的场景。比如，环境采样。
- 手工登记：适用于少量样品类别信息录入的场景。
#### 操作页面

<html><span id='orders/new/SampleTypeInfo/page'></span></html>


![合同登记-登记样品类别信息页面](http://datmfiles.ebookchain.org/1J9fYeeDvkyLES-%E5%90%88%E5%90%8C%E7%AE%A1%E7%90%86-%E5%90%88%E5%90%8C%E7%99%BB%E8%AE%B0-%E5%BD%95%E5%85%A5%E6%A0%B7%E5%93%81%E7%B1%BB%E5%88%AB%E4%BF%A1%E6%81%AF.png "登记样品类别信息页面")
#### 页面元素


| 页面元素 | 元素类型| 说明 | 是否必填 |
| --- | --- | --- | --- |
|      |    |     |     |
|      |    |     |     |
|      |    |     |     |
|      |    |     |     |

#### 操作说明
样品类别信息是根据动态表单自动生成的。样品类别信息录入有两种方式，一种Excel表导入，一种是手动录入。

- **Excel模板导入** 委托合同中没有样品类别时，只显示“Excel模板导入”方式，此方式可实现快速导入。具体步骤可参照[交接表导入]()所示步骤。
- **手工登记** 在[样品类别信息录入页面](#orders/new/SampleTypeInfo/page)中，输入样品类别信息，添加样品类别信息，即可完成样品类别信息的添加。


<html><span id='orders/new/AddTestItem'></span></html>


### 2.4.添加检测项目
#### 功能说明
- **检索检测项目** 根据编辑框中提示的条件关键字，检索标准库中的检测项目。
- **添加检测项目**  选择并将标准库中的检测项目添加到当前样品或样品类型上。
- **复制检测项目** 选择并将标准库中的检测项目记录信息复制到创建检测项目编辑栏中，供用户修改。
- **创建检测项目** 新建标准库不存在的检测项目信息到标准库，同时添加到当前样品或样品类型上。

- **删除检测项目**  删除单个或全部已添加到样品或样品类型的检测项目。
#### 操作页面

<html><span id='orders/new/AddTestItem/page'></span></html>   

![合同登记-添加检测项目页面](http://datmfiles.ebookchain.org/1J9XvBphvsLLES-%E5%90%88%E5%90%8C%E7%AE%A1%E7%90%86-%E5%90%88%E5%90%8C%E7%99%BB%E8%AE%B0-%E6%B7%BB%E5%8A%A0%E6%A3%80%E6%B5%8B%E9%A1%B9%E7%9B%AE%E9%A1%B5%E9%9D%A2.png "添加检测项目页面")
#### 页面元素


| 页面元素 | 元素类型| 说明 | 是否必填 |
| --- | --- | --- | --- |
| 检测项目     |    |     |     |
| 判定依据     |    |     |     |
| 检测依据     |    |     |     |
| 技术要求     |    |     |     |
| 限量单位     |    |     |     |
| 样品分类     |    |     |     |


#### 操作说明

- **检索检测项目** 可根据样品编号、检测项目、判定依据、检测依据、技术要求、限量单位和样品分类检索。其中根据样品编号检索适用于参照已送检样品检测项目的场景。

- **添加检测项目** 添加检测项目有两种方式:

     **(1) 导航添加** 添加完样品/样品类型信息，点击【保存】，系统自动弹出[添加检测项目对话框](#orders/new/AddTestItem/page) 。  
 
    **(2) 直接添加** 在[合同样品列表]()或[合同样品类型列表]()中，点击【添加项目】，系统自动弹出[添加检测项目对话框](#orders/new/AddTestItem/page)。
 
 添加检测项目操作步骤如下表所示：

| 步骤 | 描述| 备注 |是否必须 | 
| ------ | --- | --- |--- |
| 第一步 | 检索检测检测项目    |     |  √ |  
| 第二步 | 点击需要添加检测项目记录右端的【↓】    |     |  √ |    
如果需要添加多个检测项目，则需重复上表步骤。 

- **复制检测项目** 点击需要复制的检测项目记录右端的【↑】 。

- **创建检测项目** 操作步骤如下表所示：

| 步骤 | 描述| 备注 |是否必须 | 
| ------ | --- | --- |--- |
| 第一步 | [复制检测项目]()或者手工录入检测项目信息    |     |  √ |  
| 第二步 | 点击【创建】    |     |  √ | 
>_注意：创建检测项目会在标准库中自动添加一条记录。_

- **删除检测项目**
删除样品或样品类型的检测项目有两种方式：

    **(1) 单记录删除** 点击需要添加检测项目记录右端的【↑】。

    **(2) 全部删除** 点击标准库与检测项目之间的【↑↑】。

>_温馨提醒：删除样品或样品类型的检测项目不会删除标准库中的检测项目。_



<html><span id='orders/review/SubmitForContractReview'></span></html>


### 2.5.提交合同评审 

操作路径：{工作台（2.0）}-->{合同管理}-->{合同列表}。

提交合同评审有两种方式：

   - **单记录操作** 点击当前委托合同右端【操作】-->【提交审核】，[执行合同评审](#orders/review)。
   - **批量操作** 选择需要提交审核的委托合同，点击【批量提交】按钮，[执行合同评审](#orders/review)。

<html><span id='orders/review'></span></html>

## 合同评审

#### 功能说明
- **审核通过** 若没有问题，则审核通过
- **驳回** 如有问题，则驳回给提交人重新[编辑合同](#orders/reeidt)
#### 操作页面

<html><span id='orders/review/Page'></span></html>

![合同评审页面](http://datmfiles.ebookchain.org/1JavaecALLsLES-%E5%90%88%E5%90%8C%E7%AE%A1%E7%90%86-%E5%90%88%E5%90%8C%E5%AE%A1%E6%A0%B8%E9%A1%B5%E9%9D%A2.png "合同审核页面")
#### 页面元素


| 页面元素 | 元素类型| 说明 | 是否必填 |
| --- | --- | --- | --- |
|      |    |     |     |
|      |    |     |     |
|      |    |     |     |
|      |    |     |     |

#### 操作说明

操作路径：{工作台（2.0）}-->{合同管理}-->{合同列表}→【合同评审】，弹出[合同评审页面](#orders/review/Page)。若没有问题，则点击【审核通过】按钮**通过审核**； 如有问题，则填写驳回原因后，点击【驳回】，**驳回**给提交人重新[编辑合同](#orders/reeidt)。

<html><span id='orders/reeidt'></span></html>

## 编辑合同

#### 功能说明

- **编辑合同基本信息** 如果有问题需要重新编辑。
- **编辑样品类型信息** 如果有问题需要重新编辑。
- **编辑送检样品信息** 如果有问题需要重新编辑。
- **编辑检测项目** 如果有问题需要重新编辑。
- **提交合同评审** 重新编辑后需要重新提交评审。

#### 操作页面

<html><span id='orders/reeidt/page'></span></html>

![编辑合同页面](http://datmfiles.ebookchain.org/1JaS5JnS8GtLES-%E5%90%88%E5%90%8C%E7%AE%A1%E7%90%86-%E7%BC%96%E8%BE%91%E5%90%88%E5%90%8C%E9%A1%B5%E9%9D%A2.png "编辑合同页面")
#### 操作说明

操作路径：{工作台（2.0）}→{合同管理}→{编辑合同}→【操作】→【编辑】，弹出[编辑合同页面](#orders/reeidt/page)。打开页面后，上部是委托合同信息，点击右上角的“+”或“-”图标按钮，可以展开或收起委托合同信息。

- **编辑合同基本信息** 参照合同登记中的[创建合同](#orders/new) 
- **编辑样品类型信息** 

    **1)编辑** 点击[样品类型列表]()中的【编辑】，弹出[样品类别信息录入页面](#orders/new/SampleTypeInfo/page),详细操作参照合同登记中的[登记样品类型信息](#orders/new/SampleTypeInfo)。
    
    **2)复制** 

    **3)删除** 点击[样品类型列表]()中的【删除】，弹出[样品类别删除确认对话框](),点击【确定】。


- **编辑送检样品信息**

    **1)编辑** 点击[样品列表]()中的【编辑】，弹出[登记样品信息页面](#orders/new/SampleInfo/page)参照合同登记中的[登记送检样品信息](#orders/new/SampleInfo) 
    
    **2)复制** 点击[样品列表]()中的【复制】，弹出[样品复制页面]()。
    
    **(1)增加** 点击【增加样品信息】可增加复制样品信息，编辑需要修改的信息后点击【完成复制】。
    
    **(2)删除** 点击【删除样品信息】可删除最后一个样品信息
  ![样品类型复制页面](http://datmfiles.ebookchain.org/1Jb3vw7zJZkLES-%E5%90%88%E5%90%8C%E7%AE%A1%E7%90%86-%E7%BC%96%E8%BE%91%E5%90%88%E5%90%8C-%E5%A4%8D%E5%88%B6%E6%A0%B7%E5%93%81.png "样品类型复制页面")  
    
    **3)删除** 点击[样品列表]()中的【删除】，弹出[样品类别删除确认对话框](),点击【确定】。



- **编辑检测项目**

    **1)编辑** 点击[检测项目列表]()中的【添加项目】，弹出参照合同登记中的[添加检测项目](#orders/new/AddTestItem)
    
    **2)删除** 在[检测项目列表]()中点击需要删除的检测项目记录右端的【删除】，弹出[样品删除确认对话框](),点击【确定】。
- **提交合同评审** 参照合同登记中的[提交合同评审](#orders/review/SubmitForContractReview)
