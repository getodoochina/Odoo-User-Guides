# 使用支票支付

当支付供应商账单时,你可选择用支票来支付。然后,在一天结束的时候,可批量打印所有支票。最后,银行将支付的支票和银行对账单核销。

## 配置

### 安装必须的模块

用支票来付款,必须安装\* 支票填写 模块。这个模块登记支票处理。其他模块用来打印支票, 国家不同也不同。举个例子,美国 支票打印 \[UNKNOWN NODE problematic\]模块根据美国的支票来设计。

> 注解
>
> 根据所在国家和所使用的科目表,这些模块可默认安装。\(例如:美国用户不用安装,已默认配置\)。

### 激活支票付款方式

如需用支票支付,必须在银行账上激活付款方式。从会计仪表板\(进入会计应用程序的界面\),点击你的银行账户:\[UNKNOWN NODE title\_reference\] option. 在\* 支付方式 字段,设置 检查 \[UNKNOWN NODE problematic\]。

## 打印支票的兼容支票纸张

### 美国

对于美国, Odoo默认支持支票格式 :

* Quickbooks & Quicken: 在顶部检查,存根在中间和底部
* Peachtree: 在中部检查,存根在顶部和底部
* ADP: 在底部检查,存根在顶部

通过自定义格式, 可自定义自己的支票格式。

## 用支票支付供应商账单

用支票支付采购发票, 需要三个步骤:

1. 在账单上登记付款

2. 批量打印所有的已登记付款

3. 调节银行对账单

### 用支票登记付款

如需在账单上登记付款,在此点开发票:menuselection:\[UNKNOWN NODE title\_reference\]. 一旦采购发票审核,可登记付款。在对话框内, 将\* 支付方式 设置为 \* \* 支票 \[UNKNOWN NODE problematic\]。

付款界面字段的解释:

| 字段 | 解释 |
| :--- | :--- |
| Has Invoices | 技术字段可使用 |
| Hide Payment | 当所选的账设置为“手动”, 支付方式的字段被隐藏. |
| Method |  |
| Code | 技术字段根据付款方式来调整。 |
| Manual | 勾选此选项如果你的预先印制支票是没有编号的。 |
| Numbering |  |
| Check Number | 所选的账簿已配置成打印支票编号。如果支票已有了编号或当前编号是错误的,你可在账簿界面去更改设置。 |

### 打印支票

从会计仪表盘,银行账户,可看到一个链接“X支票打印”。点击这个链接,会得到所有未打印的支票清单。从这个界面,可批量打印或是逐个检查。

如果你想在打印前查看每笔付款,打开支付界面,点击\* 打印支票 \[UNKNOWN NODE problematic\]。对话框会问你检查的编号。它会自动提出你下一个编号,但是,如果编号不匹配, 可修改。

如需批量打印,从列表中选择所有支票, 点击顶部“打印”菜单。

### 调节银行对账单

当处理银行对账单时,支票已从银行账户支出,Odoo将自动与付款匹配。这标志着付款\* 核销 \[UNKNOWN NODE problematic\]。

> 小技巧
>
> 如支票未支付,点击付款, 过滤状态。查看2星期前的付款。

## 用支票支付任何东西

可登记与发票没有关系的付款。使用顶部菜单:menuselection:\[UNKNOWN NODE title\_reference\]. 登记付款, 选择付款方式。

如果支付一个特殊的发票,在\* \* 备忘录\* \[UNKNOWN NODE problematic\]字段写入备注。

付款登记后, 点击\* 确定 。确认后,就可以直接 打印支票 \[UNKNOWN NODE problematic\]或批量打印:

* Print checks
* Reconcile bank statements



