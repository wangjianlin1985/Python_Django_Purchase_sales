# Python_Django_Purchase_sales
Python基于Django商品销售进销存系统毕业源码案例设计

## 技术环境: PyCharm + Django2.2 + Python3.6 + mysql5.6

采用最新Python环境和Django框架实现的一个商品进销存销售管理系统，管理员可以在后台发布管理各种信息包括商品信息，供应商和客户信息，商品进货和销售记录等，用户可以在前台查询信息！

## 实体ER属性：
商品类别: 商品类别编号,商品类别名称

产品信息: 产品编号,产品类别,产品名称,产品图片,产品单价,产品库存,生产日期,产品描述

供应商: 供应商编号,供应商名称,供应商电话,联系人,供应商地址

客户信息: 客户编号,客户名称,联系人,联系电话,联系地址

产品进货: 进货编号,进货产品,进货日期,进货单价,进货数量,供应商,负责人

产品销售: 销售编号,销售产品,销售日期,销售价格,销售数量,销售客户,销售负责人
