
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

    https://api.it120.cc/lvtian/media/video/detail  get  [videoId:f062685c77294c05b944113235e22fca]

    https://api.it120.cc/lvtian/shop/goods/pingtuan/list  get  [goodsId:116910]

    https://api.it120.cc/lvtian/shop/goods/price   get  [goodsId:116910,propertyChildIds:10733:41992,]

  待付款订单
    https://api.it120.cc/lvtian/user/shipping-address/default  get  [token:8b303736-5b91-40e5-9092-f3caec8faf18]

    https://api.it120.cc/lvtian/user/shipping-address/add  get  [token:8b303736-5b91-40e5-9092-f3caec8faf18,id:0,provinceId:110000,cityId:110101,districtId:,linkMan:好孩子,address:被打断发个梵蒂冈,mobile:13123456789,code:131234,isDefault:true]

    https://api.it120.cc/lvtian/order/create  post  [token:8b303736-5b91-40e5-9092-f3caec8faf18,goodsJsonStr:[{"goodsId":116910,"number":1,"propertyChildIds":"10733:41992,","logisticsType":0, "inviter_id":0}],remark:,provinceId:110000,cityId:110101,address:被打断发个梵蒂冈,linkMan:好孩子,mobile:13123456789,code:131234,calculate:true]

    https://api.it120.cc/lvtian/discounts/my  get  [token:8b303736-5b91-40e5-9092-f3caec8faf18,status:0]

    https://api.it120.cc/tz/template-msg/wxa/formId  get  [ token: , type:form , formId:the formId is a mock one]

    https://api.it120.cc/lvtian/template-msg/put  post  [module:order,business_id:245374,trigger:-1,postJsonString:{"keyword1":{"value":"2019-02-08 02:34:09","color":"#173177"},"keyword2":{"value":"8元","color":"#173177"},"keyword3":{"value":"OD1902081878140886","color":"#173177"},"keyword4":{"value":"订单已关闭","color":"#173177"},"keyword5":{"value":"您可以重新下单，请在30分钟内完成支付","color":"#173177"}},template_id:mGVFc31MYNMoR9Z-A9yeVVYLIVGphUVcK2-S2UdZHmg,type:0,token:8b303736-5b91-40e5-9092-f3caec8faf18,url:pages/index/index]  与 [module:order,business_id:245374,trigger:2,postJsonString:{"keyword1":{"value":"您的订单已发货，请注意查收","color":"#173177"},"keyword2":{"value":"OD1902081878140886","color":"#173177"},"keyword3":{"value":"2019-02-08 02:34:09","color":"#173177"}},template_id:Arm2aS1rsklRuJSrfz-QVoyUzLVmU2vEMn_HgMxuegw,type:0,token:8b303736-5b91-40e5-9092-f3caec8faf18,url:pages/order-details/index?id=245374]

  订单列表
    https://api.it120.cc/lvtian/order/statistics  get [token:392ffdd9-dffd-4e13-a3ce-82717cbbb940]

    https://api.it120.cc/lvtian/order/list   get  [token:392ffdd9-dffd-4e13-a3ce-82717cbbb940,status:0] 【 status 0待付款 1待发货 2待收货 3待评价 4已完成 】

    https://api.it120.cc/lvtian/order/close  get  [token:392ffdd9-dffd-4e13-a3ce-82717cbbb940,orderId:245375]

  我的
    https://api.it120.cc/lvtian/user/detail get [token:74eaf786-b357-477b-b05a-4f67d504af09]

    https://api.it120.cc/lvtian/user/amount  get [token:74eaf786-b357-477b-b05a-4f67d504af09]

    https://api.it120.cc/lvtian/score/today-signed  get [token:74eaf786-b357-477b-b05a-4f67d504af09]

  在线充值
    https://api.it120.cc/lvtian/pay/alipay/semiAutomatic/payurl post [token:392ffdd9-dffd-4e13-a3ce-82717cbbb940,money:100]

    https://api.it120.cc/lvtian/pay/wx/wxapp  post  [token:392ffdd9-dffd-4e13-a3ce-82717cbbb940,money:100,remark:在线充值,payName:在线支付,nextAction:[object Object]]