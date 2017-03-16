<!DOCTYPE HTML>
<html lang="zh-CN">
<head>
    <meta charset="UTF-8">
    <title>Hello World!</title>
    <meta name="viewport" content="initial-scale=1.0, maximum-scale=1.0, user-scalable=no" />
    <meta name="keywords" content="" />
    <meta name="description" content="" />
    <meta name="apple-mobile-web-app-capable" content="no" />
    <meta name="format-detection" content="telephone=no">
    <link rel="stylesheet" type="text/css" href="../css/style-index.css" />
</head>
<body style="background-color:#c11925;overflow-x: hidden;">
  <img src="../img/bj.gif3" class="flow-bg" alt="" />
  <div style="width:100%;background-color:#fa2231;"><img src="../img/fl.gif" class="flow-top-img" alt=""/></div>
  <div class="flow-input-box" style="width:100%;">
    <img src="../img/rub.gif" class="flow-input-bg" alt="" style="height: 100%;"/>
    <input type="text" class="flow-input" value="请输入您的电信手机号码">
    <button onclick="showOrCloseLayer('open')"><img src="../img/cai.fw.png" class="flow-input-remove" /></button>
  </div>
  <div class="flow-rule" style="background-color:#c11925;">
      <h1>活动规则：</h1>
      <ul>
        <li>粉丝参与“福利大派送  流量免费兑”活动，即可随机获得电信包流量（10M、30M、500M），100%拆红包中奖。</li>
        <li>每个粉丝只能兑换一次，仅限广东省内电信号码参与兑换。（电信号码开头为：133、153、189、180、181、177）</li>
        <li>流量包兑完即止。</li>
        <li>最终解释权归多粉所有。</li>
      </ul>
  </div>

  <div style="width:100%;text-align:center;background-color:#c11925;">
    <img style="width:45%;" src="../img/logo.fw.png">
  </div>
      <div class="layer_popup" id="layerPopup">
        <div class="layer_content">
            <div class="content-box">
               <div class="content-title">温馨提示</div>
               <span class="content-close" onclick="showOrCloseLayer('close')">×</span>
            </div>
         <div class="prompt"><img src="../img/1.gif"></div>
           <h5>亲、活动仅限中国电信广东用户 </h5>
           <div class="bouuton">
               <div class="login-button"><a href="" id="login-button-submit">确定</a></div>
          </div>
        </div>
      </div>
      <script>
      var showOrCloseLayer = function(type){
        var layerPopup = document.querySelectorAll('.layer_popup');
        if(type == 'close'){
          layerPopup[0].style.display = 'none';
        }else{
          layerPopup[0].style.display = 'block';

        }
        console.log(layerPopup)
      }
      </script>
</body>
</html>