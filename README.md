# shopify-connector

The UCP agent profile of a private household shopping assistant that looks up products in
Shopify's Global Catalog to compare prices for its owner.

- `agent-profile.json` is the profile passed as `meta.ucp-agent.profile` in catalog requests. It
  declares product search and lookup only: no cart, no checkout, no orders.
- The assistant shows results to its owner with the merchant's name and the product link exactly
  as the catalog returns them, and does not build a product database from them.

Nothing else lives here: no code, no keys.

---

一个家用购物助手的 UCP 说明文件。助手用 Shopify 的 Global Catalog 为主人查商品、比价格。

- `agent-profile.json` 是请求里 `meta.ucp-agent.profile` 指向的文件，只声明商品搜索和查询，
  不含购物车、结账和订单。
- 查到的结果连同商家名和原样的商品链接展示给主人，不用来建商品库。

这里没有别的东西：没有代码，没有密钥。
