# MobileGo
一个国际的移动充值的API。在这里你可以进行手机话费充值、买数据、电视缴费、购买谷歌礼品卡、购买游戏卡等。An international API for mobile recharge. here you can do cell phone bill recharge, buy data, TV bill payment, buy Google gift card, buy game card and so on.
# API 文档

这是一个演示如何使用 README.md 编写 API 文档的示例。

## 接口概述

在这里提供对 API 的概述和简要说明。

## 接口列表

### 1. 获取产品信息

- **URL:**  `/api/products/{id}` 
- **方法:** GET
- **描述:** 获取指定产品的信息
- **参数:**
  -  `id`  (路径参数)：产品ID
- **返回值:**
  -  `name` ：产品名称
  -  `price` ：产品价格
  -  `description` ：产品描述

### 2. 获取供应商信息

- **URL:**  `/api/providers/{id}` 
- **方法:** GET
- **描述:** 获取指定供应商的信息
- **参数:**
  -  `id`  (路径参数)：供应商ID
- **返回值:**
  -  `name` ：供应商名称
  -  `email` ：供应商邮箱
  -  `address` ：供应商地址

### 3. 获取国家信息

- **URL:**  `/api/countries/{id}` 
- **方法:** GET
- **描述:** 获取指定国家的信息
- **参数:**
  -  `id`  (路径参数)：国家ID
- **返回值:**
  -  `name` ：国家名称
  -  `capital` ：国家首都
  -  `population` ：国家人口

## 示例代码

这里提供一个使用 cURL 的示例代码来演示如何调用 API：
# 获取产品信息
curl -X GET /api/products/123

# 获取供应商信息
curl -X GET /api/providers/456

# 获取国家信息
curl -X GET /api/countries/789
## 注意事项

在这里提供任何其他的注意事项或特殊要求。请确保文档清晰、易读，并包含足够的信息以供其他开发人员理解和使用您的 API。
