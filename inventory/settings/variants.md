# 使用产品型号\(变体\)

产品变型用来管理有不同变量的产品, 例如尺寸, 颜色等等。它可以让我们在产品模板层面对产品进行管理\(所有的变量\), 也可以在变型层面管理\(特定一个属性\)。

例如, 一个销售ｔ血衫的公司可能有以下产品 :

* B&C T血衫

在该示例中, B&C T血衫 是产品模板, B&C T血衫, S, 蓝色 是一个产品变量, 尺寸和颜色是 属性。

以上示例总共有20个不同的产品\(5中尺寸x4种颜色\)。每一个产品都会有自己的库存, 销售信息, 等等。

## 变型的影响

* **Barcode**: the code and barcode is associated to a variant, not the template. Every variant may have its own barcode / SKU.
* **Price**: every product variant has its own public price that is computed based on the template price \($20\) with an optional extra for every variant \(+$3 for color red\). However, you can define pricelist rules that apply on the template or the variant.
* **Inventory**: the inventory is managed by product variant. You don't own t-shirts, you only own "T-shirts, S, Red", or "T-Shirts, M, Blue". For information purpose, on the product template form, you get the inventory that is the sum of every variant. \(but the actual inventory is computed by variant\)
* **Picture**: the picture is related to the variant, every variation of a product may have its own primary picture.
* **Other fields**: most of the other fields belongs to the product template. If you update them, it updates automatically all the variants. \(example: Income Account, Taxes\)

## 应该使用产品变型吗？

### 何时应该使用产品变型？

使用变型有以下影响 :

* eCommerce: in your online shop, the customer will only see product templates in the catalog page. Once the visitor click on such a product, he will have options to choose amongst the variants \(colors, sizes, …\)
* Manufacturing: Using variants allows to define only one bill of material for a product template and slight variations for some of the variants. Example: instead of creating a Bill of Material for "T-shirt, Red, S", you create a bill of material for "T-shirt" and add some lines that are specific to the dimension S, and other lines specific to the color Red.
* Pricing: The default price of a product is computed using the price of the product template and add the optional extra price on each dimension of the variant. This way, variant prices are easier to maintain since you don't have to set the price for every variant. However, it's possible to create pricelist rules to fix price per variants too.

### 在什么时候应该避免使用产品型号？

使用变量有可能会增加操作的复杂程度, 当你要使用产品的变量属性时, 你要确保这样做只会减少操作的复杂程度。

例如, 如果使用型号的话, 在导入期初数据的时候就比较麻烦。你不能只是导入产品的列表, 还必须要导入产品模板以及相关的型号。

另外, 你需要谨慎的选择尺寸作为变量, 这些都术语一个单独的产品模板。局一个例子, 一个公司有如下产品 :

* 质量 :T血衫, 马球, 衬衫

* 颜色 : 红色, 蓝色

* 尺寸 : S, M, L, XL

在该用户案例中, 你可以创建1个带有尺寸变量的模板\(布局, ｔ血衫, 保罗\)。但是, 我们还是建议你创建两种不同的产品把保罗或者衬衫分开, 并且在你的电脑上网站客户也乐意看到这样分 :

* 产品模板 :T血衫

* 产品模板 :马球

## 配置

### 激活产品型号特性

在你使用产品变量之前, 你需要在设置中激活产品变量。要这样做, 你需要进入销售模块, 在菜单 配置 ‣ 设置 , 找到 产品变形 　行, 然后勾选 产品可以有多个变体 , 然后点击 应用 。

### 创建带有型号的产品

一旦你激活了变量选项, 你就可以给产品添加变量。要这样做的话, 进入销售模块 :\[UNKNOWN NODE title\_reference\] 。还可以从采购和库存模块进入产品页面。

现在, 点击你想添加型号的产品。

在产品页面, 一个新的变量页面显示出来。在页面上方的紫色数字是当前该产品的变量数量。要添加新的变量, 点击该按钮, 在新的窗口, 点击 创建 。

在 属性 中, 点击下拉菜单并选择你要添加的变量类型。。如果变量不存在, 你可以通过点击创建和编辑随手创建……

在属性窗口, 值 字段是属性的描述例如绿色, 塑料或者32G, 属性 字段是变量的类型例如颜色, 材料或者内存。

你可以在 属性额外价格 字段顺便给特定型号添加相关成本, 或者选择稍后更改, 点击 保存 。

你也可以给型号添加不同的条码以及内部参考码。

完成输入该型号的所有的特定属性后, 点击 保存。

## 管理产品型号

### 介绍

以下示例就是一个产品模板上的两个不同属性的型号产品:

* B&C T血衫

### 管理组合可能性

默认情况下, 使用上述产品的模板,你可以得到15个不同产品\(3种颜色, 5个尺寸\)。如果XXL只存在与红色和蓝色t恤,您可以设置禁用于白色产品系列。

要这样做的话, 点击 型号 按钮, 选择XXL, 白色Ｔ血衫。在产品页面上, 不勾选XXL, 白色Ｔ血衫这个产品 有效 框。

> 小技巧
>
> 使产品无效不同于设定产品的库存为0。

### 根据型号设置价格

对产品的有些型号你可以添加超过主要价格的成本。

一旦你激活了产品变量选项, 你就可以在产品上添加产品变量。要这样做, 进入销售模块, 打开 销售 ‣ 产品 并点击你想要更改的产品, 点击 变量价格 按钮来查看变量列表。

点击你想要添加值的变量名称, 确保3个字段可编辑。在 额外属性价格 字段你, 添加该变量的成本, 他会自动的和原始价格相加。

一旦你输入了所有的额外值, 点击 保存 。

