比特派 APP 唤起
=================================

比特派唤起流程图

..  image:: ../img/app_wake.png
    :width: 377px
    :height: 551px
    :scale: 100%
    :align: center


说明：

1、比特派唤起前，先调用 API 登录。

2、判断是否安装比特派。

3、唤起比特派之后，通过调用 API 获取用户信息。


      ** API **
         * ``url`` *bitpie://piebank/login?app_name={token_planets}&app_key={hkey}*


      ** 参数 **
         * ``token_planets``
         * ``hkey`` *QR标识*

      ** 回值 **






