# hungry
H5自助购买，为自助货柜的扫描付款，调起的是自己的的收银台。
项目背景：办公室自助贩卖机的兴起，同时公司是做支付的，所以为推广以前的H5收银台，同时也为了适应潮流（其实用户较少）才启动了这个项目。并且项目投产没有夭折，
继而才有了这个项目。
技术：原生和jQuery，原始传统的项目。分为商品列表页和订单详情页。
功能：列表商品的查询，列表项和购物车项的数量联动，购物车采用localstorage存储数据，确认订单后生成订单号，后台根据订单号查询该笔订单的状态，
前台根据状态来判断是否仍然进行数据的缓存。
开发人员：1前端，后台涉及交易对应后台，核心组后台。
开发环境：集中的环境，需要前端和后台都把代码部署到开发环境的服务器上面进行联调。
