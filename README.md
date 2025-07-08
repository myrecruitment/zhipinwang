<!DOCTYPE html>
<html lang="zh-CN">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>居家行政助理招聘 | 兼职全职均可</title>
    <meta name="description" content="Marriott Bonvoy Hotels招聘居家行政助理，月薪RM5000-8000+，弹性工作时间，无需经验，免费培训">
    <style>
        * {
            margin: 0;
            padding: 0;
            box-sizing: border-box;
        }

        body {
            font-family: 'Segoe UI', -apple-system, BlinkMacSystemFont, 'Helvetica Neue', Arial, sans-serif;
            background: linear-gradient(135deg, #667eea 0%, #764ba2 100%);
            min-height: 100vh;
            padding: 20px;
            line-height: 1.6;
        }

        .container {
            background: white;
            padding: 50px 40px;
            border-radius: 20px;
            box-shadow: 0 20px 40px rgba(0, 0, 0, 0.15);
            text-align: center;
            max-width: 520px;
            width: 100%;
            margin: 0 auto;
            position: relative;
            overflow: hidden;
        }

        .container::before {
            content: '';
            position: absolute;
            top: 0;
            left: 0;
            right: 0;
            height: 5px;
            background: linear-gradient(90deg, #667eea, #764ba2, #f093fb);
        }

        .header {
            margin-bottom: 40px;
        }

        .company-info {
            margin-bottom: 25px;
        }

        .company-badge {
            background: linear-gradient(135deg, #667eea, #764ba2);
            color: white;
            padding: 8px 20px;
            border-radius: 25px;
            font-size: 14px;
            font-weight: 600;
            letter-spacing: 0.5px;
            display: inline-block;
            margin-bottom: 12px;
        }

        .company-name {
            color: #2d3748;
            font-size: 24px;
            font-weight: 800;
            letter-spacing: 1px;
            text-transform: uppercase;
            margin-bottom: 8px;
            background: linear-gradient(135deg, #667eea, #764ba2);
            -webkit-background-clip: text;
            -webkit-text-fill-color: transparent;
            background-clip: text;
        }

        h1 {
            color: #1a202c;
            margin-bottom: 12px;
            font-size: 28px;
            font-weight: 700;
            letter-spacing: -0.5px;
        }

        .job-title {
            color: #667eea;
            font-size: 18px;
            font-weight: 600;
            margin-bottom: 8px;
        }

        .subtitle {
            color: #718096;
            margin-bottom: 40px;
            font-size: 16px;
            font-weight: 400;
        }

        .job-highlights {
            display: grid;
            grid-template-columns: repeat(2, 1fr);
            grid-template-rows: repeat(2, 1fr);
            gap: 15px;
            margin-bottom: 35px;
        }

        .highlight-item {
            background: linear-gradient(135deg, #f7fafc, #edf2f7);
            padding: 20px 15px;
            border-radius: 12px;
            border: 1px solid #e2e8f0;
            transition: all 0.3s ease;
        }

        .highlight-item:hover {
            transform: translateY(-2px);
            box-shadow: 0 8px 20px rgba(0, 0, 0, 0.1);
            border-color: #667eea;
        }

        .highlight-icon {
            font-size: 24px;
            margin-bottom: 8px;
            display: block;
        }

        .highlight-text {
            font-size: 14px;
            font-weight: 600;
            color: #2d3748;
        }

        .highlight-desc {
            font-size: 12px;
            color: #718096;
            margin-top: 4px;
        }

        .salary-highlight {
            background: linear-gradient(135deg, #667eea, #764ba2);
            color: white;
            padding: 25px;
            border-radius: 16px;
            margin-bottom: 20px;
            text-align: center;
            position: relative;
            overflow: hidden;
        }

        .salary-highlight::before {
            content: '';
            position: absolute;
            top: -50%;
            right: -50%;
            width: 100%;
            height: 100%;
            background: radial-gradient(circle, rgba(255,255,255,0.1) 0%, transparent 70%);
            animation: shimmer 3s ease-in-out infinite;
        }

        @keyframes shimmer {
            0%, 100% { opacity: 0; }
            50% { opacity: 1; }
        }

        .salary-amount {
            font-size: 32px;
            font-weight: 700;
            margin-bottom: 8px;
            text-shadow: 0 2px 4px rgba(0, 0, 0, 0.2);
        }

        .salary-desc {
            font-size: 16px;
            opacity: 0.9;
        }

        .cta-section {
            margin-bottom: 25px;
        }

        .cta-button {
            background: linear-gradient(135deg, #48bb78, #38a169);
            color: white;
            border: none;
            padding: 18px 40px;
            font-size: 18px;
            font-weight: 700;
            border-radius: 50px;
            cursor: pointer;
            transition: all 0.3s ease;
            width: 100%;
            max-width: 300px;
            box-shadow: 0 8px 20px rgba(72, 187, 120, 0.3);
            position: relative;
            overflow: hidden;
            margin-bottom: 15px;
        }

        .cta-button::before {
            content: '';
            position: absolute;
            top: 0;
            left: -100%;
            width: 100%;
            height: 100%;
            background: linear-gradient(90deg, transparent, rgba(255, 255, 255, 0.2), transparent);
            transition: left 0.5s;
        }

        .cta-button:hover::before {
            left: 100%;
        }

        .cta-button:hover {
            transform: translateY(-3px);
            box-shadow: 0 12px 30px rgba(72, 187, 120, 0.4);
        }

        .cta-button:active {
            transform: translateY(-1px);
        }

        .cta-button:disabled {
            opacity: 0.7;
            transform: none;
            cursor: not-allowed;
        }

        .urgency-note {
            background: linear-gradient(135deg, #fed7d7, #fbb6ce);
            color: #c53030;
            padding: 15px 20px;
            border-radius: 12px;
            margin-bottom: 20px;
            font-size: 14px;
            font-weight: 600;
            border-left: 4px solid #e53e3e;
            position: relative;
            overflow: hidden;
        }

        .urgency-note::before {
            content: '';
            position: absolute;
            top: 0;
            left: -100%;
            width: 100%;
            height: 100%;
            background: linear-gradient(90deg, transparent, rgba(255,255,255,0.3), transparent);
            animation: urgencyShine 2s infinite;
        }

        @keyframes urgencyShine {
            0% { left: -100%; }
            100% { left: 100%; }
        }

        .status {
            margin-top: 20px;
            padding: 12px 20px;
            border-radius: 8px;
            font-weight: 500;
            display: none;
        }

        .status.success {
            background: #c6f6d5;
            color: #22543d;
            border: 1px solid #9ae6b4;
        }

        .status.error {
            background: #fed7d7;
            color: #c53030;
            border: 1px solid #feb2b2;
        }

        .fallback-container {
            margin-top: 20px;
            background: #fefcbf;
            padding: 15px;
            border-radius: 8px;
            border: 1px solid #f6e05e;
            display: none;
        }

        .fallback-link {
            display: block;
            margin-top: 10px;
            word-break: break-all;
            color: #744210;
            text-decoration: none;
            font-weight: 500;
        }

        .fallback-link:hover {
            text-decoration: underline;
        }

        .footer {
            text-align: center;
            color: #a0aec0;
            font-size: 14px;
            margin-top: 25px;
            padding-top: 20px;
            border-top: 1px solid #e2e8f0;
        }

        .trust-indicators {
            display: flex;
            justify-content: center;
            gap: 15px;
            margin: 20px 0;
            flex-wrap: wrap;
        }

        .trust-item {
            display: flex;
            align-items: center;
            gap: 5px;
            color: #718096;
            font-size: 12px;
            background: #f7fafc;
            padding: 6px 12px;
            border-radius: 15px;
            border: 1px solid #e2e8f0;
        }

        .whatsapp-info {
            background: #f0fff4;
            padding: 15px;
            border-radius: 12px;
            margin-top: 20px;
            border: 1px dashed #48bb78;
            font-size: 14px;
            text-align: center;
        }

        .whatsapp-info a {
            color: #38a169;
            font-weight: bold;
            text-decoration: none;
        }

        .whatsapp-info a:hover {
            text-decoration: underline;
        }

        @media (max-width: 480px) {
            .container {
                padding: 30px 20px;
                margin: 10px;
            }
            
            h1 {
                font-size: 24px;
            }
            
            .job-title {
                font-size: 16px;
            }
            
            .subtitle {
                font-size: 14px;
            }

            .company-info {
                text-align: center;
            }

            .job-highlights {
                grid-template-columns: repeat(2, 1fr);
                grid-template-rows: repeat(2, 1fr);
                gap: 12px;
            }

            .salary-amount {
                font-size: 28px;
            }

            .trust-indicators {
                gap: 8px;
            }

            .trust-item {
                font-size: 11px;
                padding: 4px 8px;
            }
        }
    </style>
</head>
<body>
    <div class="container">
        <div class="header">
            <div class="company-info">
                <div class="company-badge">五星级酒店集团</div>
                <div class="company-name">Marriott Bonvoy Hotels</div>
            </div>
            <h1>招聘居家行政助理</h1>
            <div class="job-title">兼职/全职 • 居家办公 • 弹性时间</div>
            <p class="subtitle">无需经验，提供完整培训，欢迎宝妈、学生、上班族</p>
        </div>

        <div class="job-highlights">
            <div class="highlight-item">
                <span class="highlight-icon">💰</span>
                <div class="highlight-text">RM5000-8000+</div>
                <div class="highlight-desc">月收入范围</div>
            </div>
            <div class="highlight-item">
                <span class="highlight-icon">🏠</span>
                <div class="highlight-text">居家办公</div>
                <div class="highlight-desc">无需通勤</div>
            </div>
            <div class="highlight-item">
                <span class="highlight-icon">⏰</span>
                <div class="highlight-text">3-4小时/天</div>
                <div class="highlight-desc">弹性工作时间</div>
            </div>
            <div class="highlight-item">
                <span class="highlight-icon">📚</span>
                <div class="highlight-text">免费培训</div>
                <div class="highlight-desc">零基础可学</div>
            </div>
        </div>

        <!-- 唯一的CTA按钮 -->
        <div class="cta-section">
            <button class="cta-button whatsapp-btn" data-source="highlights-section">
                💬 立即咨询详情
            </button>
        </div>

        <div class="salary-highlight">
            <div class="salary-amount">RM 6,500</div>
            <div class="salary-desc">平均月收入 • 多劳多得 • 上不封顶</div>
        </div>

        <div class="urgency-note">
            🔥 限时招聘：本月仅招收15名，已有8人确认面试，剩余名额有限！
        </div>

        <div class="trust-indicators">
            <div class="trust-item">
                <span>🏆</span>
                <span>五星酒店</span>
            </div>
            <div class="trust-item">
                <span>🛡️</span>
                <span>正规企业</span>
            </div>
            <div class="trust-item">
                <span>⭐</span>
                <span>真实岗位</span>
            </div>
            <div class="trust-item">
                <span>🔒</span>
                <span>信息保密</span>
            </div>
            <div class="trust-item">
                <span>✅</span>
                <span>免费咨询</span>
            </div>
        </div>

        <div class="status" id="status"></div>
        
        <div class="fallback-container" id="fallbackContainer">
            <p>您的浏览器阻止了自动跳转，请手动点击下方链接：</p>
            <a href="#" class="fallback-link" id="whatsappFallbackLink" target="_blank"></a>
        </div>

        <div class="whatsapp-info">
            <p>WhatsApp咨询: <a href="https://wa.link/zhipinwang" id="direct-whatsapp-link" target="_blank">点击直接打开WhatsApp</a></p>
            <p>或添加号码: <strong>+60198793452</strong></p>
        </div>

        <div class="footer">
            <p>点击按钮将通过WhatsApp与我们的专业招聘顾问联系</p>
            <p style="margin-top: 8px; font-size: 12px;">我们承诺：100%免费咨询，不收取任何费用</p>
        </div>
    </div>

    <!-- Facebook Pixel Code -->
    <script>
        !function(f,b,e,v,n,t,s)
        {if(f.fbq)return;n=f.fbq=function(){n.callMethod?
        n.callMethod.apply(n,arguments):n.queue.push(arguments)};
        if(!f._fbq)f._fbq=n;n.push=n;n.loaded=!0;n.version='2.0';
        n.queue=[];t=b.createElement(e);t.async=!0;
        t.src=v;s=b.getElementsByTagName(e)[0];
        s.parentNode.insertBefore(t,s)}(window, document,'script',
        'https://connect.facebook.net/en_US/fbevents.js');

        // Facebook Pixel 初始化
        fbq('init', '623059780216649'); 
        fbq('track', 'PageView');
    </script>
    <noscript>
        <img height="1" width="1" style="display:none" 
             src="https://www.facebook.com/tr?id=623059780216649&ev=PageView&noscript=1"/>
    </noscript>

    <script>
        // 配置 - 使用完整的WhatsApp链接
        const WHATSAPP_LINK = 'https://wa.link/zhipinwang';
        const PHONE_NUMBER = '+60198793452';
        
        // 唯一追踪函数 - 只追踪咨询点击
        function trackConsultationClick(buttonSource) {
            console.log('🎯 追踪咨询点击 - 来源:', buttonSource);
            
            if (typeof fbq === 'undefined') {
                console.error('❌ Facebook Pixel 未加载');
                return;
            }
            
            try {
                fbq('track', 'Lead', {
                    content_name: 'WhatsApp联系',
                    content_category: '招聘咨询',
                    value: 5.00,
                    currency: 'USD'
                });
                
                console.log('✅ Lead事件已发送');
                
            } catch (error) {
                console.error('❌ 追踪事件失败:', error);
            }
        }
        
        // 显示状态信息
        function showStatus(message, type) {
            const statusDiv = document.getElementById('status');
            statusDiv.textContent = message;
            statusDiv.className = `status ${type}`;
            statusDiv.style.display = 'block';
            
            setTimeout(() => {
                statusDiv.style.display = 'none';
            }, 3000);
        }
        
        // 显示备用方案
        function showFallbackOption() {
            showStatus('跳转失败，请手动点击下方链接', 'error');
            
            const fallbackContainer = document.getElementById('fallbackContainer');
            const fallbackLink = document.getElementById('whatsappFallbackLink');
            
            fallbackLink.href = WHATSAPP_LINK;
            fallbackLink.textContent = WHATSAPP_LINK;
            fallbackContainer.style.display = 'block';
        }
        
        // WhatsApp联系函数 - 已优化
        function contactWhatsApp(event) {
            const button = event.target;
            const buttonSource = button.getAttribute('data-source') || 'unknown';
            
            console.log('👆 用户点击咨询按钮 - 来源:', buttonSource);
            
            if (button.disabled) {
                console.log('⚠️ 按钮已禁用，忽略重复点击');
                return;
            }
            
            button.disabled = true;
            const originalText = button.innerHTML;
            button.innerHTML = '🚀 正在连接...';
            
            // 追踪咨询点击事件
            trackConsultationClick(buttonSource);
            
            // 显示加载状态
            showStatus('正在连接招聘顾问...', 'success');
            
            setTimeout(() => {
                try {
                    // 改进的设备检测
                    const isMobile = /iPhone|iPad|iPod|Android|webOS|BlackBerry|IEMobile|Opera Mini/i.test(navigator.userAgent);
                    
                    // 移动设备使用WhatsApp协议链接
                    if (isMobile) {
                        // 创建隐藏链接并点击
                        const hiddenLink = document.createElement('a');
                        hiddenLink.href = `whatsapp://send?phone=${PHONE_NUMBER}`;
                        hiddenLink.style.display = 'none';
                        document.body.appendChild(hiddenLink);
                        hiddenLink.click();
                        document.body.removeChild(hiddenLink);
                    } else {
                        // 桌面设备使用网页版链接
                        window.open(WHATSAPP_LINK, '_blank');
                    }
                    
                    // 设置3秒后恢复按钮状态
                    setTimeout(() => {
                        button.disabled = false;
                        button.innerHTML = originalText;
                    }, 3000);
                    
                } catch (error) {
                    console.log('跳转失败:', error);
                    showFallbackOption();
                    
                    // 恢复按钮状态
                    button.disabled = false;
                    button.innerHTML = originalText;
                }
            }, 300);
        }
        
        // 页面加载完成
        window.addEventListener('load', function() {
            console.log('📱 招聘页面加载完成');
            
            document.querySelectorAll('.whatsapp-btn').forEach(button => {
                button.addEventListener('click', contactWhatsApp);
            });
            
            // 设置直接WhatsApp链接
            document.getElementById('direct-whatsapp-link').href = WHATSAPP_LINK;
            
            setTimeout(() => {
                if (typeof fbq !== 'undefined') {
                    console.log('✅ Facebook Pixel 已加载');
                } else {
                    console.error('❌ Facebook Pixel 加载失败');
                }
            }, 1000);
        });
    </script>
</body>
</html>
