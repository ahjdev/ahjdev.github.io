---
layout: default
title: Test
color_scheme: light
---
- NamespaceReymon\Types
- [Properties](#Properties)
- [Methods](#Methods)

### Properties
{{test | .text-yellow-100}}
> - `public string $name` - Message ID
> - `$out` : `bool` Whether the message is outgoing
> - `$chatId` : `int` ID of the chat where the message was sent

### Methods
> - [`isReply(): bool`](#felan) - Whether this message replied
> - [`delete(boolean $revoke = true): void`](#felan) - Delete message
> - [`read(bool $readAll = false): boolean`](#felan) - Mark message as read
