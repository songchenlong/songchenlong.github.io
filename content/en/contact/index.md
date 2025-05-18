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
view: citation
banner:
  caption: ''
  image: ''


---

<!DOCTYPE html>
<html lang="zh-CN">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>实验室联系方式</title>
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
</head>
<body class="font-inter bg-neutral-100 text-neutral-700 min-h-screen flex flex-col">
    <!-- 顶部导航栏 -->
    <header class="bg-white shadow-md fixed w-full z-50 transition-all duration-300" id="navbar">
        <div class="container mx-auto px-4 py-3 flex items-center justify-between">
            <div class="flex items-center space-x-2">
                <i class="fa-solid fa-flask text-primary text-2xl"></i>
                <h1 class="text-xl font-bold text-neutral-700">实验室名称</h1>
            </div>
            <nav class="hidden md:flex items-center space-x-8">
                <a href="#" class="text-neutral-500 hover:text-primary transition-custom font-medium">首页</a>
                <a href="#" class="text-primary border-b-2 border-primary pb-1 font-medium">联系方式</a>
                <a href="#" class="text-neutral-500 hover:text-primary transition-custom font-medium">关于我们</a>
                <a href="#" class="text-neutral-500 hover:text-primary transition-custom font-medium">研究方向</a>
                <a href="#" class="text-neutral-500 hover:text-primary transition-custom font-medium">新闻动态</a>
            </nav>
            <button class="md:hidden text-neutral-700 text-xl" id="menuBtn">
                <i class="fa-solid fa-bars"></i>
            </button>
        </div>
        <!-- 移动端菜单 -->
        <div class="md:hidden hidden bg-white w-full absolute top-full left-0 shadow-lg" id="mobileMenu">
            <div class="container mx-auto px-4 py-3 flex flex-col space-y-4">
                <a href="#" class="text-neutral-500 hover:text-primary py-2 transition-custom">首页</a>
                <a href="#" class="text-primary font-medium py-2">联系方式</a>
                <a href="#" class="text-neutral-500 hover:text-primary py-2 transition-custom">关于我们</a>
                <a href="#" class="text-neutral-500 hover:text-primary py-2 transition-custom">研究方向</a>
                <a href="#" class="text-neutral-500 hover:text-primary py-2 transition-custom">新闻动态</a>
            </div>
        </div>
    </header>

    <!-- 主内容区 -->
    <main class="flex-grow pt-24 pb-16">
        <!-- 页面标题 -->
        <section class="text-center mb-12">
            <h2 class="text-[clamp(2rem,5vw,3.5rem)] font-bold text-neutral-700 mb-4 text-shadow">联系我们</h2>
            <p class="text-neutral-500 max-w-2xl mx-auto text-lg">欢迎随时与我们取得联系，您可以通过以下方式找到我们或给我们留言</p>
            <div class="w-24 h-1 bg-primary mx-auto mt-6 rounded-full"></div>
        </section>

        <!-- 联系信息卡片 -->
        <section class="container mx-auto px-4 mb-16">
            <div class="grid grid-cols-1 md:grid-cols-3 gap-8">
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

        <!-- 地图区域 -->
        <section class="container mx-auto px-4 mb-16">
            <div class="bg-white rounded-xl shadow-card p-6 md:p-8">
                <h3 class="text-2xl font-bold text-neutral-700 mb-6 flex items-center">
                    <i class="fa-solid fa-map-location-dot text-primary mr-3"></i>
                    实验室位置
                </h3>
                
                <!-- 地图切换选项卡 -->
                <div class="flex flex-wrap border-b border-neutral-200 mb-6">
                    <button class="map-tab px-6 py-3 font-medium text-primary border-b-2 border-primary" data-map="gaode">
                        高德地图
                    </button>
                    <button class="map-tab px-6 py-3 font-medium text-neutral-500 hover:text-neutral-700" data-map="baidu">
                        百度地图
                    </button>
                </div>
                
                <!-- 地图容器 -->
                <div class="relative h-[500px] rounded-lg overflow-hidden shadow-inner">
                    <!-- 高德地图 -->
                    <div id="gaodeMap" class="map-container absolute inset-0 bg-neutral-100">
                        <img src="https://picsum.photos/1200/500" alt="实验室位置地图" class="w-full h-full object-cover">
                        <div class="absolute top-4 right-4 bg-white/90 backdrop-blur-sm rounded-lg shadow-md p-4 max-w-xs">
                            <h4 class="font-bold text-neutral-700 mb-2">实验室名称</h4>
                            <p class="text-neutral-600 text-sm mb-3">中国北京市海淀区中关村科技园区清华大学某某楼 XXXX 室</p>
                            <div class="flex space-x-2">
                                <a href="#" class="text-xs bg-primary text-white px-3 py-1 rounded hover:bg-primary/90 transition-custom">
                                    <i class="fa-solid fa-location-arrow mr-1"></i> 导航
                                </a>
                                <a href="#" class="text-xs bg-neutral-200 text-neutral-700 px-3 py-1 rounded hover:bg-neutral-300 transition-custom">
                                    <i class="fa-solid fa-expand mr-1"></i> 全屏
                                </a>
                            </div>
                        </div>
                    </div>
                    
                    <!-- 百度地图 -->
                    <div id="baiduMap" class="map-container absolute inset-0 bg-neutral-100 hidden">
                        <img src="https://picsum.photos/1201/500" alt="实验室位置地图" class="w-full h-full object-cover">
                        <div class="absolute top-4 right-4 bg-white/90 backdrop-blur-sm rounded-lg shadow-md p-4 max-w-xs">
                            <h4 class="font-bold text-neutral-700 mb-2">实验室名称</h4>
                            <p class="text-neutral-600 text-sm mb-3">中国北京市海淀区中关村科技园区清华大学某某楼 XXXX 室</p>
                            <div class="flex space-x-2">
                                <a href="#" class="text-xs bg-primary text-white px-3 py-1 rounded hover:bg-primary/90 transition-custom">
                                    <i class="fa-solid fa-location-arrow mr-1"></i> 导航
                                </a>
                                <a href="#" class="text-xs bg-neutral-200 text-neutral-700 px-3 py-1 rounded hover:bg-neutral-300 transition-custom">
                                    <i class="fa-solid fa-expand mr-1"></i> 全屏
                                </a>
                            </div>
                        </div>
                    </div>
                </div>
            </div>
        </section>

        <!-- 联系表单 -->
        <section class="container mx-auto px-4">
            <div class="bg-white rounded-xl shadow-card p-6 md:p-8">
                <h3 class="text-2xl font-bold text-neutral-700 mb-6">留言咨询</h3>
                <p class="text-neutral-500 mb-8 max-w-2xl">如果您有任何问题或建议，请通过以下表单与我们联系，我们将尽快回复您</p>
                
                <form class="grid grid-cols-1 md:grid-cols-2 gap-6">
                    <div class="space-y-2">
                        <label for="name" class="block text-sm font-medium text-neutral-700">姓名</label>
                        <input type="text" id="name" name="name" class="w-full px-4 py-3 border border-neutral-300 rounded-lg focus:ring-2 focus:ring-primary focus:border-primary transition-custom" placeholder="请输入您的姓名">
                    </div>
                    
                    <div class="space-y-2">
                        <label for="email" class="block text-sm font-medium text-neutral-700">电子邮箱</label>
                        <input type="email" id="email" name="email" class="w-full px-4 py-3 border border-neutral-300 rounded-lg focus:ring-2 focus:ring-primary focus:border-primary transition-custom" placeholder="请输入您的电子邮箱">
                    </div>
                    
                    <div class="space-y-2 md:col-span-2">
                        <label for="subject" class="block text-sm font-medium text-neutral-700">主题</label>
                        <input type="text" id="subject" name="subject" class="w-full px-4 py-3 border border-neutral-300 rounded-lg focus:ring-2 focus:ring-primary focus:border-primary transition-custom" placeholder="请输入留言主题">
                    </div>
                    
                    <div class="space-y-2 md:col-span-2">
                        <label for="message" class="block text-sm font-medium text-neutral-700">留言内容</label>
                        <textarea id="message" name="message" rows="5" class="w-full px-4 py-3 border border-neutral-300 rounded-lg focus:ring-2 focus:ring-primary focus:border-primary transition-custom resize-none" placeholder="请输入您的留言内容..."></textarea>
                    </div>
                    
                    <div class="md:col-span-2">
                        <button type="submit" class="px-6 py-3 bg-primary text-white rounded-lg hover:bg-primary/90 focus:ring-4 focus:ring-primary/30 font-medium transition-custom flex items-center">
                            <i class="fa-solid fa-paper-plane mr-2"></i>
                            发送留言
                        </button>
                    </div>
                </form>
            </div>
        </section>
    </main>

    <!-- 页脚 -->
    <footer class="bg-neutral-800 text-white py-12">
        <div class="container mx-auto px-4">
            <div class="grid grid-cols-1 md:grid-cols-4 gap-8">
                <div>
                    <div class="flex items-center space-x-2 mb-6">
                        <i class="fa-solid fa-flask text-primary text-2xl"></i>
                        <h3 class="text-xl font-bold">实验室名称</h3>
                    </div>
                    <p class="text-neutral-400 mb-6">专注于前沿科学研究与技术创新，致力于推动学科发展与社会进步。</p>
                    <div class="flex space-x-4">
                        <a href="#" class="text-neutral-400 hover:text-white transition-custom">
                            <i class="fa-brands fa-weibo text-xl"></i>
                        </a>
                        <a href="#" class="text-neutral-400 hover:text-white transition-custom">
                            <i class="fa-brands fa-weixin text-xl"></i>
                        </a>
                        <a href="#" class="text-neutral-400 hover:text-white transition-custom">
                            <i class="fa-brands fa-github text-xl"></i>
                        </a>
                        <a href="#" class="text-neutral-400 hover:text-white transition-custom">
                            <i class="fa-brands fa-twitter text-xl"></i>
                        </a>
                    </div>
                </div>
                
                <div>
                    <h4 class="text-lg font-bold mb-6">快速链接</h4>
                    <ul class="space-y-3">
                        <li><a href="#" class="text-neutral-400 hover:text-white transition-custom">首页</a></li>
                        <li><a href="#" class="text-neutral-400 hover:text-white transition-custom">关于我们</a></li>
                        <li><a href="#" class="text-neutral-400 hover:text-white transition-custom">研究方向</a></li>
                        <li><a href="#" class="text-neutral-400 hover:text-white transition-custom">研究成果</a></li>
                        <li><a href="#" class="text-neutral-400 hover:text-white transition-custom">团队成员</a></li>
                    </ul>
                </div>
                
                <div>
                    <h4 class="text-lg font-bold mb-6">联系方式</h4>
                    <ul class="space-y-3">
                        <li class="flex items-start">
                            <i class="fa-solid fa-envelope text-primary mt-1 mr-3"></i>
                            <span class="text-neutral-400">contact@example.com</span>
                        </li>
                        <li class="flex items-start">
                            <i class="fa-solid fa-phone text-primary mt-1 mr-3"></i>
                            <span class="text-neutral-400">+86 10 12345678</span>
                        </li>
                        <li class="flex items-start">
                            <i class="fa-solid fa-map-marker-alt text-primary mt-1 mr-3"></i>
                            <span class="text-neutral-400">中国北京市海淀区中关村科技园区清华大学某某楼 XXXX 室</span>
                        </li>
                    </ul>
                </div>
                
                <div>
                    <h4 class="text-lg font-bold mb-6">关注我们</h4>
                    <p class="text-neutral-400 mb-4">扫描二维码关注我们的微信公众号</p>
                    <div class="bg-white p-2 inline-block rounded">
                        <img src="https://picsum.photos/120/120" alt="微信公众号二维码" class="w-24 h-24 object-cover">
                    </div>
                </div>
            </div>
            
            <div class="border-t border-neutral-700 mt-12 pt-8 text-center text-neutral-500">
                <p>© 2025 实验室名称. 保留所有权利.</p>
            </div>
        </div>
    </footer>

    <script>
        // 导航栏滚动效果
        const navbar = document.getElementById('navbar');
        window.addEventListener('scroll', () => {
            if (window.scrollY > 50) {
                navbar.classList.add('py-2', 'shadow-lg', 'bg-white/95', 'backdrop-blur-sm');
                navbar.classList.remove('py-3', 'shadow-md');
            } else {
                navbar.classList.add('py-3', 'shadow-md');
                navbar.classList.remove('py-2', 'shadow-lg', 'bg-white/95', 'backdrop-blur-sm');
            }
        });

        // 移动端菜单切换
        const menuBtn = document.getElementById('menuBtn');
        const mobileMenu = document.getElementById('mobileMenu');
        menuBtn.addEventListener('click', () => {
            mobileMenu.classList.toggle('hidden');
            menuBtn.innerHTML = mobileMenu.classList.contains('hidden') 
                ? '<i class="fa-solid fa-bars"></i>' 
                : '<i class="fa-solid fa-times"></i>';
        });

        // 地图切换
        const mapTabs = document.querySelectorAll('.map-tab');
        mapTabs.forEach(tab => {
            tab.addEventListener('click', () => {
                // 移除所有选项卡的活跃状态
                mapTabs.forEach(t => {
                    t.classList.remove('text-primary', 'border-primary');
                    t.classList.add('text-neutral-500', 'hover:text-neutral-700');
                });
                
                // 添加当前选项卡的活跃状态
                tab.classList.remove('text-neutral-500', 'hover:text-neutral-700');
                tab.classList.add('text-primary', 'border-b-2', 'border-primary');
                
                // 隐藏所有地图
                document.querySelectorAll('.map-container').forEach(map => {
                    map.classList.add('hidden');
                });
                
                // 显示当前地图
                const mapId = tab.getAttribute('data-map') + 'Map';
                document.getElementById(mapId).classList.remove('hidden');
            });
        });

        // 表单提交处理
        const contactForm = document.querySelector('form');
        contactForm.addEventListener('submit', (e) => {
            e.preventDefault();
            // 这里可以添加表单验证和提交逻辑
            alert('留言已提交，我们将尽快回复您！');
            contactForm.reset();
        });

        // 平滑滚动
        document.querySelectorAll('a[href^="#"]').forEach(anchor => {
            anchor.addEventListener('click', function (e) {
                e.preventDefault();
                const targetId = this.getAttribute('href');
                if (targetId === '#') return;
                
                const targetElement = document.querySelector(targetId);
                if (targetElement) {
                    window.scrollTo({
                        top: targetElement.offsetTop - 80,
                        behavior: 'smooth'
                    });
                    
                    // 如果是在移动端，点击导航链接后关闭菜单
                    if (window.innerWidth < 768) {
                        mobileMenu.classList.add('hidden');
                        menuBtn.innerHTML = '<i class="fa-solid fa-bars"></i>';
                    }
                }
            });
        });
    </script>
</body>
</html>
    