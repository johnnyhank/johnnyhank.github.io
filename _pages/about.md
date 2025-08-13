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
  font-size: 0.9em;
  line-height: 1.6;
  margin-bottom: 0.5em;
}

.quote-author {
  font-size: 0.7em;
  color: #6c757d;
  font-weight: 500;
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
    font-size: 0.85em;
  }
  
  .quote-author {
    font-size: 0.65em;
  }
}

/* 控制页面底部空白 */
body {
  min-height: auto !important;
}

.page {
  min-height: auto !important;
}

.archive {
  min-height: auto !important;
  padding-bottom: 2em !important;
}

/* 额外的布局控制 */
.page__content {
  padding-bottom: 2em !important;
}

.initial-content {
  min-height: auto !important;
}

#main {
  min-height: auto !important;
}

/* 如果有footer，确保它紧跟内容 */
.page__footer {
  margin-top: 2em !important;
}
</style>

<div class="academic-profile">

<div class="quote-section">
<div class="quote-text">"The past is known, but fixed. The future is unknown, but shaped by design."</div>
<div class="quote-author">— In the spirits of Claude Shannon and Tao Yuanming</div>
</div>

<div class="intro-section">
<p>I am a fourth-year undergraduate student from the <span class="affiliation"><a href="https://icisee.sjtu.edu.cn/">School of Integrated Circuits (School of Information Science and Electronic Engineering)</a></span>, <span class="affiliation"><a href="https://www.sjtu.edu.cn">Shanghai Jiao Tong University</a></span>.</p>

<p>I am very fortunate to be guided by <strong><a href="https://icisee.sjtu.edu.cn/jiaoshiml/sunshu.html">Assoc. Prof. Shu Sun</a></strong> of <a href="https://ee.sjtu.edu.cn/Show.aspx?infolb=94&infoid=346&flag=42">Institute of Wireless Communication Technology</a>, Shanghai Jiao Tong University. I am going to start my Ph.D. in the <span class="affiliation"><a href="https://icisee.sjtu.edu.cn/">School of Integrated Circuits</a></span>, <span class="affiliation"><a href="https://www.sjtu.edu.cn">Shanghai Jiao Tong University</a></span> in <strong>September 2026</strong>.</p>

<div class="research-section">
<p class="research-description">My research interests lie in the field of <strong>physical layer technologies in wireless communications</strong>, including <em>OTFS Modulation, Channel Modeling and Multiple Access</em>. I am also keen to explore the <strong>integration of artificial intelligence and wireless communication technologies</strong>, particularly leveraging machine learning techniques to optimize resource allocation and improve adaptive strategies. My goal is to contribute my knowledge toward the digital and intelligent evolution of wireless communications in the 6G era.</p>
</div>

<div class="cv-note">For detailed academic background and research experience, please refer to my <a href="../_pages/Lihan_Zheng_PhD_Application_CV.pdf">Curriculum Vitae</a>.</div>
</div>

<script>
// 动态调整页面高度，消除底部空白
(function() {
    function adjustPageHeight() {
        // 获取页面内容的实际高度
        var content = document.querySelector('.academic-profile') || document.querySelector('.page__content') || document.body;
        var actualHeight = content.scrollHeight;
        
        // 找到可能导致额外高度的元素
        var elements = ['body', 'html', '.page', '.archive', '#main', '.initial-content', '.page__content'];
        
        elements.forEach(function(selector) {
            var element = document.querySelector(selector);
            if (element) {
                element.style.minHeight = 'auto';
                element.style.height = 'auto';
            }
        });
        
        // 如果页面仍然太高，强制设置body高度
        if (window.innerHeight > actualHeight + 100) {
            document.body.style.height = (actualHeight + 100) + 'px';
            document.documentElement.style.height = (actualHeight + 100) + 'px';
        }
    }
    
    // 页面加载完成后调整
    if (document.readyState === 'loading') {
        document.addEventListener('DOMContentLoaded', adjustPageHeight);
    } else {
        adjustPageHeight();
    }
    
    // 窗口大小改变时重新调整
    window.addEventListener('resize', adjustPageHeight);
})();
</script>