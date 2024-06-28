---
title: Home
layout: home
title: Test
layout: #test.md
---
<details>
  <summary>Methods</summary>
    <li><a href="#installation">🔗</a><code>remove(int $index): bool</code></li>
    <li><a href="#installation">🔗</a><code>count(): int</code></li>
</details>

# Method: account.changeAuthorizationSettings
[Back to methods index](index.html)

Change settings related to a session.

### Parameters:

| Name     |    Type       | Description | Required |
|----------|---------------|-------------|----------|
|confirmed|[Bool](/API_docs/types/Bool.html) | If set, [confirms a newly logged in session »](https://core.telegram.org/api/auth#confirming-login). | Optional|
|hash|Array of [long](/API_docs/types/long.html) | Session ID from the [authorization](../constructors/authorization.html) constructor, fetchable using [account.getAuthorizations](../methods/account.getAuthorizations.html) | Optional|
|encrypted\_requests\_disabled|[Bool](/API_docs/types/Bool.html) | Whether to enable or disable receiving encrypted chats: if the flag is not set, the previous setting is not changed | Optional|
|call\_requests\_disabled|[Bool](/API_docs/types/Bool.html) | Whether to enable or disable receiving calls: if the flag is not set, the previous setting is not changed | Optional|


### Return type: [Bool](/API_docs/types/Bool.html)
