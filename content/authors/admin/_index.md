---
title: Chunzheng Zhu
role: Ph.D. Student
bio:
interests:
  - AI Agents
  - Multimodal Large Language Models
  - Reinforcement Learning
  - Medical Image Analysis
  - Image Quality Assessment
  - Brain-Computer Interface
social:
  - icon: envelope
    icon_pack: fas
    link: mailto:zhuchzh@hnu.edu.cn
  - icon: github
    icon_pack: fab
    link: https://github.com/zhcz328/
  - icon: graduation-cap
    icon_pack: fas
    link: https://scholar.google.com/citations?user=HsJamBgAAAAJ&hl=zh-CN
  - icon: weixin
    icon_pack: fab
    label: "WeChat"
    link: "/authors/admin/#wechat"
# - icon: cv
#   icon_pack: ai
#   link: uploads/resume.pdf
organizations:
  - name: Hunan University
    url: https://www.hnu.edu.cn/
education:
  courses:
    - course: Ph.D. in Computer Science and Technology
      institution: Hunan University
      year: 2022.09 - 2027.06
    - course: B.Eng. in Data Science and Big Data Technology
      institution: Minzu University of China
      year: 2018.09 - 2022.06

email: ""
superuser: true
highlight_name: true
---

I am a Ph.D. student in Computer Science and Technology at Hunan University. My research focuses on AI agents, multimodal large language models, reinforcement learning, medical image analysis, and brain-computer interfaces.

<p class="bio-opportunity-callout">Expected PhD graduation: June 2027. I am open to roles in industry and academic positions, including postdoctoral fellowships. Welcome to reach out for opportunities and collaborations.</p>


<!-- WeChat modal (hidden by default) -->
<div id="wechat-modal" style="display:none;position:fixed;inset:0;z-index:2000;align-items:center;justify-content:center;">
  <div id="wechat-modal-backdrop" style="position:fixed;inset:0;background:rgba(0,0,0,0.5);"></div>
  <div style="position:relative;max-width:360px;width:90%;margin:0 auto;background:#fff;border-radius:10px;padding:1rem;box-shadow:0 6px 30px rgba(0,0,0,0.2);z-index:2001;text-align:center;">
    <button id="wechat-modal-close" aria-label="Close" style="position:absolute;right:8px;top:8px;background:none;border:none;font-size:1.2rem;cursor:pointer;">✕</button>
    <h3 style="margin-top:0.2rem;">WeChat</h3>
    <p style="color:#555;margin:0.25rem 0 0.75rem;">扫码添加我为微信好友，或手动添加：<strong>zhchzh183</strong></p>
    <img src="/uploads/wechat_qr.png" alt="WeChat QR" style="max-width:260px;width:70%;height:auto;border-radius:8px;box-shadow:0 2px 10px rgba(0,0,0,0.12);" />
  </div>
</div>

<script>
// Show modal when clicking social WeChat icon links
(function(){
  function showWechatModal(e){
    if(e) e.preventDefault();
    var modal = document.getElementById('wechat-modal');
    if(modal) modal.style.display = 'flex';
  }
  function hideWechatModal(){
    var modal = document.getElementById('wechat-modal');
    if(modal) modal.style.display = 'none';
  }
  // Attach to any anchor that links to the wechat anchor or has a weixin icon
  document.addEventListener('DOMContentLoaded', function(){
    // anchors linking to the wechat anchor
    var anchors = Array.from(document.querySelectorAll('a[href="/authors/admin/#wechat"], a[href="#wechat"]'));
    anchors.forEach(function(a){ a.addEventListener('click', showWechatModal); });

    // also attach to any element containing a font-awesome weixin icon
    var faIcons = Array.from(document.querySelectorAll('i.fab.fa-weixin, i.fa-weixin'));
    faIcons.forEach(function(icon){
      var parent = icon.closest('a');
      if(parent) parent.addEventListener('click', showWechatModal);
    });

    // close handlers
    var backdrop = document.getElementById('wechat-modal-backdrop');
    if(backdrop) backdrop.addEventListener('click', hideWechatModal);
    var btn = document.getElementById('wechat-modal-close');
    if(btn) btn.addEventListener('click', hideWechatModal);
    document.addEventListener('keydown', function(e){ if(e.key === 'Escape') hideWechatModal(); });
  });
})();
</script>

