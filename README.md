<p align="center">
  <img src="https://vetrx3zkmavopskp.public.blob.vercel-storage.com/lingojs-a5GTXEzkvIysXRWV5lkCbNstI0MoL9.png" alt="Logo" width="200"/>
</p>

# 🌐 LingoJs – Effortless Multilingual Support for Websites

**LingoJs** is a developer first translation management platform that makes it easy to add multilingual support to any website. With just one script tag, you can manage, translate, and deploy language versions of your site without complex infrastructure or external translation services.
[LingoJs.com](https://lingojs.com)

## ✨ Why LingoJs?

* **No Backend Needed** – Just drop a script into your HTML and you're live.
* **Full Control Over Translations** – Manage translations manually or collaboratively with your team.
* **Flexible Language Switcher** – Auto-detect language or let users choose via a customizable widget.
* **Developer-Oriented** – Built with simplicity and flexibility in mind, it works with any tech stack.
* **Collaboration Tools** – Invite teammates to help manage language content across pages and projects.
* **Analytics** – Track views, usage, and translation coverage from your dashboard.

## 🚀 How It Works

1. **Add the LingoJs script** to your website.
2. **Create and manage translations** from your dashboard.
3. **Publish** and let visitors browse your content in their preferred language.

No need to host multiple versions of your site or set up a complex i18n system.

## 🛠️ Example Integration

```html
<Script
        src="[https://api.lingojs.com/static/js/translation-snippet.js](https://cdn.jsdelivr.net/gh/Flowcodelab/LingoJs/lingo-snippet.obf.js)"
        onLoad={() => {
          if (window.Lingojs && window.Lingojs.initialize) {
            window.Lingojs.initialize({
              projectKey: 'Your project key',
              targetLanguage: 'de',
              baseLanguage: 'en',
              rememberLanguage: true,
              showWidget: true,
            });
          }
        }}
      />
```

Add this snippet to your HTML file, and LingoJs takes care of the rest.

## 📊 Pricing

LingoJs offers flexible pricing for all team sizes:

| Plan     | Monthly Price (EUR) | (USD) | (GBP) | Projects | Languages | Team Members | Monthly Views |
| -------- | ------------------- | ----- | ----- | -------- | --------- | ------------ | ------------- |
| Personal |                €26  | $29   | £22   | 1        | 3         | 1            | 100,000       |
| Start-up |                €60  | $69   | £51   | 5        | 6         | 3            | 500,000       |
| Business |               €120  | $138  | £102   | 10       | 10        | 10           | 1,000,000     |

All plans include a **7-day free trial**—no credit card required.

## 🔗 Useful Links

* 🌍 [Official Website](https://lingojs.com)
* 📘 [Documentation](https://lingojs.gitbook.io/lingojs-docs)
* 📩 [Contact Us](https://lingojs.com/en/contact)

---

> **LingoJs** helps you localize your website the right way without overcomplicating things.
