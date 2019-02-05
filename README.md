
接口与需要的数据

  打开获取的接口
    https://api.it120.cc/tz/config/get-value?key=mallName get

    https://api.it120.cc/tz/score/send/rule  post  [code:goodReputation]


    https://api.it120.cc/tz/config/get-value?key=recharge_amount_min  get

    https://api.it120.cc/tz/shop/goods/kanjia/list post

    https://api.it120.cc/tz/user/wxapp/login post [code:023sMRpP0CHpr421ukrP0aDDpP0sMRpd ,type:2]

    https://api.it120.cc/lvtian/user/check-token  get [token:74eaf786-b357-477b-b05a-4f67d504af09]

  首页
    https://api.it120.cc/tz/template-msg/wxa/formId  get  [ token: , type:form , formId:the formId is a mock one]

    https://api.it120.cc/tz/banner/list  get  [key:mallName]

    https://api.it120.cc/tz/shop/goods/category/all  get

    https://api.it120.cc/tz/discounts/coupons  get

    https://api.it120.cc/tz/notice/list get  [pageSize:5]

    https://api.it120.cc/tz/shop/goods/list  get  [ categoryId: , nameLike: , page:1 , pageSize:20]  下拉，主动请求 【带上page页码，categoryId是分类id，首页默认没有】

  首页-搜索
    https://api.it120.cc/tz/shop/goods/list  get  [ categoryId: , nameLike:袜子 , page:1 , pageSize:20]

  首页 - 点击公告
    https://api.it120.cc/tz/notice/detail get [id:161]

  首页-公告下面优惠券
    https://api.it120.cc/tz/discounts/fetch get [  id:221 , token:]

  商品详情
    https://api.it120.cc/tz/shop/goods/detail get [id:3776]

    https://api.it120.cc/tz/shop/goods/reputation  get  [goodsId:3776]

    https://api.it120.cc/tz/shop/goods/list  get  [  categoryId: , nameLike: , page:3 , pageSize:20] (首页重复)

    https://api.it120.cc/lvtian/media/video/detail

我的
    https://api.it120.cc/lvtian/user/detail get [token:74eaf786-b357-477b-b05a-4f67d504af09]

    https://api.it120.cc/lvtian/user/amount  get [token:74eaf786-b357-477b-b05a-4f67d504af09]

    https://api.it120.cc/lvtian/score/today-signed  get [token:74eaf786-b357-477b-b05a-4f67d504af09]

