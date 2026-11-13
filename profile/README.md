<div align="center">

<a href="https://replyze.chat/?utm_source=github&utm_medium=referral&utm_campaign=profile">
  <picture>
    <source media="(prefers-color-scheme: dark)" srcset="https://raw.githubusercontent.com/Replyze/.github/main/assets/logo-on-dark.png">
    <img src="https://raw.githubusercontent.com/Replyze/.github/main/assets/logo-on-light.png" alt="Replyze" height="56">
  </picture>
</a>

### AI customer support: an AI agent that answers from your docs, live chat on your website and one inbox for every channel

[![Create a free account](https://img.shields.io/badge/Create_a_free_account-1eabd2?style=for-the-badge)](https://client.replyze.chat/register?utm_source=github&utm_medium=referral&utm_campaign=profile&utm_content=cta-top)
[![Live demo](https://img.shields.io/badge/Live_demo-replyze.chat-0b0f17?style=for-the-badge)](https://replyze.chat/?utm_source=github&utm_medium=referral&utm_campaign=profile&utm_content=live-demo)
[![Developer docs](https://img.shields.io/badge/Developers-Docs-2ea44f?style=for-the-badge)](https://github.com/Replyze/replyze)

</div>

---

## What Replyze does

- **AI agent** that answers your customers from your website, help articles and files, and hands the chat to your team when it can't help or when the customer asks for a person.
- **One inbox** for web chat, email, WhatsApp and Telegram (Messenger and Instagram in beta), shared by your whole team.
- **Live chat widget** for your website and your mobile app, in your customers' language.
- **Help center** with articles that the AI answers from, and that customers can read on their own.
- **API, webhooks and an MCP server**, so your own tools and AI assistants can work with your conversations.

The live demo is replyze.chat itself: the chat bubble in the corner of [replyze.chat](https://replyze.chat/?utm_source=github&utm_medium=referral&utm_campaign=profile&utm_content=live-demo) is the Replyze widget. Plans: [replyze.chat/pricing](https://replyze.chat/pricing?utm_source=github&utm_medium=referral&utm_campaign=profile).

## Start in two minutes

1. [Create a free account](https://client.replyze.chat/register?utm_source=github&utm_medium=referral&utm_campaign=profile&utm_content=quickstart) and copy your widget token (`wgt_...`) from **Settings → Integrations → Install widget**.
2. Pick your stack:

| You use | Start here | Install |
|---|---|---|
| Any website: HTML, Shopify, Wix, Squarespace, Webflow, Framer, Ghost, GTM | [add-live-chat-to-website](https://github.com/Replyze/add-live-chat-to-website) | one `<script>` tag |
| WordPress or WooCommerce | [wordpress-live-chat](https://github.com/Replyze/wordpress-live-chat) | [`replyze.zip`](https://github.com/Replyze/wordpress-live-chat/releases/latest/download/replyze.zip) → Plugins → Upload |
| React or Next.js | [react-live-chat](https://github.com/Replyze/react-live-chat) | `npm install github:Replyze/react-live-chat` |
| Vue or Nuxt | [vue-live-chat](https://github.com/Replyze/vue-live-chat) | `npm install github:Replyze/vue-live-chat` |
| React Native or Expo | [react-native-live-chat](https://github.com/Replyze/react-native-live-chat) | `npm install github:Replyze/react-native-live-chat` |
| Flutter | [flutter-live-chat](https://github.com/Replyze/flutter-live-chat) | git dependency in `pubspec.yaml` |
| Your backend: REST API, webhooks, OpenAPI | [replyze](https://github.com/Replyze/replyze) | an API key from **Settings → Integrations → Developer** |
| Claude, ChatGPT, Cursor, VS Code | [replyze-mcp](https://github.com/Replyze/replyze-mcp) · [knowledge-base-mcp-server](https://github.com/Replyze/knowledge-base-mcp-server) | a remote MCP URL, nothing to host |

On a plain website, this is all it takes:

```html
<script>
  window.ReplyzeConfig = {
    token: 'wgt_YOUR_TOKEN',
    apiUrl: 'https://client.replyze.chat'
  };
</script>
<script src="https://cdn.replyze.chat/widget.js" async></script>
```

## Developers

| Repository | What is inside |
|---|---|
| [replyze](https://github.com/Replyze/replyze) | Embed code, JavaScript API, REST API, webhooks and the OpenAPI spec, with tested examples in cURL, Node.js, Python and PHP |
| [replyze-mcp](https://github.com/Replyze/replyze-mcp) | MCP server: Claude, Cursor and VS Code read and answer your customer conversations and search your knowledge base |
| [knowledge-base-mcp-server](https://github.com/Replyze/knowledge-base-mcp-server) | Your public help center as an MCP server: anyone's assistant can search and cite your articles, no key needed |
| [ai-customer-support-agent](https://github.com/Replyze/ai-customer-support-agent) | A small Python AI support agent that answers only from your docs, cites them and hands off to a person, with evals |
| [n8n-chat-widget](https://github.com/Replyze/n8n-chat-widget) | n8n workflows for the Replyze chat: answer with your own n8n AI agent and hand off to your team, or send new chats to Slack and leads to Google Sheets, with signed webhooks |

## Guides and free tools

| Repository | What is inside |
|---|---|
| [ai-chatbot-for-website](https://github.com/Replyze/ai-chatbot-for-website) | An AI chatbot trained on your own pages: how it reads a site, writing pages it can use, and tested code for Docusaurus, VitePress, MkDocs, Starlight and Nextra |
| [whatsapp-chat-button](https://github.com/Replyze/whatsapp-chat-button) | A free WhatsApp chat button for any website, with a [generator](https://replyze.github.io/whatsapp-chat-button/): one script tag, no tracking |
| [customer-service-templates](https://github.com/Replyze/customer-service-templates) | Free customer service templates: email templates for tough situations, canned responses, an AI chatbot prompt, ChatGPT prompts and replies for 21 industries |
| [awesome-live-chat](https://github.com/Replyze/awesome-live-chat) | A curated list of live chat and customer support software: open source, hosted, AI agents, SDKs and MCP servers |

## Help

Questions about your account or the AI agent: **support@replyze.chat** or the chat on [replyze.chat](https://replyze.chat/?utm_source=github&utm_medium=referral&utm_campaign=profile&utm_content=support). A bug in one of these repositories: open an issue there. Missing an integration: open an issue with the **Integration request** form. Security: see our [security policy](https://github.com/Replyze/.github/blob/main/SECURITY.md).
