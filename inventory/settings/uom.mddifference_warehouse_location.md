# What is the difference between warehouses and locations?

在Odoo中 **仓库** 是你存放货物的实际的建筑／地方。你可以设置多仓库并在不同的仓库质检调拨。

A Location, is a specific space within your warehouse. It can be considered as a sublocation of your warehouse, as a shelf, a floor, an aisle, etc. Therefore, a location is part of one warehouse only and it is not possible to link one location to multiple warehouses. You can configure as much locations as you need under one warehouse.

有3种类型的位置 :

* The Physical Locations are internal locations that are part of the warehouses for which you are the owner. They can be the loading and unloading area of your warehouse, a shelf or a department, etc.
* The Partner Locations are spaces within a customer and/or vendor's warehouse. They work the same way as Physical Locations with the only difference being that you are not the owner of the warehouse.
* The Virtual Locations are places that do not exist, but in which products can be placed when they are not physically in an inventory yet \(or anymore\). They come in handy when you want to place lost products out of your stock \(in the Inventory loss\), or when you want to take into account products that are on their way to your warehouse \(Procurements\).

在Odoo中, 库位按照级别进行架构组织。根据库位之间的父－子关系, 你可以把库位配置为一个树形结构。这能让你对库存操作进行详细的分析以及对仓库进行更好的管理。



