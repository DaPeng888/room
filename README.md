# room
基于javaEE+jqueryEasyUi+eclipseLInk(课程设计客房管理信息系统)
----
### 一.初始阶段
#### 1.可行性分析
 - 建立商业案例并确定项目的边界
 - 成本估计
 - 风险分析
 - 识别所有与系统交互的外部实体
#### 2.需求识别
 - 业务需求
 - 用户需求
 - 功能需求
 - 非功能需求
#### 3.需求获取
 - 用户访谈
 - 原型法
 - 情景串联
 #### 4.需求验证
 - 需求评审
 - 需求确认
#### 5.启动管理
 - 分工计划书
 - 风险控制计划书
 - 甘特图计划书
 - 需求管理
 #### 6.里程碑
 - 生命周期目标(Lifecycle Objective)里程碑：生命周期目标里程碑评价项目基本的生存能力。
### 二.细化阶段
#### 1.需求分析
* 用例图（功能需求）
![usercase]
* 稳定，安全，响应快（非功能需求）
* 使用java+mysql(设计约束)
#### 2.概要设计
* 画类图（模块划分、建立模块的层次结构及调用关系、确定模块间的接口及人机界面）
![classtu]
* 数据结构设计（数据特征的描述、确定数据的结构特性，数据库设计）
* E-R图
* 物理模型设计
![er]
![pdm]
#### 3.详细设计
* 顺序图
![sx]
* 状态图
* 活动图
![zt]
![a]
![b]
#### 4.规划管理
 - 需求规格说明书
 - 概要设计说明书
 - 详细设计说明书
#### 5.里程碑
 - 生命周期结构(Lifecycle Architecture)里程碑。生命周期结构里程碑为系统的结构建立了管理基准并使项目小组能够在构建阶段中进行衡量。此刻，要检验详细的系统目标和范围、结构的选择以及主要风险的解决方案。
### 三. 构造阶段
* MVC设计模式下，使java的面向的对象编程，模型，视图，业务逻辑
* 里程碑:初始功能(Initial Operational)里程碑。初始功能里程碑决定了产品是否可以在测试环境中进行部署。此刻，要确定软件、环境、用户是否可以开始系统的运作。此时的产品版本也常被称为“beta”版。
### 四.交付阶段
#### 1.测试
* 单元测试
* 集成测试
* 系统测试
* 功能测试
* 性能测试
#### 2.维护
* 软件维护
#### 3.里程碑
 - 产品发布(Product Release)里程碑。此时，要确定目标是否实现，是否应该开始另一个开发周期。在一些情况下这个里程碑可能与下一个周期的初始阶段的结束重合。

----
`以上基于软件工程的统一软件工程(RUP)模型`

[usercase]:/images/usercase.png "用例图"
[classtu]:/images/classtu.png "类图"
[er]:/images/er.png "E-R图"
[pdm]:/images/pdm.png "物理模型"
[sx]:/images/sx.png "预定房间顺序图"
[a]:/images/a.png "前台操作员的活动图"
[b]:/images/b.png "系统管理员的活动图"
[zt]:/images/zt.png "顾客会员变化状态图"
