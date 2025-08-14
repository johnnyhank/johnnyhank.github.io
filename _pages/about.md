---
permalink: /
title: "About me"
author_profile: true
redirect_from: 
  - /about/
  - /about.html
---

<style>
.academic-profile {
  max-width: 100%;
  line-height: 1.8;
  color: #2c3e50;
  font-size: 1.05em;
  margin-bottom: 1em;
}

.intro-section {
  background: #fdfdfd;
  padding: 2em;
  margin: 0.5em 0 1em 0;
}

.quote-section {
  text-align: center;
  margin: 1em 0 0.5em 0;
  padding: 1.5em;
  background: #f8f9fa;
  border-left: 4px solid #6c757d;
  font-style: italic;
  color: #495057;
}

.quote-text {
  font-size: 1.05em;
  line-height: 1.7;
  margin-bottom: 0.8em;
  font-family: 'Georgia', 'Times New Roman', serif;
  font-weight: 300;
  letter-spacing: 0.3px;
  color: #2c3e50;
}

.quote-author {
  font-size: 0.8em;
  color: #6c757d;
  font-weight: 400;
  font-family: 'Helvetica Neue', Arial, sans-serif;
  letter-spacing: 0.5px;
  text-transform: uppercase;
}

.intro-section p {
  margin-bottom: 1em;
  text-align: justify;
}

.intro-section p:last-child {
  margin-bottom: 0;
}

.affiliation a {
  color: #2c3e50;
  text-decoration: none;
  font-weight: 600;
  border-bottom: 1px solid transparent;
  transition: border-bottom 0.2s ease;
}

.affiliation a:hover {
  border-bottom: 1px solid #34495e;
}

.research-section {
  margin: 1.5em 0;
}

.research-description {
  font-size: 1.1em;
  margin-bottom: 2em;
  text-align: justify;
  color: #2c3e50;
}

.cv-note {
  margin: 1.5em 0 0 0;
  padding: 1em 0 0.5em 0;
  border-top: 1px solid #e9ecef;
  font-style: italic;
  color: #6c757d;
  text-align: center;
}

.cv-note a {
  color: #495057;
  text-decoration: none;
  font-weight: 600;
  border-bottom: 1px dotted #6c757d;
}

.cv-note a:hover {
  color: #2c3e50;
  border-bottom: 1px solid #2c3e50;
}

@media (max-width: 768px) {
  .academic-profile {
    font-size: 1em;
  }
  
  .intro-section {
    padding: 1.5em;
    margin: 1.5em 0;
  }
  
  .quote-section {
    padding: 1em;
    margin: 0.8em 0 0.3em 0;
  }
  
  .quote-text {
    font-size: 0.95em;
    line-height: 1.6;
  }
  
  .quote-author {
    font-size: 0.7em;
  }
}

/* 彻底控制页面底部空白 */
html, body {
  height: auto !important;
  min-height: auto !important;
  max-height: none !important;
  overflow-x: hidden;
}

body {
  margin: 0 !important;
  padding: 0 !important;
}

.page {
  min-height: auto !important;
  height: auto !important;
}

.archive {
  min-height: auto !important;
  height: auto !important;
  padding-bottom: 2em !important;
}

.page__content {
  padding-bottom: 2em !important;
  min-height: auto !important;
  height: auto !important;
}

.initial-content {
  min-height: auto !important;
  height: auto !important;
}

#main {
  min-height: auto !important;
  height: auto !important;
}

.wrapper {
  min-height: auto !important;
  height: auto !important;
}

.layout--single {
  min-height: auto !important;
  height: auto !important;
}

/* 强制页面容器紧贴内容 */
.page__wrapper {
  min-height: auto !important;
  height: auto !important;
}

/* 如果有footer，确保它紧跟内容 */
.page__footer {
  margin-top: 2em !important;
  position: relative !important;
}

/* 移除可能的全局最小高度设置 */
* {
  min-height: auto !important;
}

*:not(.academic-profile):not(.intro-section):not(.quote-section):not(.research-section):not(.cv-note) {
  min-height: auto !important;
}
</style>

<div class="academic-profile">

<div class="quote-section">
<div class="quote-text">"The past is known, but fixed. The future is unknown, but shaped by design."</div>
<div class="quote-author">— In the spirits of Claude Shannon and Tao Yuanming</div>
</div>

<div class="intro-section">
<p>I am a fourth-year undergraduate student from the <span class="affiliation"><a href="https://icisee.sjtu.edu.cn/">School of Integrated Circuits (School of Information Science and Electronic Engineering)</a></span>, <span class="affiliation"><a href="https://www.sjtu.edu.cn">Shanghai Jiao Tong University</a></span>.</p>

<p>I am very fortunate to be guided by <strong><a href="https://icisee.sjtu.edu.cn/jiaoshiml/sunshu.html">Assoc. Prof. Shu Sun</a></strong> of <strong><a href="https://ee.sjtu.edu.cn/Show.aspx?infolb=94&infoid=346&flag=42">Institute of Wireless Communication Technology</a></strong>, Shanghai Jiao Tong University. I am going to start my Ph.D. in the <span class="affiliation"><a href="https://icisee.sjtu.edu.cn/">School of Integrated Circuits (School of Information Science and Electronic Engineering)</a></span>, <span class="affiliation"><a href="https://www.sjtu.edu.cn">Shanghai Jiao Tong University</a></span> in <strong>September 2026</strong>.</p>

<div class="research-section">
<p class="research-description">My research interests lie in the field of <strong>physical layer technologies in wireless communications</strong>, including <em>OTFS Modulation, Channel Modeling and Multiple Access</em>. I am also keen to explore the <strong>integration of artificial intelligence and wireless communication technologies</strong>, particularly leveraging machine learning techniques to optimize resource allocation and improve adaptive strategies. My goal is to contribute my knowledge toward the digital and intelligent evolution of wireless communications in the 6G era.</p>
</div>

<div class="cv-note">For detailed academic background and research experience, please refer to my <a href="../_pages/Lihan_Zheng_PhD_Application_CV.pdf">Curriculum Vitae</a>.</div>
</div>

<script>
// 彻底消除页面底部空白的强化解决方案
(function() {
    function forceRemoveBottomSpace() {
        // 等待页面完全加载
        setTimeout(function() {
            // 获取实际内容高度
            var mainContent = document.querySelector('.academic-profile') || 
                             document.querySelector('.page__content') || 
                             document.querySelector('#main') ||
                             document.body;
                             
            if (mainContent) {
                var contentHeight = mainContent.offsetHeight;
                var windowHeight = window.innerHeight;
                
                // 强制设置所有可能影响高度的元素
                var selectors = [
                    'html', 'body', '.page', '.archive', '#main', 
                    '.initial-content', '.page__content', '.wrapper',
                    '.layout--single', '.page__wrapper', '.masthead',
                    '.page__hero', '.page__hero--overlay'
                ];
                
                selectors.forEach(function(selector) {
                    var elements = document.querySelectorAll(selector);
                    elements.forEach(function(element) {
                        if (element) {
                            element.style.setProperty('height', 'auto', 'important');
                            element.style.setProperty('min-height', 'auto', 'important');
                            element.style.setProperty('max-height', 'none', 'important');
                        }
                    });
                });
                
                // 特别处理 body 和 html
                document.body.style.setProperty('margin', '0', 'important');
                document.body.style.setProperty('padding', '0', 'important');
                document.documentElement.style.setProperty('height', 'auto', 'important');
                document.documentElement.style.setProperty('min-height', 'auto', 'important');
                
                // 如果内容高度远小于窗口高度，强制调整
                if (windowHeight - contentHeight > 200) {
                    document.body.style.setProperty('height', (contentHeight + 100) + 'px', 'important');
                    document.documentElement.style.setProperty('height', (contentHeight + 100) + 'px', 'important');
                }
                
                // 移除任何可能的固定高度样式
                var allElements = document.querySelectorAll('*');
                for (var i = 0; i < allElements.length; i++) {
                    var element = allElements[i];
                    var computedStyle = window.getComputedStyle(element);
                    if (computedStyle.minHeight && computedStyle.minHeight.indexOf('vh') > -1) {
                        element.style.setProperty('min-height', 'auto', 'important');
                    }
                }
            }
        }, 100);
    }
    
    // 多次执行以确保生效
    document.addEventListener('DOMContentLoaded', forceRemoveBottomSpace);
    window.addEventListener('load', forceRemoveBottomSpace);
    
    // 延迟执行，确保所有脚本都加载完毕
    setTimeout(forceRemoveBottomSpace, 500);
    setTimeout(forceRemoveBottomSpace, 1000);
    setTimeout(forceRemoveBottomSpace, 2000);
    
    // 窗口大小改变时重新调整
    window.addEventListener('resize', function() {
        setTimeout(forceRemoveBottomSpace, 100);
    });
})();
</script>