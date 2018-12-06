
<!DOCTYPE html>
<html>
<head>
    <meta charset="UTF-8">
    <title>redirect</title>
    <meta id="i18n_pagename" content="message">
    <meta name="viewport" content="width=device-width, user-scalable=no, initial-scale=1.0, maximum-scale=1.0, minimum-scale=1.0">
    <script src="https://static.medishares.net/js/jquery-3.2.1.min.js"></script>
    <script src="https://static.medishares.net/js/common.js?v=2018082901"></script>
</head>
<body>
<div class="mds-group">
loading...

<script type="text/javascript">

  $(function() {

    (function ($) {
        $.getUrlParam = function (name) {
            var reg = new RegExp("(^|&)" + name + "=([^&]*)(&|$)");
            var r = window.location.search.substr(1).match(reg);
            if (r != null) return unescape(r[2]); return null;
        }
    })(jQuery);


    function initTronWeb(){
      return new Promise(function(resolve, reject){
        let tries = 0;

        // 初始化成功后执行
        const loadFinish = function(){
          account = tronWeb.defaultAddress.base58;
          resolve(window.tronWeb);
        };

        let timer = setInterval(function(){
          if(window.tronWeb){
            clearInterval(timer);
            if(!window.tronWeb.defaultAddress.base58){
              window.tronWeb.on('addressChanged',function(){
                return loadFinish();
              });
            }else{
              return loadFinish();
            }
          }
          if(tries > 10){
            clearInterval(timer);
            reject();
          }
        }, 100);
      });
    }

    initTronWeb().then(function(tronWeb){
      // console.log(tronWeb);
      account = tronWeb.defaultAddress.base58;

      var dapp = $.getUrlParam('dapp');

      switch(dapp)
      {
        case 'tronscan':

          window.location.href='https://tronscan.org/#/address/' + account;
          break;
        default:
          window.location.href='https://tronscan.org/#/address/'+account;
      }

    })

  });

</script>

</div>
</body>
</html>
