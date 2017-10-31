---
id: version-0.48-clipboard
title: Clipboard
category: APIs
permalink: docs/clipboard.html
original_id: clipboard
---
<div><div><p><code>Clipboard</code> gives you an interface for setting and getting content from Clipboard on both iOS and Android</p></div><span><h3><a class="anchor" name="methods"></a>Methods <a class="hash-link" href="docs/clipboard.html#methods">#</a></h3><div class="props"><div class="prop"><h4 class="methodTitle"><a class="anchor" name="getstring"></a><span class="methodType">static </span>getString<span class="methodType">()</span> <a class="hash-link" href="docs/clipboard.html#getstring">#</a></h4><div><p>Get content of string type, this method returns a <code>Promise</code>, so you can use following code to get clipboard content</p><div class="prism language-javascript"><span class="token keyword">async</span> <span class="token function">_getContent</span><span class="token punctuation">(</span><span class="token punctuation">)</span> <span class="token punctuation">{</span>
  <span class="token keyword">var</span> content <span class="token operator">=</span> <span class="token keyword">await</span> Clipboard<span class="token punctuation">.</span><span class="token function">getString</span><span class="token punctuation">(</span><span class="token punctuation">)</span><span class="token punctuation">;</span>
<span class="token punctuation">}</span></div></div></div><div class="prop"><h4 class="methodTitle"><a class="anchor" name="setstring"></a><span class="methodType">static </span>setString<span class="methodType">(content)</span> <a class="hash-link" href="docs/clipboard.html#setstring">#</a></h4><div><p>Set content of string type. You can use following code to set clipboard content</p><div class="prism language-javascript"><span class="token function">_setContent</span><span class="token punctuation">(</span><span class="token punctuation">)</span> <span class="token punctuation">{</span>
  Clipboard<span class="token punctuation">.</span><span class="token function">setString</span><span class="token punctuation">(</span><span class="token string">'hello world'</span><span class="token punctuation">)</span><span class="token punctuation">;</span>
<span class="token punctuation">}</span></div><p>@param the content to be stored in the clipboard.</p></div></div></div></span></div>