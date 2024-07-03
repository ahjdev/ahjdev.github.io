---
layout: default
title: Test
color_scheme: light
---
<blockquote> <p>Just the time</p> <div class="language-php highlighter-rouge"><div class="highlight"><pre class="highlight"><code><span class="nb">public</span> <span class="s1">int</span> <span class="k">$date</span>
</code></pre></div><button type="button" aria-label="Copy code to clipboard"><svg viewBox="0 0 24 24" class="copy-icon"><use xlink:href="#svg-copy"></use></svg></button></div></blockquote>

<blockquote> <p>Whether the message is outgoing</p> <div class="language-php highlighter-rouge"><div class="highlight"><pre class="highlight"><code><span class="nb">public</span> <span class="s1">bool</span> <span class="k">$out</span>
</code></pre></div><button type="button" aria-label="Copy code to clipboard"><svg viewBox="0 0 24 24" class="copy-icon"><use xlink:href="#svg-copy"></use></svg></button></div></blockquote>

<blockquote> <p>ID of the chat where the message was sent</p><div class="language-php highlighter-rouge"><div class="highlight"><pre class="highlight"><code><span class="nb">public</span> <a href="#felan"><span class="s1">int</span></a> <span class="k">$chatId</span>
</code></pre></div><button type="button" aria-label="Copy code to clipboard"><svg viewBox="0 0 24 24" class="copy-icon"><use xlink:href="#svg-copy"></use></svg></button></div></blockquote>

<h1><code>Reymon\Types\Message</code></h1>

> Represents a query sent by the user by clicking on a button.{ .note }
> - [Properties](#Properties){: .btn .btn-purple}
> - [Constants](#Constants){: .btn .btn-purple}
> - [Methods](#Methods){: .btn .btn-purple}

### Properties
> - `public`[`string`](#felan)`$name` - Message ID
> - `red{: style="color: red"} $out` : `bool` Whether the message is outgoing
> - `$chatId` : `int` ID of the chat where the message was sent

### Constants
> - `public const int $flag` - Class flag

### Methods
> - [`isReply(): bool`](#felan) - Whether this message replied
> - [`delete(boolean $revoke = true): void`](#felan) - Delete message
> - [`read(bool $readAll = false): boolean`](#felan) - Mark message as read
