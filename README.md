<div class="Box-sc-g0xbh4-0 bJMeLZ js-snippet-clipboard-copy-unpositioned" data-hpc="true"><article class="markdown-body entry-content container-lg" itemprop="text"><div class="markdown-heading" dir="auto"><h1 tabindex="-1" class="heading-element" dir="auto"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">Nebuly - 法学硕士用户分析平台</font></font></h1><a id="user-content-nebuly---the-user-analytics-platform-for-llms" class="anchor" aria-label="永久链接：Nebuly - 基于大模型的用户分析平台" href="#nebuly---the-user-analytics-platform-for-llms"><svg class="octicon octicon-link" viewBox="0 0 16 16" version="1.1" width="16" height="16" aria-hidden="true"><path d="m7.775 3.275 1.25-1.25a3.5 3.5 0 1 1 4.95 4.95l-2.5 2.5a3.5 3.5 0 0 1-4.95 0 .751.751 0 0 1 .018-1.042.751.751 0 0 1 1.042-.018 1.998 1.998 0 0 0 2.83 0l2.5-2.5a2.002 2.002 0 0 0-2.83-2.83l-1.25 1.25a.751.751 0 0 1-1.042-.018.751.751 0 0 1-.018-1.042Zm-4.69 9.64a1.998 1.998 0 0 0 2.83 0l1.25-1.25a.751.751 0 0 1 1.042.018.751.751 0 0 1 .018 1.042l-1.25 1.25a3.5 3.5 0 1 1-4.95-4.95l2.5-2.5a3.5 3.5 0 0 1 4.95 0 .751.751 0 0 1-.018 1.042.751.751 0 0 1-1.042.018 1.998 1.998 0 0 0-2.83 0l-2.5 2.5a1.998 1.998 0 0 0 0 2.83Z"></path></svg></a></div>
<p dir="auto"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">这是 Nebuly 的官方 Python SDK。</font></font><strong><a href="https://www.nebuly.com/" rel="nofollow"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">Nebuly</font></font></a></strong><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">&nbsp;是LLM的用户分析平台，使您能够自动捕获用户如何与模型交互。该平台可帮助您了解您的法学硕士用户喜欢什么、不喜欢什么以及原因、最常见的问题是什么，以及如何改进您的法学硕士产品以使您的客户满意。</font></font></p>
<div class="markdown-heading" dir="auto"><h2 tabindex="-1" class="heading-element" dir="auto"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">安装</font></font></h2><a id="user-content-installation" class="anchor" aria-label="永久链接：安装" href="#installation"><svg class="octicon octicon-link" viewBox="0 0 16 16" version="1.1" width="16" height="16" aria-hidden="true"><path d="m7.775 3.275 1.25-1.25a3.5 3.5 0 1 1 4.95 4.95l-2.5 2.5a3.5 3.5 0 0 1-4.95 0 .751.751 0 0 1 .018-1.042.751.751 0 0 1 1.042-.018 1.998 1.998 0 0 0 2.83 0l2.5-2.5a2.002 2.002 0 0 0-2.83-2.83l-1.25 1.25a.751.751 0 0 1-1.042-.018.751.751 0 0 1-.018-1.042Zm-4.69 9.64a1.998 1.998 0 0 0 2.83 0l1.25-1.25a.751.751 0 0 1 1.042.018.751.751 0 0 1 .018 1.042l-1.25 1.25a3.5 3.5 0 1 1-4.95-4.95l2.5-2.5a3.5 3.5 0 0 1 4.95 0 .751.751 0 0 1-.018 1.042.751.751 0 0 1-1.042.018 1.998 1.998 0 0 0-2.83 0l-2.5 2.5a1.998 1.998 0 0 0 0 2.83Z"></path></svg></a></div>
<p dir="auto"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">安装 Nebuly SDK 最简单的方法是通过&nbsp;</font></font><code>pip</code><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">：</font></font></p>
<div class="snippet-clipboard-content notranslate position-relative overflow-auto"><pre class="notranslate"><code>pip install nebuly
</code></pre><div class="zeroclipboard-container">
  
  </div></div>
<p dir="auto"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">安装完成后，对 Nebuly 平台进行身份验证并开始构建。</font></font></p>
<div class="markdown-heading" dir="auto"><h2 tabindex="-1" class="heading-element" dir="auto"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">开始使用</font></font></h2><a id="user-content-get-started" class="anchor" aria-label="永久链接：开始吧" href="#get-started"><svg class="octicon octicon-link" viewBox="0 0 16 16" version="1.1" width="16" height="16" aria-hidden="true"><path d="m7.775 3.275 1.25-1.25a3.5 3.5 0 1 1 4.95 4.95l-2.5 2.5a3.5 3.5 0 0 1-4.95 0 .751.751 0 0 1 .018-1.042.751.751 0 0 1 1.042-.018 1.998 1.998 0 0 0 2.83 0l2.5-2.5a2.002 2.002 0 0 0-2.83-2.83l-1.25 1.25a.751.751 0 0 1-1.042-.018.751.751 0 0 1-.018-1.042Zm-4.69 9.64a1.998 1.998 0 0 0 2.83 0l1.25-1.25a.751.751 0 0 1 1.042.018.751.751 0 0 1 .018 1.042l-1.25 1.25a3.5 3.5 0 1 1-4.95-4.95l2.5-2.5a3.5 3.5 0 0 1 4.95 0 .751.751 0 0 1-.018 1.042.751.751 0 0 1-1.042.018 1.998 1.998 0 0 0-2.83 0l-2.5 2.5a1.998 1.998 0 0 0 0 2.83Z"></path></svg></a></div>
<p dir="auto"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">跟踪与 Nebuly 的交互非常简单，只需要两行代码。一如既往地使用您的法学硕士，您所需要做的就是：</font></font></p>
<ol dir="auto">
<li><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">包括 Nebuly 的 API 密钥。</font></font></li>
<li><font style="vertical-align: inherit;"></font><strong><code>user_id</code></strong><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">&nbsp;在模型调用中</font><font style="vertical-align: inherit;">添加&nbsp;参数。</font></font></li>
</ol>
<p dir="auto"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">通过这些简单的添加，您可以在 2 分钟内开始跟踪与 Nebuly 的交互。</font></font></p>
<div class="highlight highlight-source-python notranslate position-relative overflow-auto" dir="auto"><pre><span class="pl-k">import</span> <span class="pl-s1">nebuly</span>
<span class="pl-k">import</span> <span class="pl-s1">openai</span>

<span class="pl-s1">nebuly</span>.<span class="pl-en">init</span>(<span class="pl-s1">api_key</span><span class="pl-c1">=</span><span class="pl-s">"&lt;nebuly_api_key&gt;"</span>)
<span class="pl-s1">openai</span>.<span class="pl-s1">api_key</span> <span class="pl-c1">=</span> <span class="pl-s">"&lt;your_openai_api_key&gt;"</span>

<span class="pl-s1">response</span> <span class="pl-c1">=</span> <span class="pl-s1">openai</span>.<span class="pl-v">ChatCompletion</span>.<span class="pl-en">create</span>(
    <span class="pl-s1">model</span><span class="pl-c1">=</span><span class="pl-s">"gpt-3.5-turbo"</span>,
    <span class="pl-s1">messages</span><span class="pl-c1">=</span>[
        {
            <span class="pl-s">"role"</span>: <span class="pl-s">"system"</span>,
            <span class="pl-s">"content"</span>: <span class="pl-s">"You are an helpful assistant"</span>
        },
        {
            <span class="pl-s">"role"</span>: <span class="pl-s">"user"</span>,
            <span class="pl-s">"content"</span>: <span class="pl-s">"Hello, I need help with my computer"</span>
        }
    ],
    <span class="pl-s1">user_id</span><span class="pl-c1">=</span><span class="pl-s">"test_user"</span>,
)</pre><div class="zeroclipboard-container">
    
  </div></div>
<p dir="auto"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">我们还支持 Azure OpenAI、HuggingFace、Cohere、Anthropic、VertexAI 和 Bedrock。要了解更多信息，请访问</font></font><a href="https://docs.nebuly.com/welcome/overview" rel="nofollow"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">文档</font></font></a><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">。</font></font></p>
</article></div>
