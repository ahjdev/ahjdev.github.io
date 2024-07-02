---
layout: default
title: Test
color_scheme: light
---

<figure class="highlight">
<code class="language-php" data-lang="php"><pre><span class="nb">public</span>&nbsp;<span class="s1">int</span>&nbsp;<span class="k">$date</span></pre></code>
</figure>



<h1><code>Reymon\Types\Message</code></h1>

Represents a query sent by the user by clicking on a button.
{: .highlight }

> - [Methods](#Methods){: .btn .btn-purple}
> - [Properties](#Properties){: .btn .btn-purple}

### Properties
> - `public`[`string`](#felan)`$name` - Message ID
> - `$out` : `bool` Whether the message is outgoing
> - `$chatId` : `int` ID of the chat where the message was sent

### Constants
> - `public const int $flag` - Class flag

### Methods
> - [`isReply(): bool`](#felan) - Whether this message replied
> - [`delete(boolean $revoke = true): void`](#felan) - Delete message
> - [`read(bool $readAll = false): boolean`](#felan) - Mark message as read
