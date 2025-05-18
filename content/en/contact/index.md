---
title: Contact
date: 2022-10-24

type: landing

sections:
  - block: markdown
    content:
      title: Contact
      subtitle:
      text: |
        <!-- 电子邮件卡片 -->
        <div class="card mb-5">
          <div class="card-header bg-gray-500 text-black font-weight-bold"> <!-- 灰色标题栏 -->
            <i class="fa fa-envelope mr-2"></i>E-mails
          </div>
          <div class="card-body">
            <p class="card-text">您可以通过以下邮箱与我们取得联系：</p>
            <ul class="list-group list-group-flush">
              <li class="list-group-item"><i class="fa fa-envelope"></i>&nbsp;&nbsp;<a href="mailto:yuyanwei@ouc.edu.cn">yuyanwei@ouc.edu.cn</a></li>
            </ul>
          </div>
        </div>
        <!-- 地址卡片 -->
        <div class="card mb-5">
          <div class="card-header bg-gray-600 text-black font-weight-bold">
            <i class="fa fa-map-marker mr-2 text-black"></i>Address
          </div>
          <div class="card-body">
            <!-- 文字描述的地址 -->
            <div class="mb-4">
              <p class="font-weight-bold">中国海洋大学（西海岸校区）</p>
              <p class="text-secondary">青岛市黄岛区松岭路238号<br>邮编：266100<br>中国</p>
            </div>
            <!-- 地图组件 -->
            <div class="embed-responsive embed-responsive-16by9">
              <iframe src="https://uri.amap.com/embed?mapType=0&zoom=16&center=120.022208,35.778096&markers=120.022208,35.778096&markerTitles=中国海洋大学(西海岸校区)" 
                      width="100%" height="300" frameborder="0" style="border:1px solid #ddd" allowfullscreen></iframe>
            </div>
          </div>
        </div>
        <!-- 微信卡片 -->
        <div class="card">
          <div class="card-header bg-gray-500 text-black font-weight-bold"> <!-- 灰色标题栏 -->
            <i class="fa fa-weixin"></i>Wechat
          </div>
          <div class="card-body d-flex flex-column align-items-center justify-content-center py-5">
            <div class="qr-container p-3 border border-gray-300 rounded-lg shadow-lg mb-4"> <!-- 图片地址存在static/images/中 -->
              <img src="/images/wechat.jpg" alt="WeChat QR Code" class="img-fluid rounded" style="max-width:220px;">
            </div>
            <h5 class="card-title">时空智能挖掘分析</h5>
            <p class="card-text"><i class="fa fa-qrcode mr-2"></i>Wechat ID：SIGMA-OUC</p>
          </div>
        </div>

      
    design:
      # See Page Builder docs for all section customization options.
      # Choose how many columns the section has. Valid values: '1' or '2'.
      columns: '1'
---

