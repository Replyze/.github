<div align="center">

<a href="https://replyze.chat/?utm_source=github&utm_medium=profile">
  <picture>
    <source media="(prefers-color-scheme: dark)" srcset="https://raw.githubusercontent.com/Replyze/.github/main/assets/logo-on-dark.png">
    <img src="https://raw.githubusercontent.com/Replyze/.github/main/assets/logo-on-light.png" alt="Replyze" height="56">
  </picture>
</a>

### AI customer support: an AI agent that answers from your docs, live chat on your website and one inbox for every channel

[![Website](https://img.shields.io/badge/Website-replyze.chat-1eabd2?style=for-the-badge)](https://replyze.chat/?utm_source=github&utm_medium=profile)
[![Sign up](https://img.shields.io/badge/Dashboard-Sign_up-0b0f17?style=for-the-badge)](https://client.replyze.chat/register?utm_source=github&utm_medium=profile)
[![Developer docs](https://img.shields.io/badge/Developers-Docs-2ea44f?style=for-the-badge)](https://github.com/Replyze/replyze)
[![Integrations](https://img.shields.io/badge/Integrations-All_platforms-8a63d2?style=for-the-badge)](https://replyze.chat/integrations?utm_source=github&utm_medium=profile)

</div>

---

## What Replyze does

- **AI agent** that answers your customers from your website, help articles and files, and hands the chat to your team when it can't help or when the customer asks for a person.
- **One inbox** for web chat, email, WhatsApp and Telegram (Messenger and Instagram in beta), shared by your whole team.
- **Live chat widget** for your website and your mobile app, in your customers' language.
- **Help center** with articles that the AI answers from, and that customers can read on their own.
- **API, webhooks and an MCP server**, so your own tools and AI assistants can work with your conversations.

Plans and prices: [replyze.chat/pricing](https://replyze.chat/pricing?utm_source=github&utm_medium=profile).

## Add the chat to your website

```html
<script>
  window.ReplyzeConfig = {
    token: 'wgt_YOUR_TOKEN',
    apiUrl: 'https://client.replyze.chat'
  };
</script>
<script src="https://cdn.replyze.chat/widget.js" async></script>
```

Your token is in the [dashboard](https://client.replyze.chat/?utm_source=github&utm_medium=profile): Settings → Integrations → Install widget. Step-by-step code for WordPress, Shopify, Wix, Webflow, Next.js, Vue, Laravel and more: [add-live-chat-to-website](https://github.com/Replyze/add-live-chat-to-website).

## Integrations

| Repository | What is inside |
|---|---|
| [wordpress-live-chat](https://github.com/Replyze/wordpress-live-chat) | WordPress plugin: the chat on any WordPress or WooCommerce site, signed-in customers recognized |
| [react-native-live-chat](https://github.com/Replyze/react-native-live-chat) | Live chat and AI support inside React Native and Expo apps |
| [flutter-live-chat](https://github.com/Replyze/flutter-live-chat) | Live chat and AI support inside Flutter apps for iOS and Android |
| [add-live-chat-to-website](https://github.com/Replyze/add-live-chat-to-website) | Copy-paste install code for every common website platform and framework |

## Developers

| Repository | What is inside |
|---|---|
| [replyze](https://github.com/Replyze/replyze) | Embed code, JavaScript API, REST API, webhooks and the OpenAPI spec, with examples in cURL, Node.js, Python and PHP |
| [replyze-mcp](https://github.com/Replyze/replyze-mcp) | MCP server: Claude, Cursor and VS Code read and answer your customer conversations and search your knowledge base |
