---
layout: default
title: Test
color_scheme: light
---
<h1><code>Reymon\Types\Message</code></h1>

> Represents a query sent by the user by clicking on a button.{ .note }
> - [Properties](#Properties){: .btn .btn-purple}
> - [Constants](#Constants){: .btn .btn-purple}
> - [Methods](#Methods){: .btn .btn-purple}

### Properties
<blockquote> <p>Message ID</p> <div class="language-php highlighter-rouge"><div class="highlight"><pre class="highlight"><code><span class="nb">public</span> <span class="s1">string</span> <span class="k">$name</span>
</code></pre></div><button type="button" aria-label="Copy code to clipboard"><svg viewBox="0 0 24 24" class="copy-icon"><use xlink:href="#svg-copy"></use></svg></button></div></blockquote>

<blockquote> <p>Just the time</p> <div class="language-php highlighter-rouge"><div class="highlight"><pre class="highlight"><code><span class="nb">public</span> <span class="s1">int</span> <span class="k">$date</span>
</code></pre></div><button type="button" aria-label="Copy code to clipboard"><svg viewBox="0 0 24 24" class="copy-icon"><use xlink:href="#svg-copy"></use></svg></button></div></blockquote>

<blockquote> <p>Whether the message is outgoing</p> <div class="language-php highlighter-rouge"><div class="highlight"><pre class="highlight"><code><span class="nb">public</span> <span class="s1">bool</span> <span class="k">$out</span>
</code></pre></div><button type="button" aria-label="Copy code to clipboard"><svg viewBox="0 0 24 24" class="copy-icon"><use xlink:href="#svg-copy"></use></svg></button></div></blockquote>

<blockquote> <p>ID of the chat where the message was sent</p><div class="language-php highlighter-rouge"><div class="highlight"><pre class="highlight"><code><span class="nb">public</span> <a href="#felan"><span class="s1">int</span></a> <span class="k">$chatId</span>
</code></pre></div><button type="button" aria-label="Copy code to clipboard"><svg viewBox="0 0 24 24" class="copy-icon"><use xlink:href="#svg-copy"></use></svg></button></div></blockquote>

### Constants
<blockquote> <p>Class flag</p><div class="language-php highlighter-rouge"><div class="highlight"><pre class="highlight"><code><span class="nb">public</span> <code><span class="nb">const</span> <a href="#felan"><span class="s1">int</span></a> <span class="k">$flag</span>
</code></pre></div><button type="button" aria-label="Copy code to clipboard"><svg viewBox="0 0 24 24" class="copy-icon"><use xlink:href="#svg-copy"></use></svg></button></div></blockquote>

### Methods
> - Whether this message replied
```php
isReply(): bool
```

> - Delete message
```php
delete(boolean $revoke = true): void
```

> - Mark message as read
```php
read(bool $readAll = false): boolean
```
