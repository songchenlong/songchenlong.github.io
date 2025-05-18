<!-- ---
title: Contact
date: 2022-10-24

type: landing

sections:
  - block: contact
    content:
      title: Contact
      # text: |-
      #   Lorem ipsum dolor sit amet, consectetur adipiscing elit. Integer tempus augue non tempor egestas. Proin nisl nunc, dignissim in accumsan dapibus, auctor ullamcorper neque. Quisque at elit felis. Vestibulum ante ipsum primis in faucibus orci luctus et ultrices posuere cubilia curae; Aenean eget elementum odio. Cras interdum eget risus sit amet aliquet. In volutpat, nisl ut fringilla dignissim, arcu nisl suscipit ante, at accumsan sapien nisl eu eros.
      email: yuyanwei@ouc.edu.cn
      address:
        street: 450 Serra Mall
        city: Stanford
        region: CA
        postcode: '94305'
        country: United States
        country_code: US
      # coordinates:
      #   latitude: '35.7784'
      #   longitude: '120.0362'
      directions: Enter Building 1 and take the stairs to Office 200 on Floor 2
      # office_hours:
      #   - 'Monday 10:00 to 13:00'
      #   - 'Wednesday 09:00 to 10:00'
      # appointment_url: 'https://calendly.com'
      #contact_links:
      #  - icon: comments
      #    icon_pack: fas
      #    name: Discuss on Forum
      #    link: 'https://discourse.gohugo.io'
    
      # Automatically link email and phone or display as text?
      autolink: true
    
      # Email form provider
      # form:
      #   provider: netlify
      #   formspree:
      #     id:
      #   netlify:
      #     # Enable CAPTCHA challenge to reduce spam?
      #     captcha: false
    design:
      columns: '1'
--- -->

---
title: Contact
date: 2022-10-24

type: landing
---

<div class="py-12">
  <div class="container mx-auto px-4">
    <div class="grid grid-cols-1 gap-8 max-w-3xl mx-auto">
      <!-- Email卡片 -->
      <div class="bg-white rounded-xl shadow-lg hover:shadow-xl p-8 transition-all duration-300 transform hover:-translate-y-1 border-t-4 border-primary">
        <div class="w-16 h-16 bg-primary/10 rounded-full flex items-center justify-center mb-6">
          <i class="fa-solid fa-envelope text-primary text-2xl"></i>
        </div>
        <h3 class="text-xl font-bold text-gray-800 mb-3">电子邮箱</h3>
        <p class="text-gray-600 mb-4">如需发送邮件，请使用以下邮箱地址联系我们</p>
        <a href="mailto:contact@example.com" class="text-primary hover:text-primary/80 font-medium flex items-center transition-colors">
          <i class="fa-solid fa-arrow-right mr-2"></i>
          contact@example.com
        </a>
      </div>
      <!-- 地址卡片 -->
      <div class="bg-white rounded-xl shadow-lg hover:shadow-xl p-8 transition-all duration-300 transform hover:-translate-y-1 border-t-4 border-secondary">
        <div class="w-16 h-16 bg-secondary/10 rounded-full flex items-center justify-center mb-6">
          <i class="fa-solid fa-map-marker-alt text-secondary text-2xl"></i>
        </div>
        <h3 class="text-xl font-bold text-gray-800 mb-3">实验室地址</h3>
        <p class="text-gray-600 mb-4">我们位于以下地址，欢迎前来参观交流</p>
        <div class="text-gray-800 font-medium">
          <p>中国北京市海淀区</p>
          <p>中关村科技园区</p>
          <p>清华大学某某楼 XXXX 室</p>
        </div>
      </div>
      <!-- 微信公众号卡片 -->
      <div class="bg-white rounded-xl shadow-lg hover:shadow-xl p-8 transition-all duration-300 transform hover:-translate-y-1 border-t-4 border-green-500">
        <div class="w-16 h-16 bg-green-500/10 rounded-full flex items-center justify-center mb-6">
          <i class="fa-brands fa-weixin text-green-500 text-2xl"></i>
        </div>
        <h3 class="text-xl font-bold text-gray-800 mb-3">微信公众号</h3>
        <p class="text-gray-600 mb-4">扫描下方二维码，关注我们的微信公众号获取最新资讯</p>
        <div class="bg-white p-3 inline-block rounded-lg shadow-sm">
          <img src="https://picsum.photos/200/200" alt="微信公众号二维码" class="w-48 h-48 object-cover">
        </div>
        <p class="mt-4 text-green-500 font-medium">实验室名称</p>
      </div>
    </div>
  </div>
</div>