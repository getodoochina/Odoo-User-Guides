# 开票流程概述

基于你的业务场景以及你所使用的模块, 在Odoo中有几种不同的方式去自动触发客户发票。通常, 系统创建草稿发票\(发票信息从其他单据例如销售订单或者合同\)并且会计只需要确认草稿发票并且批量的发送即可\(快递或者电子邮件\)

基于你的业务场景, 可以选择以下方式的其中之一创建草稿发票 :

## 销售

### 销售订单‣发票

在大多数公司里面, 销售人员创建报价单, 并且确认后转换为销售就订单。然后基于销售订单创建草稿发票。可以选择如下集中方式 :

* 手工发票 :利用出售才能触发发票草案上的一个按钮

* 发票交付之前 :触发交付订单之前发票的完整的订单

* 根据送货单发票 :参见下一节

发货之前开票通常用于电商应用中, 通常都是客户先付钱之后我们发货给他们\(预付\)。

对于大多数其他用途的情况下, 建议手动发票。它可以让销售人员引发与期权需求的发票 :发票整个订单, 发票百分比（前进）, 发票的某些行, 发票固定的前进。

该过程适用与服务类型的产品和实物类产品

### 销售订单\(Sales Order\) ‣ 提货单\(Delivery Order\) ‣ 发票\(Invoice\)

零售商和电子商务通常是基于发票, 而不是销售订单交货订单。这种方法适用于企业, 你从订购数量交付量可能会有所不同 :食品（根据实际公斤发票）。

该方法下, 如果你部分发货, 只需要为实际发出的数量开票。如果需要未完成订单的话\(部分发货和稍晚剩余发出\), 客户会收到基于两次发货生成的两个发票。

### 电子商务订单 ‣ 发票

在全部付款完成后, 电商订单也会触发订单的创建, 如果允许通过支票和电汇付款, Odoo只会创建一张订单并且一旦付款完成发票会触发。

## 合约

### 定期合同‣发票

如果您使用的合同, 您可以根据时间和材料的花费, 费用或服务/产品固定线路引发的发票。每个月, 营业员将根据有关合同规定的活动引发的发票。

活动可以是 :

* 固定的产品/服务, 从销售订单来了链接到该合同

* 采购材料（你将重新开具发票）

* 基于时间表或购买（分包）时间和材料

* 喜欢旅行和住宿费用, 你重新发票给客户

您可以在合同结束发票或触发中间发票。这种方法使用该发票大多是基于时间和材料服务公司。对于发票上的固定价格服务公司, 他们使用常规的销售订单。

### 经常性合同‣发票

对于订阅, 发票会定期地, 自动地生成。生成发票频率以及服务／产品已经在合同上定义好了。

## 其它

### 手工创建发票

用户也可以不通过合同或者销售订单手工的创建发票。如果没有使用销售模块\(报价\)以及仓库模块, 建议使用手工创建发票。

及时可以从销售订单中创建发票, 在一些特殊场景中还是需要手工创建发票 :

* 如果需要创建退款

* 如果需要折扣

* 如果需要变更为从销售订单开票

* 如果需要对不是主营业务的交易开票

### 具体模块

一些特定的模块还能够生成发票草案 :

* 会员资格：每年给你的会员开发票
* 修理: 为售后服务开票



