---
title: "A-Acquiring 的角色有 5 個"
date: "2022-10-18"
tags: SaaS
---

## Acquiring 的角色有 5 個

主要有 5 個角色:
1. **ISO/MSP (Independent sales organization/ Member service provider)**

第三方支付公司，被授權可處理某家企業的信用卡交易。

[ISO 跟 MSP 基本上是指同樣的角色](https://staxpayments.com/blog/what-is-an-iso/)，但 Visa 稱呼為 ISO ; Mastercard 稱呼為 MSP。

為什麼商家不直接跟銀行找銀行合作、串接金流服務呢 ? [因為比較麻煩](https://bit.ly/3VBouR9)，包含: 
1. 銀行需要跨部門申請，流程繁瑣耗時 (銀行內部的公文要跑很久)
2. 測試串接維護，高工程成本 (商家要多雇個工程師)
3. 年費、規費都得繳，還比第三方金流高 (比較貴)

案例公司有
- 國外: Square, The Transaction Group, Paywire, North American Bankard
- 台灣: 藍新、綠界、紅陽、歐付寶

ISO/MSP 會跟 Payment Gateway 合作，當商家產生交易時將交易資訊拋送給 Payment Gateway 處理。

2. **Payment Gateway (支付閘道)**

處理付款資訊的資訊商。

案例公司有: 
- 國外: PayPal, Stripe, worldpay from FIS, Klarna, Aden, Alipay, nmi, amazon payments
- 台灣: 藍新、綠界、紅陽、ezPay 台灣支付、TapPay、GMO

3. **Acquiring Processor (收單處理機構)**

[「Acquiring (收單)」指提供刷卡機（或是網路刷卡機制）給店家（稱為特約商店）的機構](https://www.mypay.com.tw/main_article1.html)。

「Acquiring Processor」是處理收單資訊的資訊商，連接「Card network (信用卡網路)」和「Acquiring bank(收單銀行)」。

案例公司有: 
- 國外: Aden, risers, worldpay from FIS, Elavon, FirstData, global payments, First American, PayPal
- 台灣: 大型銀行通常都是、聯合信用卡處理中心、[環匯](https://www.bnext.com.tw/article/56540/global-payments-strategy)

4. **Merchant Account (商戶在銀行的帳號)**

5. **Acquiring bank (收單銀行)**: 提供商戶在銀行的帳戶，可用來收取消費者付費的款項。

Next > [[notes/Issuing 的角色有 4 個|Issuing (發卡)]]