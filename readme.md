<div class="Box-sc-g0xbh4-0 bJMeLZ js-snippet-clipboard-copy-unpositioned" data-hpc="true"><article class="markdown-body entry-content container-lg" itemprop="text"><p align="center" dir="auto">
  </p><div class="markdown-heading" dir="auto"><h2 align="center" tabindex="-1" class="heading-element" dir="auto"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">带参考模仿的零样本图像编辑</font></font></h2><a id="user-content-zero-shot-image-editing-with-reference-imitation" class="anchor" aria-label="永久链接：使用参考模仿进行零样本图像编辑" href="#zero-shot-image-editing-with-reference-imitation"><svg class="octicon octicon-link" viewBox="0 0 16 16" version="1.1" width="16" height="16" aria-hidden="true"><path d="m7.775 3.275 1.25-1.25a3.5 3.5 0 1 1 4.95 4.95l-2.5 2.5a3.5 3.5 0 0 1-4.95 0 .751.751 0 0 1 .018-1.042.751.751 0 0 1 1.042-.018 1.998 1.998 0 0 0 2.83 0l2.5-2.5a2.002 2.002 0 0 0-2.83-2.83l-1.25 1.25a.751.751 0 0 1-1.042-.018.751.751 0 0 1-.018-1.042Zm-4.69 9.64a1.998 1.998 0 0 0 2.83 0l1.25-1.25a.751.751 0 0 1 1.042.018.751.751 0 0 1 .018 1.042l-1.25 1.25a3.5 3.5 0 1 1-4.95-4.95l2.5-2.5a3.5 3.5 0 0 1 4.95 0 .751.751 0 0 1-.018 1.042.751.751 0 0 1-1.042.018 1.998 1.998 0 0 0-2.83 0l-2.5 2.5a1.998 1.998 0 0 0 0 2.83Z"></path></svg></a></div>
  <p align="center" dir="auto">
    <a href="https://xavierchen34.github.io/" rel="nofollow"><strong><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">陈曦</font></font></strong></a><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">
    ·
    </font></font><a href="https://scholar.google.com.hk/citations?user=mZwJLeUAAAAJ&amp;hl=zh-CN" rel="nofollow"><strong><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">冯雨桐</font></font></strong></a><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">
    ·
    </font></font><a href="https://mengtingchen.github.io/" rel="nofollow"><strong><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">陈梦婷</font></font></strong></a><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">
    ·
    </font></font><a href="https://openreview.net/profile?id=~Yiyang_Wang2" rel="nofollow"><strong><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">王一阳</font></font></strong></a><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">
    ·
    </font></font><a href="https://jshilong.github.io/" rel="nofollow"><strong><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">张世龙</font></font></strong></a><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">
    ·
    </font></font><a href="https://scholar.google.com/citations?user=8zksQb4AAAAJ&amp;hl=zh-CN" rel="nofollow"><strong><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">刘宇</font></font></strong></a><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">
    ·
    </font></font><a href="https://shenyujun.github.io/" rel="nofollow"><strong><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">沈玉君</font></font></strong></a><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">
    ·
    </font></font><a href="https://hszhao.github.io/" rel="nofollow"><strong><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">赵恒双</font></font></strong></a>
    <font style="vertical-align: inherit;"><b><font style="vertical-align: inherit;">香港大学 |阿里巴巴集团 |蚂蚁集团</font></b></font><br>
    <br>
        <a href="https://arxiv.org/abs/2406.07547" rel="nofollow"><img src="https://camo.githubusercontent.com/2e33acf509d6bb03e9a339b55485730b2bb3ea3280b120d161c369aaeb4f09ec/68747470733a2f2f696d672e736869656c64732e696f2f62616467652f61725869762d4d696d696342727573682d726564" alt="论文 PDF" data-canonical-src="https://img.shields.io/badge/arXiv-MimicBrush-red" style="max-width: 100%;"></a>
        <a href="https://xavierchen34.github.io/MimicBrush-Page/" rel="nofollow"><img src="https://camo.githubusercontent.com/30223ac68bc94e703ea2956601c52b24e5ad26ccae3faa6836f6e616ff896112/68747470733a2f2f696d672e736869656c64732e696f2f62616467652f50726f6a6563745f506167652d4d696d696342727573682d677265656e" alt="项目页面" data-canonical-src="https://img.shields.io/badge/Project_Page-MimicBrush-green" style="max-width: 100%;"></a>
        <a href="https://modelscope.cn/studios/iic/mimicbrush-demo/summary" rel="nofollow"><img src="https://camo.githubusercontent.com/981edc24494dd7d6a54c66343589604be0b0a07198a8c49d381eb29a97ad905b/68747470733a2f2f696d672e736869656c64732e696f2f62616467652f4d6f64656c53636f70652d4d696d696342727573682d79656c6c6f77" data-canonical-src="https://img.shields.io/badge/ModelScope-MimicBrush-yellow" style="max-width: 100%;"></a>
        <a href="https://huggingface.co/spaces/xichenhku/MimicBrush" rel="nofollow"><img src="https://camo.githubusercontent.com/5762a687b24495afb299c2c0bc68674a2a7dfca9bda6ee444b9da7617d4223a6/68747470733a2f2f696d672e736869656c64732e696f2f62616467652f25463025394625413425393725323048756767696e67253230466163652d5370616365732d626c7565" data-canonical-src="https://img.shields.io/badge/%F0%9F%A4%97%20Hugging%20Face-Spaces-blue" style="max-width: 100%;"></a>
    <br>
    <b><font style="vertical-align: inherit;"></font></b>
  </p>
  <table align="center">
    <tbody><tr>
    <td>
      <a target="_blank" rel="noopener noreferrer" href="/ali-vilab/MimicBrush/blob/main/assets/teaser.png"><img src="/ali-vilab/MimicBrush/raw/main/assets/teaser.png" style="max-width: 100%;"></a>
    </td>
    </tr>
  </tbody></table>
<div class="markdown-heading" dir="auto"><h2 tabindex="-1" class="heading-element" dir="auto"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">消息</font></font></h2><a id="user-content-news" class="anchor" aria-label="固定链接：新闻" href="#news"><svg class="octicon octicon-link" viewBox="0 0 16 16" version="1.1" width="16" height="16" aria-hidden="true"><path d="m7.775 3.275 1.25-1.25a3.5 3.5 0 1 1 4.95 4.95l-2.5 2.5a3.5 3.5 0 0 1-4.95 0 .751.751 0 0 1 .018-1.042.751.751 0 0 1 1.042-.018 1.998 1.998 0 0 0 2.83 0l2.5-2.5a2.002 2.002 0 0 0-2.83-2.83l-1.25 1.25a.751.751 0 0 1-1.042-.018.751.751 0 0 1-.018-1.042Zm-4.69 9.64a1.998 1.998 0 0 0 2.83 0l1.25-1.25a.751.751 0 0 1 1.042.018.751.751 0 0 1 .018 1.042l-1.25 1.25a3.5 3.5 0 1 1-4.95-4.95l2.5-2.5a3.5 3.5 0 0 1 4.95 0 .751.751 0 0 1-.018 1.042.751.751 0 0 1-1.042.018 1.998 1.998 0 0 0-2.83 0l-2.5 2.5a1.998 1.998 0 0 0 0 2.83Z"></path></svg></a></div>
<ul dir="auto">
<li><strong><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">[2024.06.12]</font></font></strong><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">发布推理代码，本地gradio demo，在线demo。</font></font></li>
<li><strong><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">[Todo]</font></font></strong><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">发布我们的基准。</font></font></li>
</ul>
<div class="markdown-heading" dir="auto"><h2 tabindex="-1" class="heading-element" dir="auto"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">社区贡献</font></font></h2><a id="user-content-community-contributions" class="anchor" aria-label="永久链接：社区贡献" href="#community-contributions"><svg class="octicon octicon-link" viewBox="0 0 16 16" version="1.1" width="16" height="16" aria-hidden="true"><path d="m7.775 3.275 1.25-1.25a3.5 3.5 0 1 1 4.95 4.95l-2.5 2.5a3.5 3.5 0 0 1-4.95 0 .751.751 0 0 1 .018-1.042.751.751 0 0 1 1.042-.018 1.998 1.998 0 0 0 2.83 0l2.5-2.5a2.002 2.002 0 0 0-2.83-2.83l-1.25 1.25a.751.751 0 0 1-1.042-.018.751.751 0 0 1-.018-1.042Zm-4.69 9.64a1.998 1.998 0 0 0 2.83 0l1.25-1.25a.751.751 0 0 1 1.042.018.751.751 0 0 1 .018 1.042l-1.25 1.25a3.5 3.5 0 1 1-4.95-4.95l2.5-2.5a3.5 3.5 0 0 1 4.95 0 .751.751 0 0 1-.018 1.042.751.751 0 0 1-1.042.018 1.998 1.998 0 0 0-2.83 0l-2.5 2.5a1.998 1.998 0 0 0 0 2.83Z"></path></svg></a></div>
<p dir="auto"><a href="https://github.com/AIFSH/ComfyUI-MimicBrush"><font style="vertical-align: inherit;"></font></a><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">由</font><a href="https://github.com/AIFSH"><font style="vertical-align: inherit;">@AIFSH提供的</font></a><a href="https://github.com/AIFSH/ComfyUI-MimicBrush"><font style="vertical-align: inherit;">ComfyUI 版本</font></a></font><a href="https://github.com/AIFSH"><font style="vertical-align: inherit;"></font></a></p>
<div class="markdown-heading" dir="auto"><h2 tabindex="-1" class="heading-element" dir="auto"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">安装</font></font></h2><a id="user-content-installation" class="anchor" aria-label="固定链接：安装" href="#installation"><svg class="octicon octicon-link" viewBox="0 0 16 16" version="1.1" width="16" height="16" aria-hidden="true"><path d="m7.775 3.275 1.25-1.25a3.5 3.5 0 1 1 4.95 4.95l-2.5 2.5a3.5 3.5 0 0 1-4.95 0 .751.751 0 0 1 .018-1.042.751.751 0 0 1 1.042-.018 1.998 1.998 0 0 0 2.83 0l2.5-2.5a2.002 2.002 0 0 0-2.83-2.83l-1.25 1.25a.751.751 0 0 1-1.042-.018.751.751 0 0 1-.018-1.042Zm-4.69 9.64a1.998 1.998 0 0 0 2.83 0l1.25-1.25a.751.751 0 0 1 1.042.018.751.751 0 0 1 .018 1.042l-1.25 1.25a3.5 3.5 0 1 1-4.95-4.95l2.5-2.5a3.5 3.5 0 0 1 4.95 0 .751.751 0 0 1-.018 1.042.751.751 0 0 1-1.042.018 1.998 1.998 0 0 0-2.83 0l-2.5 2.5a1.998 1.998 0 0 0 0 2.83Z"></path></svg></a></div>
<p dir="auto"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">安装方式</font></font><code>conda</code><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">：</font></font></p>
<div class="highlight highlight-source-shell notranslate position-relative overflow-auto" dir="auto"><pre>conda env create -f environment.yaml
conda activate mimicbrush</pre><div class="zeroclipboard-container">
    <clipboard-copy aria-label="Copy" class="ClipboardButton btn btn-invisible js-clipboard-copy m-2 p-0 tooltipped-no-delay d-flex flex-justify-center flex-items-center" data-copy-feedback="Copied!" data-tooltip-direction="w" value="conda env create -f environment.yaml
conda activate mimicbrush" tabindex="0" role="button">
      <svg aria-hidden="true" height="16" viewBox="0 0 16 16" version="1.1" width="16" data-view-component="true" class="octicon octicon-copy js-clipboard-copy-icon">
    <path d="M0 6.75C0 5.784.784 5 1.75 5h1.5a.75.75 0 0 1 0 1.5h-1.5a.25.25 0 0 0-.25.25v7.5c0 .138.112.25.25.25h7.5a.25.25 0 0 0 .25-.25v-1.5a.75.75 0 0 1 1.5 0v1.5A1.75 1.75 0 0 1 9.25 16h-7.5A1.75 1.75 0 0 1 0 14.25Z"></path><path d="M5 1.75C5 .784 5.784 0 6.75 0h7.5C15.216 0 16 .784 16 1.75v7.5A1.75 1.75 0 0 1 14.25 11h-7.5A1.75 1.75 0 0 1 5 9.25Zm1.75-.25a.25.25 0 0 0-.25.25v7.5c0 .138.112.25.25.25h7.5a.25.25 0 0 0 .25-.25v-7.5a.25.25 0 0 0-.25-.25Z"></path>
</svg>
      <svg aria-hidden="true" height="16" viewBox="0 0 16 16" version="1.1" width="16" data-view-component="true" class="octicon octicon-check js-clipboard-check-icon color-fg-success d-none">
    <path d="M13.78 4.22a.75.75 0 0 1 0 1.06l-7.25 7.25a.75.75 0 0 1-1.06 0L2.22 9.28a.751.751 0 0 1 .018-1.042.751.751 0 0 1 1.042-.018L6 10.94l6.72-6.72a.75.75 0 0 1 1.06 0Z"></path>
</svg>
    </clipboard-copy>
  </div></div>
<p dir="auto"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">或者</font></font><code>pip</code><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">：</font></font></p>
<div class="highlight highlight-source-shell notranslate position-relative overflow-auto" dir="auto"><pre><span class="pl-c"><span class="pl-c">#</span>Python==3.8.5</span>
pip install -r requirements.txt</pre><div class="zeroclipboard-container">
    <clipboard-copy aria-label="Copy" class="ClipboardButton btn btn-invisible js-clipboard-copy m-2 p-0 tooltipped-no-delay d-flex flex-justify-center flex-items-center" data-copy-feedback="Copied!" data-tooltip-direction="w" value="#Python==3.8.5
pip install -r requirements.txt" tabindex="0" role="button">
      <svg aria-hidden="true" height="16" viewBox="0 0 16 16" version="1.1" width="16" data-view-component="true" class="octicon octicon-copy js-clipboard-copy-icon">
    <path d="M0 6.75C0 5.784.784 5 1.75 5h1.5a.75.75 0 0 1 0 1.5h-1.5a.25.25 0 0 0-.25.25v7.5c0 .138.112.25.25.25h7.5a.25.25 0 0 0 .25-.25v-1.5a.75.75 0 0 1 1.5 0v1.5A1.75 1.75 0 0 1 9.25 16h-7.5A1.75 1.75 0 0 1 0 14.25Z"></path><path d="M5 1.75C5 .784 5.784 0 6.75 0h7.5C15.216 0 16 .784 16 1.75v7.5A1.75 1.75 0 0 1 14.25 11h-7.5A1.75 1.75 0 0 1 5 9.25Zm1.75-.25a.25.25 0 0 0-.25.25v7.5c0 .138.112.25.25.25h7.5a.25.25 0 0 0 .25-.25v-7.5a.25.25 0 0 0-.25-.25Z"></path>
</svg>
      <svg aria-hidden="true" height="16" viewBox="0 0 16 16" version="1.1" width="16" data-view-component="true" class="octicon octicon-check js-clipboard-check-icon color-fg-success d-none">
    <path d="M13.78 4.22a.75.75 0 0 1 0 1.06l-7.25 7.25a.75.75 0 0 1-1.06 0L2.22 9.28a.751.751 0 0 1 .018-1.042.751.751 0 0 1 1.042-.018L6 10.94l6.72-6.72a.75.75 0 0 1 1.06 0Z"></path>
</svg>
    </clipboard-copy>
  </div></div>
<div class="markdown-heading" dir="auto"><h2 tabindex="-1" class="heading-element" dir="auto"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">下载检查点</font></font></h2><a id="user-content-download-checkpoints" class="anchor" aria-label="永久链接：下载检查点" href="#download-checkpoints"><svg class="octicon octicon-link" viewBox="0 0 16 16" version="1.1" width="16" height="16" aria-hidden="true"><path d="m7.775 3.275 1.25-1.25a3.5 3.5 0 1 1 4.95 4.95l-2.5 2.5a3.5 3.5 0 0 1-4.95 0 .751.751 0 0 1 .018-1.042.751.751 0 0 1 1.042-.018 1.998 1.998 0 0 0 2.83 0l2.5-2.5a2.002 2.002 0 0 0-2.83-2.83l-1.25 1.25a.751.751 0 0 1-1.042-.018.751.751 0 0 1-.018-1.042Zm-4.69 9.64a1.998 1.998 0 0 0 2.83 0l1.25-1.25a.751.751 0 0 1 1.042.018.751.751 0 0 1 .018 1.042l-1.25 1.25a3.5 3.5 0 1 1-4.95-4.95l2.5-2.5a3.5 3.5 0 0 1 4.95 0 .751.751 0 0 1-.018 1.042.751.751 0 0 1-1.042.018 1.998 1.998 0 0 0-2.83 0l-2.5 2.5a1.998 1.998 0 0 0 0 2.83Z"></path></svg></a></div>
<p dir="auto"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">下载 SD-1.5 和 SD-1.5-inpainting 检查点：</font></font></p>
<ul dir="auto">
<li><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">你可以从 HuggingFace </font></font><a href="https://huggingface.co/runwayml/stable-diffusion-v1-5" rel="nofollow"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">stable-diffusion-v1-5</font></font></a><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">和</font></font><a href="https://huggingface.co/runwayml/stable-diffusion-inpainting/" rel="nofollow"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">stable-diffusion-inpainting下载它们</font></font></a></li>
<li><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">但是，上面的 repo 包含许多不会使用的模型，我们在</font></font><a href="https://modelscope.cn/models/xichen/cleansd/" rel="nofollow"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">cleansd上提供了一个干净的版本</font></font></a></li>
</ul>
<p dir="auto"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">下载 MimicBrush 检查点以及 VAE、CLIP 编码器和深度模型</font></font></p>
<ul dir="auto">
<li><font style="vertical-align: inherit;"><a href="https://www.modelscope.cn/models/xichen/MimicBrush" rel="nofollow"><font style="vertical-align: inherit;">在 ModelScope xichen/MimicBrush</font></a><font style="vertical-align: inherit;">上下载权重</font></font><a href="https://www.modelscope.cn/models/xichen/MimicBrush" rel="nofollow"><font style="vertical-align: inherit;"></font></a></li>
<li><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">该模型很大，因为它包含两个 U-Nets。</font></font></li>
</ul>
<p dir="auto"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">您可以使用以下代码从 modelscope 下载它们</font></font></p>
<div class="highlight highlight-source-python notranslate position-relative overflow-auto" dir="auto"><pre><span class="pl-k">from</span> <span class="pl-s1">modelscope</span>.<span class="pl-s1">hub</span>.<span class="pl-s1">snapshot_download</span> <span class="pl-k">import</span> <span class="pl-s1">snapshot_download</span> <span class="pl-k">as</span> <span class="pl-s1">ms_snapshot_download</span>

<span class="pl-s1">sd_dir</span> <span class="pl-c1">=</span> <span class="pl-en">ms_snapshot_download</span>(<span class="pl-s">'xichen/cleansd'</span>, <span class="pl-s1">cache_dir</span><span class="pl-c1">=</span><span class="pl-s">'./modelscope'</span>)
<span class="pl-en">print</span>(<span class="pl-s">'=== Pretrained SD weights downloaded ==='</span>)
<span class="pl-s1">model_dir</span> <span class="pl-c1">=</span> <span class="pl-en">ms_snapshot_download</span>(<span class="pl-s">'xichen/MimicBrush'</span>, <span class="pl-s1">cache_dir</span><span class="pl-c1">=</span><span class="pl-s">'./modelscope'</span>)
<span class="pl-en">print</span>(<span class="pl-s">'=== MimicBrush weights downloaded ==='</span>)</pre><div class="zeroclipboard-container">
    <clipboard-copy aria-label="Copy" class="ClipboardButton btn btn-invisible js-clipboard-copy m-2 p-0 tooltipped-no-delay d-flex flex-justify-center flex-items-center" data-copy-feedback="Copied!" data-tooltip-direction="w" value="from modelscope.hub.snapshot_download import snapshot_download as ms_snapshot_download

sd_dir = ms_snapshot_download('xichen/cleansd', cache_dir='./modelscope')
print('=== Pretrained SD weights downloaded ===')
model_dir = ms_snapshot_download('xichen/MimicBrush', cache_dir='./modelscope')
print('=== MimicBrush weights downloaded ===')" tabindex="0" role="button">
      <svg aria-hidden="true" height="16" viewBox="0 0 16 16" version="1.1" width="16" data-view-component="true" class="octicon octicon-copy js-clipboard-copy-icon">
    <path d="M0 6.75C0 5.784.784 5 1.75 5h1.5a.75.75 0 0 1 0 1.5h-1.5a.25.25 0 0 0-.25.25v7.5c0 .138.112.25.25.25h7.5a.25.25 0 0 0 .25-.25v-1.5a.75.75 0 0 1 1.5 0v1.5A1.75 1.75 0 0 1 9.25 16h-7.5A1.75 1.75 0 0 1 0 14.25Z"></path><path d="M5 1.75C5 .784 5.784 0 6.75 0h7.5C15.216 0 16 .784 16 1.75v7.5A1.75 1.75 0 0 1 14.25 11h-7.5A1.75 1.75 0 0 1 5 9.25Zm1.75-.25a.25.25 0 0 0-.25.25v7.5c0 .138.112.25.25.25h7.5a.25.25 0 0 0 .25-.25v-7.5a.25.25 0 0 0-.25-.25Z"></path>
</svg>
      <svg aria-hidden="true" height="16" viewBox="0 0 16 16" version="1.1" width="16" data-view-component="true" class="octicon octicon-check js-clipboard-check-icon color-fg-success d-none">
    <path d="M13.78 4.22a.75.75 0 0 1 0 1.06l-7.25 7.25a.75.75 0 0 1-1.06 0L2.22 9.28a.751.751 0 0 1 .018-1.042.751.751 0 0 1 1.042-.018L6 10.94l6.72-6.72a.75.75 0 0 1 1.06 0Z"></path>
</svg>
    </clipboard-copy>
  </div></div>
<p dir="auto"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">或来自 Huggingface</font></font></p>
<div class="highlight highlight-source-python notranslate position-relative overflow-auto" dir="auto"><pre><span class="pl-k">from</span> <span class="pl-s1">huggingface_hub</span> <span class="pl-k">import</span> <span class="pl-s1">snapshot_download</span>
<span class="pl-en">snapshot_download</span>(<span class="pl-s1">repo_id</span><span class="pl-c1">=</span><span class="pl-s">"xichenhku/cleansd"</span>, <span class="pl-s1">local_dir</span><span class="pl-c1">=</span><span class="pl-s">"./cleansd"</span>)
<span class="pl-en">print</span>(<span class="pl-s">'=== Pretrained SD weights downloaded ==='</span>)
<span class="pl-en">snapshot_download</span>(<span class="pl-s1">repo_id</span><span class="pl-c1">=</span><span class="pl-s">"xichenhku/MimicBrush"</span>, <span class="pl-s1">local_dir</span><span class="pl-c1">=</span><span class="pl-s">"./MimicBrush"</span>)
<span class="pl-en">print</span>(<span class="pl-s">'=== MimicBrush weights downloaded ==='</span>)</pre><div class="zeroclipboard-container">
    <clipboard-copy aria-label="Copy" class="ClipboardButton btn btn-invisible js-clipboard-copy m-2 p-0 tooltipped-no-delay d-flex flex-justify-center flex-items-center" data-copy-feedback="Copied!" data-tooltip-direction="w" value="from huggingface_hub import snapshot_download
snapshot_download(repo_id=&quot;xichenhku/cleansd&quot;, local_dir=&quot;./cleansd&quot;)
print('=== Pretrained SD weights downloaded ===')
snapshot_download(repo_id=&quot;xichenhku/MimicBrush&quot;, local_dir=&quot;./MimicBrush&quot;)
print('=== MimicBrush weights downloaded ===')" tabindex="0" role="button">
      <svg aria-hidden="true" height="16" viewBox="0 0 16 16" version="1.1" width="16" data-view-component="true" class="octicon octicon-copy js-clipboard-copy-icon">
    <path d="M0 6.75C0 5.784.784 5 1.75 5h1.5a.75.75 0 0 1 0 1.5h-1.5a.25.25 0 0 0-.25.25v7.5c0 .138.112.25.25.25h7.5a.25.25 0 0 0 .25-.25v-1.5a.75.75 0 0 1 1.5 0v1.5A1.75 1.75 0 0 1 9.25 16h-7.5A1.75 1.75 0 0 1 0 14.25Z"></path><path d="M5 1.75C5 .784 5.784 0 6.75 0h7.5C15.216 0 16 .784 16 1.75v7.5A1.75 1.75 0 0 1 14.25 11h-7.5A1.75 1.75 0 0 1 5 9.25Zm1.75-.25a.25.25 0 0 0-.25.25v7.5c0 .138.112.25.25.25h7.5a.25.25 0 0 0 .25-.25v-7.5a.25.25 0 0 0-.25-.25Z"></path>
</svg>
      <svg aria-hidden="true" height="16" viewBox="0 0 16 16" version="1.1" width="16" data-view-component="true" class="octicon octicon-check js-clipboard-check-icon color-fg-success d-none">
    <path d="M13.78 4.22a.75.75 0 0 1 0 1.06l-7.25 7.25a.75.75 0 0 1-1.06 0L2.22 9.28a.751.751 0 0 1 .018-1.042.751.751 0 0 1 1.042-.018L6 10.94l6.72-6.72a.75.75 0 0 1 1.06 0Z"></path>
</svg>
    </clipboard-copy>
  </div></div>
<div class="markdown-heading" dir="auto"><h2 tabindex="-1" class="heading-element" dir="auto"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">Gradio 演示</font></font></h2><a id="user-content-gradio-demo" class="anchor" aria-label="永久链接：Gradio 演示" href="#gradio-demo"><svg class="octicon octicon-link" viewBox="0 0 16 16" version="1.1" width="16" height="16" aria-hidden="true"><path d="m7.775 3.275 1.25-1.25a3.5 3.5 0 1 1 4.95 4.95l-2.5 2.5a3.5 3.5 0 0 1-4.95 0 .751.751 0 0 1 .018-1.042.751.751 0 0 1 1.042-.018 1.998 1.998 0 0 0 2.83 0l2.5-2.5a2.002 2.002 0 0 0-2.83-2.83l-1.25 1.25a.751.751 0 0 1-1.042-.018.751.751 0 0 1-.018-1.042Zm-4.69 9.64a1.998 1.998 0 0 0 2.83 0l1.25-1.25a.751.751 0 0 1 1.042.018.751.751 0 0 1 .018 1.042l-1.25 1.25a3.5 3.5 0 1 1-4.95-4.95l2.5-2.5a3.5 3.5 0 0 1 4.95 0 .751.751 0 0 1-.018 1.042.751.751 0 0 1-1.042.018 1.998 1.998 0 0 0-2.83 0l-2.5 2.5a1.998 1.998 0 0 0 0 2.83Z"></path></svg></a></div>
<p dir="auto"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">首先修改</font></font><code>./configs/inference.yaml</code><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">设置模型权重的路径，然后运行脚本：</font></font></p>
<div class="highlight highlight-source-shell notranslate position-relative overflow-auto" dir="auto"><pre>python run_gradio3_demo.py</pre><div class="zeroclipboard-container">
    <clipboard-copy aria-label="Copy" class="ClipboardButton btn btn-invisible js-clipboard-copy m-2 p-0 tooltipped-no-delay d-flex flex-justify-center flex-items-center" data-copy-feedback="Copied!" data-tooltip-direction="w" value="python run_gradio3_demo.py" tabindex="0" role="button">
      <svg aria-hidden="true" height="16" viewBox="0 0 16 16" version="1.1" width="16" data-view-component="true" class="octicon octicon-copy js-clipboard-copy-icon">
    <path d="M0 6.75C0 5.784.784 5 1.75 5h1.5a.75.75 0 0 1 0 1.5h-1.5a.25.25 0 0 0-.25.25v7.5c0 .138.112.25.25.25h7.5a.25.25 0 0 0 .25-.25v-1.5a.75.75 0 0 1 1.5 0v1.5A1.75 1.75 0 0 1 9.25 16h-7.5A1.75 1.75 0 0 1 0 14.25Z"></path><path d="M5 1.75C5 .784 5.784 0 6.75 0h7.5C15.216 0 16 .784 16 1.75v7.5A1.75 1.75 0 0 1 14.25 11h-7.5A1.75 1.75 0 0 1 5 9.25Zm1.75-.25a.25.25 0 0 0-.25.25v7.5c0 .138.112.25.25.25h7.5a.25.25 0 0 0 .25-.25v-7.5a.25.25 0 0 0-.25-.25Z"></path>
</svg>
      <svg aria-hidden="true" height="16" viewBox="0 0 16 16" version="1.1" width="16" data-view-component="true" class="octicon octicon-check js-clipboard-check-icon color-fg-success d-none">
    <path d="M13.78 4.22a.75.75 0 0 1 0 1.06l-7.25 7.25a.75.75 0 0 1-1.06 0L2.22 9.28a.751.751 0 0 1 .018-1.042.751.751 0 0 1 1.042-.018L6 10.94l6.72-6.72a.75.75 0 0 1 1.06 0Z"></path>
</svg>
    </clipboard-copy>
  </div></div>
<p dir="auto"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">gradio 演示看起来像下面显示的 UI。</font></font></p>
<p dir="auto"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">*如果您想要像第三种情况那样进行管道纹理转移，请不要忘记点击“保持原始形状”。</font></font><br></p>
<p dir="auto"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">简要教程：</font></font></p>
<ul dir="auto">
<li><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">上传/选择要编辑的源图像。</font></font></li>
<li><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">在源图像上绘制要编辑的区域。</font></font></li>
<li><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">上传/选择参考图像。</font></font></li>
<li><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">跑步。</font></font></li>
</ul>
<table align="center">
  <tbody><tr>
  <td>
    <a target="_blank" rel="noopener noreferrer" href="/ali-vilab/MimicBrush/blob/main/assets/demo.png"><img src="/ali-vilab/MimicBrush/raw/main/assets/demo.png" style="max-width: 100%;"></a>
  </td>
  </tr>
</tbody></table>
<div class="markdown-heading" dir="auto"><h2 tabindex="-1" class="heading-element" dir="auto"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">推理</font></font></h2><a id="user-content-inference" class="anchor" aria-label="永久链接：推理" href="#inference"><svg class="octicon octicon-link" viewBox="0 0 16 16" version="1.1" width="16" height="16" aria-hidden="true"><path d="m7.775 3.275 1.25-1.25a3.5 3.5 0 1 1 4.95 4.95l-2.5 2.5a3.5 3.5 0 0 1-4.95 0 .751.751 0 0 1 .018-1.042.751.751 0 0 1 1.042-.018 1.998 1.998 0 0 0 2.83 0l2.5-2.5a2.002 2.002 0 0 0-2.83-2.83l-1.25 1.25a.751.751 0 0 1-1.042-.018.751.751 0 0 1-.018-1.042Zm-4.69 9.64a1.998 1.998 0 0 0 2.83 0l1.25-1.25a.751.751 0 0 1 1.042.018.751.751 0 0 1 .018 1.042l-1.25 1.25a3.5 3.5 0 1 1-4.95-4.95l2.5-2.5a3.5 3.5 0 0 1 4.95 0 .751.751 0 0 1-.018 1.042.751.751 0 0 1-1.042.018 1.998 1.998 0 0 0-2.83 0l-2.5 2.5a1.998 1.998 0 0 0 0 2.83Z"></path></svg></a></div>
<ol dir="auto">
<li>
<p dir="auto"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">在 Google Drive 下载我们的评估基准：</font></font></p>
<ul dir="auto">
<li><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">网址：[待发布]</font></font></li>
</ul>
</li>
<li>
<p dir="auto"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">设置每个数据集和检查点的路径</font></font><code>./config/inference.yaml</code><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">：</font></font></p>
</li>
<li>
<p dir="auto"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">使用以下方式运行推理</font></font></p>
<div class="highlight highlight-source-shell notranslate position-relative overflow-auto" dir="auto"><pre>python run_inference_benchmark.py</pre><div class="zeroclipboard-container">
    <clipboard-copy aria-label="Copy" class="ClipboardButton btn btn-invisible js-clipboard-copy m-2 p-0 tooltipped-no-delay d-flex flex-justify-center flex-items-center" data-copy-feedback="Copied!" data-tooltip-direction="w" value="python run_inference_benchmark.py" tabindex="0" role="button">
      <svg aria-hidden="true" height="16" viewBox="0 0 16 16" version="1.1" width="16" data-view-component="true" class="octicon octicon-copy js-clipboard-copy-icon">
    <path d="M0 6.75C0 5.784.784 5 1.75 5h1.5a.75.75 0 0 1 0 1.5h-1.5a.25.25 0 0 0-.25.25v7.5c0 .138.112.25.25.25h7.5a.25.25 0 0 0 .25-.25v-1.5a.75.75 0 0 1 1.5 0v1.5A1.75 1.75 0 0 1 9.25 16h-7.5A1.75 1.75 0 0 1 0 14.25Z"></path><path d="M5 1.75C5 .784 5.784 0 6.75 0h7.5C15.216 0 16 .784 16 1.75v7.5A1.75 1.75 0 0 1 14.25 11h-7.5A1.75 1.75 0 0 1 5 9.25Zm1.75-.25a.25.25 0 0 0-.25.25v7.5c0 .138.112.25.25.25h7.5a.25.25 0 0 0 .25-.25v-7.5a.25.25 0 0 0-.25-.25Z"></path>
</svg>
      <svg aria-hidden="true" height="16" viewBox="0 0 16 16" version="1.1" width="16" data-view-component="true" class="octicon octicon-check js-clipboard-check-icon color-fg-success d-none">
    <path d="M13.78 4.22a.75.75 0 0 1 0 1.06l-7.25 7.25a.75.75 0 0 1-1.06 0L2.22 9.28a.751.751 0 0 1 .018-1.042.751.751 0 0 1 1.042-.018L6 10.94l6.72-6.72a.75.75 0 0 1 1.06 0Z"></path>
</svg>
    </clipboard-copy>
  </div></div>
</li>
</ol>
<div class="markdown-heading" dir="auto"><h2 tabindex="-1" class="heading-element" dir="auto"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">致谢</font></font></h2><a id="user-content-acknowledgements" class="anchor" aria-label="永久链接：致谢" href="#acknowledgements"><svg class="octicon octicon-link" viewBox="0 0 16 16" version="1.1" width="16" height="16" aria-hidden="true"><path d="m7.775 3.275 1.25-1.25a3.5 3.5 0 1 1 4.95 4.95l-2.5 2.5a3.5 3.5 0 0 1-4.95 0 .751.751 0 0 1 .018-1.042.751.751 0 0 1 1.042-.018 1.998 1.998 0 0 0 2.83 0l2.5-2.5a2.002 2.002 0 0 0-2.83-2.83l-1.25 1.25a.751.751 0 0 1-1.042-.018.751.751 0 0 1-.018-1.042Zm-4.69 9.64a1.998 1.998 0 0 0 2.83 0l1.25-1.25a.751.751 0 0 1 1.042.018.751.751 0 0 1 .018 1.042l-1.25 1.25a3.5 3.5 0 1 1-4.95-4.95l2.5-2.5a3.5 3.5 0 0 1 4.95 0 .751.751 0 0 1-.018 1.042.751.751 0 0 1-1.042.018 1.998 1.998 0 0 0-2.83 0l-2.5 2.5a1.998 1.998 0 0 0 0 2.83Z"></path></svg></a></div>
<p dir="auto"><font style="vertical-align: inherit;"></font><a href="https://github.com/tencent-ailab/IP-Adapter"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">该项目是在IP-Adapter</font></font></a><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">和</font></font><a href="https://github.com/magic-research/magic-animate"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">MagicAnimate</font></font></a><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">的代码库上开发的</font><font style="vertical-align: inherit;">  。我们感谢这项伟大的工作！</font></font></p>
<div class="markdown-heading" dir="auto"><h2 tabindex="-1" class="heading-element" dir="auto"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">引用</font></font></h2><a id="user-content-citation" class="anchor" aria-label="永久链接：引用" href="#citation"><svg class="octicon octicon-link" viewBox="0 0 16 16" version="1.1" width="16" height="16" aria-hidden="true"><path d="m7.775 3.275 1.25-1.25a3.5 3.5 0 1 1 4.95 4.95l-2.5 2.5a3.5 3.5 0 0 1-4.95 0 .751.751 0 0 1 .018-1.042.751.751 0 0 1 1.042-.018 1.998 1.998 0 0 0 2.83 0l2.5-2.5a2.002 2.002 0 0 0-2.83-2.83l-1.25 1.25a.751.751 0 0 1-1.042-.018.751.751 0 0 1-.018-1.042Zm-4.69 9.64a1.998 1.998 0 0 0 2.83 0l1.25-1.25a.751.751 0 0 1 1.042.018.751.751 0 0 1 .018 1.042l-1.25 1.25a3.5 3.5 0 1 1-4.95-4.95l2.5-2.5a3.5 3.5 0 0 1 4.95 0 .751.751 0 0 1-.018 1.042.751.751 0 0 1-1.042.018 1.998 1.998 0 0 0-2.83 0l-2.5 2.5a1.998 1.998 0 0 0 0 2.83Z"></path></svg></a></div>
<p dir="auto"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">如果您发现该代码库对您的研究有用，请使用以下条目。</font></font></p>
<div class="highlight highlight-text-bibtex notranslate position-relative overflow-auto" dir="auto"><pre><span class="pl-k">@article</span>{<span class="pl-en">chen2024mimicbrush</span>,
  <span class="pl-s">title</span>=<span class="pl-s"><span class="pl-pds">{</span>Zero-shot Image Editing with Reference Imitation<span class="pl-pds">}</span></span>,
  <span class="pl-s">author</span>=<span class="pl-s"><span class="pl-pds">{</span>Chen, Xi and Feng, Yutong and Chen, Mengting and Wang, Yiyang, and Zhang, Shilong and Yu, Liu and Shen, Yujun and Zhao, Hengshuang<span class="pl-pds">}</span></span>,
  <span class="pl-s">journal</span>=<span class="pl-s"><span class="pl-pds">{</span>arXiv preprint arXiv:2406.07547<span class="pl-pds">}</span></span>,
  <span class="pl-s">year</span>=<span class="pl-s"><span class="pl-pds">{</span>2024<span class="pl-pds">}</span></span>
}</pre><div class="zeroclipboard-container">
    <clipboard-copy aria-label="Copy" class="ClipboardButton btn btn-invisible js-clipboard-copy m-2 p-0 tooltipped-no-delay d-flex flex-justify-center flex-items-center" data-copy-feedback="Copied!" data-tooltip-direction="w" value="@article{chen2024mimicbrush,
  title={Zero-shot Image Editing with Reference Imitation},
  author={Chen, Xi and Feng, Yutong and Chen, Mengting and Wang, Yiyang, and Zhang, Shilong and Yu, Liu and Shen, Yujun and Zhao, Hengshuang},
  journal={arXiv preprint arXiv:2406.07547},
  year={2024}
}" tabindex="0" role="button">
      <svg aria-hidden="true" height="16" viewBox="0 0 16 16" version="1.1" width="16" data-view-component="true" class="octicon octicon-copy js-clipboard-copy-icon">
    <path d="M0 6.75C0 5.784.784 5 1.75 5h1.5a.75.75 0 0 1 0 1.5h-1.5a.25.25 0 0 0-.25.25v7.5c0 .138.112.25.25.25h7.5a.25.25 0 0 0 .25-.25v-1.5a.75.75 0 0 1 1.5 0v1.5A1.75 1.75 0 0 1 9.25 16h-7.5A1.75 1.75 0 0 1 0 14.25Z"></path><path d="M5 1.75C5 .784 5.784 0 6.75 0h7.5C15.216 0 16 .784 16 1.75v7.5A1.75 1.75 0 0 1 14.25 11h-7.5A1.75 1.75 0 0 1 5 9.25Zm1.75-.25a.25.25 0 0 0-.25.25v7.5c0 .138.112.25.25.25h7.5a.25.25 0 0 0 .25-.25v-7.5a.25.25 0 0 0-.25-.25Z"></path>
</svg>
      <svg aria-hidden="true" height="16" viewBox="0 0 16 16" version="1.1" width="16" data-view-component="true" class="octicon octicon-check js-clipboard-check-icon color-fg-success d-none">
    <path d="M13.78 4.22a.75.75 0 0 1 0 1.06l-7.25 7.25a.75.75 0 0 1-1.06 0L2.22 9.28a.751.751 0 0 1 .018-1.042.751.751 0 0 1 1.042-.018L6 10.94l6.72-6.72a.75.75 0 0 1 1.06 0Z"></path>
</svg>
    </clipboard-copy>
  </div></div>
<div class="markdown-heading" dir="auto"><h2 tabindex="-1" class="heading-element" dir="auto"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">星历史</font></font></h2><a id="user-content-star-history" class="anchor" aria-label="永久链接：明星历史" href="#star-history"><svg class="octicon octicon-link" viewBox="0 0 16 16" version="1.1" width="16" height="16" aria-hidden="true"><path d="m7.775 3.275 1.25-1.25a3.5 3.5 0 1 1 4.95 4.95l-2.5 2.5a3.5 3.5 0 0 1-4.95 0 .751.751 0 0 1 .018-1.042.751.751 0 0 1 1.042-.018 1.998 1.998 0 0 0 2.83 0l2.5-2.5a2.002 2.002 0 0 0-2.83-2.83l-1.25 1.25a.751.751 0 0 1-1.042-.018.751.751 0 0 1-.018-1.042Zm-4.69 9.64a1.998 1.998 0 0 0 2.83 0l1.25-1.25a.751.751 0 0 1 1.042.018.751.751 0 0 1 .018 1.042l-1.25 1.25a3.5 3.5 0 1 1-4.95-4.95l2.5-2.5a3.5 3.5 0 0 1 4.95 0 .751.751 0 0 1-.018 1.042.751.751 0 0 1-1.042.018 1.998 1.998 0 0 0-2.83 0l-2.5 2.5a1.998 1.998 0 0 0 0 2.83Z"></path></svg></a></div>
<p dir="auto"><a href="https://star-history.com/#ali-vilab/MimicBrush&amp;Date" rel="nofollow"><img src="https://camo.githubusercontent.com/379104417b4595e1c0b758d22b679462560ac1bd76bc78ee57df6e66889b6bb4/68747470733a2f2f6170692e737461722d686973746f72792e636f6d2f7376673f7265706f733d616c692d76696c61622f4d696d6963427275736826747970653d44617465" alt="星历史图" data-canonical-src="https://api.star-history.com/svg?repos=ali-vilab/MimicBrush&amp;type=Date" style="max-width: 100%;"></a></p>
</article></div>
