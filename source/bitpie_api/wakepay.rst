比特派 APP 唤起支付
=================================

比特派唤起流程图

..  image:: ../img/app_wake_pay.png
    :width: 364px
    :height: 430px
    :scale: 100%
    :align: center


说明：

1、通过调用 API 获取支付二维码。

2、判断是否安装比特派。

3、唤起比特派进行支付，支付之后调用 API 来判断订单状态。

4、支付的币数必须先充进比特派的派银行。


      ** API **
         * ``url`` *bitpie://piebank/pay?order_id={transfer_id}&amount={amount}&coin_code={coin_code}&app_name={app_name}*


      ** 参数 **
         * ``transfer_id`` *订单号*
         * ``amount`` *支付币数*
         * ``coin_code`` *币种代码*
         * ``app_name`` *应用名称*

      ** 回值 **






