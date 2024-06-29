---
layout: default
title: Test
---
<figure class="highlight">><code class="language-ruby" data-lang="ruby"><div class="table-wrapper"><table class="rouge-table"><tbody><tr><td class="gutter gl"><pre class="lineno">1
2
3
</pre><td class="code"><pre><span class="k">def</span> <span class="nf">foo</span>
  <span class="nb">puts</span> <span class="s1">'foo'</span>
<span class="k">end</span>
</pre></figure>

# Test
<details>
  <summary>Properties</summary>
  <li> <code>$id</code> : <code>int</code> Message ID</li>
  <li> <code>$out</code> : <code>bool</code> Whether the message is outgoing</li>
  <li> <code>$chatId</code> : <code>int</code> ID of the chat where the message was sent</li>
</details>
<details>
  <summary>Methods</summary>
  <li> <a href="#felan"><code>isReply(): bool</code></a></li>
  <li> <a href="#felan"><code>delete(boolean $revoke = true): void</code></a></li>
  <li> <a href="#felan"><code>read(bool $readAll = false): boolean</code></a></li>
</details>
