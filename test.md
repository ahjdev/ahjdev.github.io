---
layout: default
title: Test
color_scheme: light
---
> `Reymon\Types\Message`
> - Represents a query sent by the user by clicking on a button.
> - [Methods](#Methods){: .btn .btn-purple}
> - [Properties](#Properties){: .btn .btn-purple}

### Properties
> - `public `[`string`](#felan)` $name` - Message ID
> - `$out` : `bool` Whether the message is outgoing
> - `$chatId` : `int` ID of the chat where the message was sent

### Methods
> - [`isReply(): bool`](#felan) - Whether this message replied
> - [`delete(boolean $revoke = true): void`](#felan) - Delete message
> - [`read(bool $readAll = false): boolean`](#felan) - Mark message as read
