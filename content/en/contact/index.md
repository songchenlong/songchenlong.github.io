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

<meta name="viewport" content="width=device-width, initial-scale=1.0">
<script src="https://cdn.tailwindcss.com"></script>
<link href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/6.7.2/css/all.min.css" rel="stylesheet">
<script>
    tailwind.config = {
        theme: {
            extend: {
                colors: {
                    primary: '#165DFF',
                    secondary: '#0FC6C2',
                    neutral: {
                        100: '#F5F7FA',
                        200: '#E4E6EB',
                        300: '#C9CDD4',
                        400: '#86909C',
                        500: '#4E5969',
                        600: '#272E3B',
                        700: '#1D2129',
                    }
                },
                fontFamily: {
                    inter: ['Inter', 'system-ui', 'sans-serif'],
                },
                boxShadow: {
                    'card': '0 10px 30px -5px rgba(0, 0, 0, 0.1)',
                    'card-hover': '0 20px 40px -5px rgba(0, 0, 0, 0.15)',
                }
            }
        }
    }
</script>
<style type="text/tailwindcss">
    @layer utilities {
        .content-auto {
            content-visibility: auto;
        }
        .text-shadow {
            text-shadow: 0 2px 4px rgba(0,0,0,0.1);
        }
        .transition-custom {
            transition: all 0.3s cubic-bezier(0.4, 0, 0.2, 1);
        }
        .bg-gradient-blue {
            background: linear-gradient(135deg, #165DFF 0%, #0FC6C2 100%);
        }
    }
</style>

<body class="font-inter bg-neutral-100 text-neutral-700 min-h-screen flex flex-col items-center justify-center p-4 md:p-8">
    <!-- 联系信息卡片 -->
    <section class="w-full max-w-3xl">
        <div class="grid grid-cols-1 gap-8">
            <!-- Email卡片 -->
            <div class="bg-white rounded-xl shadow-card hover:shadow-card-hover p-8 transition-custom transform hover:-translate-y-2 border-t-4 border-primary">
                <div class="w-16 h-16 bg-primary/10 rounded-full flex items-center justify-center mb-6">
                    <i class="fa-solid fa-envelope text-primary text-2xl"></i>
                </div>
                <h3 class="text-xl font-bold text-neutral-700 mb-3">电子邮箱</h3>
                <p class="text-neutral-500 mb-4">如需发送邮件，请使用以下邮箱地址联系我们</p>
                <a href="mailto:contact@example.com" class="text-primary hover:text-primary/80 font-medium flex items-center transition-custom">
                    <i class="fa-solid fa-arrow-right mr-2"></i>
                    contact@example.com
                </a>
            </div>
            <!-- 地址卡片 -->
            <div class="bg-white rounded-xl shadow-card hover:shadow-card-hover p-8 transition-custom transform hover:-translate-y-2 border-t-4 border-secondary">
                <div class="w-16 h-16 bg-secondary/10 rounded-full flex items-center justify-center mb-6">
                    <i class="fa-solid fa-map-marker-alt text-secondary text-2xl"></i>
                </div>
                <h3 class="text-xl font-bold text-neutral-700 mb-3">实验室地址</h3>
                <p class="text-neutral-500 mb-4">我们位于以下地址，欢迎前来参观交流</p>
                <div class="text-neutral-700 font-medium">
                    <p>中国北京市海淀区</p>
                    <p>中关村科技园区</p>
                    <p>清华大学某某楼 XXXX 室</p>
                </div>
            </div>
            <!-- 微信公众号卡片 -->
            <div class="bg-white rounded-xl shadow-card hover:shadow-card-hover p-8 transition-custom transform hover:-translate-y-2 border-t-4 border-green-500">
                <div class="w-16 h-16 bg-green-500/10 rounded-full flex items-center justify-center mb-6">
                    <i class="fa-brands fa-weixin text-green-500 text-2xl"></i>
                </div>
                <h3 class="text-xl font-bold text-neutral-700 mb-3">微信公众号</h3>
                <p class="text-neutral-500 mb-4">扫描下方二维码，关注我们的微信公众号获取最新资讯</p>
                <div class="bg-white p-3 inline-block rounded-lg shadow-sm">
                    <img src="https://picsum.photos/200/200" alt="微信公众号二维码" class="w-48 h-48 object-cover">
                </div>
                <p class="mt-4 text-green-500 font-medium">实验室名称</p>
            </div>
        </div>
    </section>
    <script>
        // 卡片悬停效果
        document.querySelectorAll('.shadow-card').forEach(card => {
            card.addEventListener('mouseenter', () => {
                card.classList.add('shadow-card-hover', '-translate-y-2');
            });
            card.addEventListener('mouseleave', () => {
                card.classList.remove('shadow-card-hover', '-translate-y-2');
            });
        });
    </script>
</body>