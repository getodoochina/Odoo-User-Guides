# 如何从网站生成线索?

您的网站应该是你公司的第一线索生成工具。您的网站是您的在线营销活动的中心枢纽, 你自然会推动合格的流量养活你的销售管道。当一个潜在客户登陆你的网站, 你的目标是捕捉到他的信息, 以便能够留在与他联系, 进一步推动他来到销售漏斗。

这就是一个典型的在线线索产生过程中的工作 :

* 您的网站访问者点击号召行动\(CTA\)从你的营销方式中的一种\(例如电子邮件通讯, 社交媒体消息或博客文章\)

* 该CTA引领你的访问者到收集个人信息的形式登陆页面\(如他的名字, 他的电子邮件地址, 他的电话号码\)。

* 访问者发送表单并自动在Odoo里生成一个线索。

> 小技巧
>
> 你的号召行动, 登陆页面和表单是线索生成过程的关键部分。随着Odoo网站, 你可以轻松地创建和优化的关键要素, 而无需编写代码或使用第三方应用程序。在这里了解更多&lt;https ://www.odoo.com/page/website-builder&gt; \[UNKNOWN NODE problematic\]。

在Odoo, 网站和CRM模块完全集成, 这意味着您可以轻松地通过您的网站的各种方式生成线索。但是, 即使你的网站托管在另一个CMS, 仍然可以使用Odoo CRM从您的网站产生线索。

## 激活线索阶段

默认情况下, 线索阶段在Odoo CRM 里是不激活的。而是, 新的线索自动成成机会.你能轻松地激活增加线索步骤的选项.如果你要导入你的联系活动作为线索而不是机会, 从销售模块的 **配置\(Configuration\)** ‣ **设置\(Settings\)** , 如下所示选择 使用线索如果... 的选项并点击 **应用** 。

注意即使没有激活这个步骤, 以下信息依然适用 -生成的线索会位于仪表盘的机会中

## 从 Odoo 网站

让我们假设你要尽可能多的得到你的网站访问者的信息。但是你怎么能确保每个想知道更多关于你公司的产品和服务的人真的留下了他的信息？感谢Odoo在CRM和网站模块间的集成, 你能轻松地自动收集线索, 感谢 联系表 和 表单生成 模块。

> 注解
>
> 另外好的方法是从你的Odoo网站的通讯或通讯弹窗收集来访者的邮件地址来产生线索。这些摘要会在你的邮件营销的邮件列表上生成新的联系人。这里可以了解更多&lt;https ://www.odoo.com/page/email-marketing&gt; \[UNKNOWN NODE problematic\]。

### 配置

从安装网站建设者模块开始。从主仪表盘, 点击 应用 , 在搜索栏中输入“ 网站 " , 并点击 安装 。您将被自动重定向到Web界面。

> 小技巧
>
> 该教程将在屏幕上弹出窗口, 如果这是你用Odoo网站上的第一次。这将帮助你开始使用的工具, 你就可以在几分钟内使用它。因此, 我们强烈建议您使用它。

### 使用联系模块创建一个线索

您可以毫不费力地通过联系表格生成线索在 联系我们 的页面上。要做到这一点, 首先需要安装联系表格模块。它会在你的 联系我们 页面添加联系人的形式, 并自动生成表格提交线索。

要安装它, 使用在屏幕的左上角方形图标回到后台。然后, 点击 应用程序 , 输入“ 联系表 " , 在搜索栏\(不要忘记删除 应用程序 标记, 否则你将看不到该模块\), 然后单击 安装 。

一旦模块安装完, 如下联系表单会集成到你的“联系我们" 的页面。这个表单被链接到Odoo CRM, 意味着所有通过这个表单输入的数据会被CRM捕获并生成一个新线索。

通过联系表单创建的所有线索都可以在销售模块中访问, 通过点击 \[UNKNOWN NODE problematic\] 。线索的名字对应与联系表格上的“主题" 字段, 其他所有的信息都存储在CRM中的相应字段。作为销售人员, 你可以添加更多的信息, 率先转变成一个机会, 甚至直接将其标记为赢或输。

### 使用界面格式生成器建立一个线索

您可以在您的网站上的任何目标网页上使用格式生成器创建完全可编辑的自定义表单。至于联系表格模块, 访问者已完成表格并点击该按钮后, 表单生成器会自动生成一个线索 发送 。

从后端, 转到设置和安装“ 网站表单生成器 " 模块\(不要忘记删除 应用程序 标记, 否则你将看不到模块\)。然后, 回到网站上, 去你想要的目标网页, 然后点击编辑访问可用片段。表单生成器片段位于 功能 部分。

一旦你已经把你的表单放置在您希望的网页位置上, 一个 表单参数 窗口会弹出。从 行动 下拉列表中, 选择 创建一个线索 在Odoo CRM自动创建线索。在 谢谢 字段中, 选择要重定向访问者提交表单后\(你不添加任何URL, 消息“表格已成功发送" 网页的URL将确认提交\)。

然后, 您可以开始创建自定义窗体。要添加新的领域, 请点击 选择容器块 , 然后在蓝色 自定义 按钮。 3个选项就会出现:

* **Change Form Parameters**: allows you to go back to the Form Parameters and change the configuration
* **Add a model field**: allows you to add a field already existing in Odoo CRM from a drop-down list. For example, if you select the Field Country, the value entered by the lead will appear under the Country field in the CRM - even if you change the name of the field on the form.
* **Add a custom field**: allows you to add extra fields that don't exist by default in Odoo CRM. The values entered will be added under "Notes" within the CRM. You can create any field type : checkbox, radio button, text, decimal number, etc.

任何提交的表单将在后台创建一个线索。

## 从其他CMS系统

如果您使用Odoo CRM但不是Odoo网站, 您依然可以用电子邮件网关自动化您的在线销售过程, 通过编辑表单上“提交" 按钮, 更换超级链接, 用一个mailto到你的相关的邮件别名\(了解如何创建销售别名 :DOC:'&lt;电子邮件&gt; \[UNKNOWN NODE problematic\]\)。

例如, 如果你的公司的别名是 salesEMEA@mycompany.com , 加" mailto :salesEMEA@mycompany.com "到常规超链接的代码\(CTRL + K\)来生成一个线索到相关销售团队Odoo CRM。



