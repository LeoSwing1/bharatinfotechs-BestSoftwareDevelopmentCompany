# Bharat Infotechs — Website

A fast, dependency-free static website. No build step, no framework, no CMS —
just open `index.html` in a browser, or upload the whole folder to any static host.

## Structure

```
index.html                                 Home — hero, Services, Integrations, Pricing
careers.html                                Careers + Training program (#training)
blog.html                                   Blog index (9 articles, easy → advanced)
blog-what-is-whatsapp-api.html              Blog: WhatsApp API basics
blog-what-is-crm.html                       Blog: CRM basics
blog-pos-vs-manual-billing.html             Blog: POS vs manual billing
blog-whatsapp-crm-signs.html                Blog: signs you need a WhatsApp CRM
blog-whatsapp-api-vs-sms.html               Blog: WhatsApp API vs bulk SMS
blog-erp-vs-crm.html                        Blog: ERP vs CRM
blog-business-automation-hours-saved.html   Blog: automation ROI
blog-crm-migration-guide.html               Blog: CRM migration (advanced)
blog-unify-pos-billing-erp-crm.html         Blog: multi-branch system integration (advanced)
sitemap.xml                                 For Google Search Console
robots.txt                                  Crawler rules + sitemap pointer
```

## What's built in

- **Hero**: WebGL shader background (animated gradient + organic noise-wipe
  transitions between 4 slides), with a CSS-gradient fallback if a browser/device
  has no WebGL.
- **Services & Integrations**: WhatsApp API, CRM, ERP, Web, Android, Custom
  Software, Billing, POS — plus the 10 systems they connect to (Payment
  gateways, Email, SMS, Sheets, Webhooks, Zapier/Make, etc).
- **Careers**: 7 open roles + a highlighted Training program section
  (`careers.html#training`) for students/freshers.
- **Blog**: 9 original articles ordered easy → advanced, each with proper
  `<title>`/description/keywords, Open Graph tags, and `BlogPosting` +
  `BreadcrumbList` schema for SEO.
- **Chatbot**: floating widget on every page — instant Call/WhatsApp/Email
  buttons plus a rule-based FAQ (services, pricing, careers, training) that
  always routes real questions to a real contact method. No external API
  dependency, so it keeps working on any host.
- **Navigation**: every nav link, footer link, and cross-article link uses
  relative paths, so the site works identically whether opened directly as a
  file, hosted at a domain root, or hosted in a subfolder.

## Contact details already wired in

- Phone / WhatsApp: **+91 88407 51012**
- Email: **infotechsbharat@gmail.com**
- Address: Sector 62, Noida, Uttar Pradesh, India

