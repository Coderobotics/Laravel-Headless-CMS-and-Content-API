# Laravel Headless CMS Software

Content Pro is a self-hosted Laravel 13 headless CMS. Teams model, write and publish content in a clean Livewire dashboard, and any website or app can pull that content through a secure, versioned REST API. It includes a visual content-type builder with 12 field types, a draft and publish workflow, signed preview links and a media library with safe uploads. The API uses hashed keys, rate limits and quotas, and each workspace is isolated, with five team roles enforced on the server. A built-in SaaS layer adds plans, trials, a public pricing page and a super-admin console, so you can sell content management as a service. It installs on ordinary shared hosting through a web installer and needs no Redis, queues or paid services. A ready-to-run Next.js 16 website, 104 automated tests and full documentation are included. You get the complete source code with no encryption and no domain limits, which suits developers, agencies, SaaS founders and product teams who want a WordPress or Contentful alternative they fully own.

<img src="https://www.coderobotics.com/frontend/assets/icon/laravel-headless-cms-saas-php-script.jpg">

Content Pro is a self-hosted Laravel headless CMS. Your team writes and manages content in a clean dashboard, and your websites and apps fetch it through a fast, read-only REST API. It is built with Laravel 13, Livewire 4 and Tailwind CSS 4. It comes with a multi-workspace SaaS setup, a web installer and a ready-to-run Next.js 16 website. You structure content once and publish it to any frontend.

A traditional CMS like WordPress ties your content to one website design. When you also need a mobile app or a second site, you end up copying the same content into several places. Content Pro keeps only the content. Editors model, write, upload and publish it in a friendly dashboard. Any number of frontends, such as Next.js, Nuxt, Astro, React or mobile apps, pull it through a versioned REST API. You write a product description once and it appears everywhere it’s needed. Developers keep full control of the frontend, and editors never touch code.

What You Get
 
Visual content-type builder: 12 field types (text, long text, rich text, number, decimal, boolean, date, date-time, select, image, file, relation), validation rules, drag-and-drop ordering and 7 starter templates (Blog post, Landing page, Product, Event, FAQ, Team member, Blank)
Versioned REST API (/api/v1): hashed API keys you can rotate, revoke or set to expire, plus pagination, sorting, filtering, field selection, relation includes and search
Rate limits and quotas: limits per key and per IP, monthly request quotas per workspace and consistent JSON errors
Built-in API reference: ready-to-copy cURL and JavaScript examples for each of your content types
Editorial workflow: draft and publish, forms generated from your fields, a rich-text editor, SEO and social-sharing fields, bulk actions, and a trash you can restore from
Preview: preview drafts in the dashboard or on your real website through signed links that expire after 60 minutes
Media library: real file-type checking, executable rejection, alt text and captions, usage tracking, and an optional “published content only” privacy mode
Teams: isolated workspaces, 5 roles (Owner, Admin, Editor, Author, Viewer), email invitations and workspace switching, with every permission enforced on the server
SaaS foundation: a public single-page website with live pricing, plans with limits (types, entries, members, storage, API requests), trials, a super-admin console, platform settings and a system health page
Next.js 16 starter website: home, article and category pages, draft preview, SEO metadata, and graceful error and empty states
Web installer: works on shared hosting, checks your server, creates your admin account and can load demo content. There are no default passwords.
PWA-installable dashboard with light and dark themes, fully responsive
104 automated tests covering tenant isolation, roles, the API, uploads and the installer
Full documentation: installation, user guide, API reference, deployment and security, customization and requirements traceability

Why This Tool?
 
Hosted headless CMS platforms charge per seat and per API call, and they keep your content on someone else’s servers. Content Pro runs on your own server. There are no per-request charges, nothing is sent to a third party, and the only limits are the ones you set.

Self-hosted, with no Redis, queue worker or paid service required
Runs on ordinary shared hosting (Apache or Nginx, PHP and MySQL)
Multi-tenant from day one: one installation can serve many isolated client workspaces
You can sell it as a service: plans, trials, a pricing page and a super-admin console are built in
Secure by design: hashed API keys, server-enforced roles, safe uploads and no default credentials
Includes complete source code that you can rebrand, extend and customize

Perfect For
 
Developers and freelancers who want to give clients an easy editing dashboard while they build the frontend in any framework
Agencies that run one installation with a separate, isolated workspace for each client
SaaS founders who want to launch their own content-management service with plans and usage limits
Product teams who manage content for a marketing site, docs or app in one place
Startups building a website and a mobile app that share the same content
Anyone moving from WordPress to a modern headless or Jamstack setup

Tech Stack
 
Laravel 13 (PHP 8.3+)
Livewire 4 and Alpine.js
Tailwind CSS 4 and Vite
MySQL / MariaDB
HTMLPurifier and Trix rich-text editor
Next.js 16, React 19 and TypeScript (starter website)
REST API (JSON, /api/v1)

Prerequisites
 
PHP 8.3+ with pdo_mysql, mbstring, openssl, fileinfo, gd and xml (the installer checks these for you)
MySQL 8+ or MariaDB 10.11+
Apache (mod_rewrite) or Nginx
Node.js 20.9+, needed only to run the Next.js starter or rebuild dashboard styles
Composer is not needed: PHP dependencies are included

Frequently Asked Questions – Content Pro
 
1. What is Content Pro?
Content Pro is a self-hosted Laravel headless CMS. Your team creates and manages content in a clean dashboard, and your websites and apps fetch it through a fast, read-only REST API. It also includes a multi-workspace SaaS setup and a ready-to-run Next.js website.

2. What is a headless CMS, and how is it different from WordPress?
WordPress keeps your content and your website design together. A headless CMS stores only the content and serves it through an API. Any number of frontends, such as a Next.js site, a React app or a mobile app, can show that content in their own design. You write it once and publish it everywhere.

3. Do I need coding knowledge to use it?
Editors don’t need any. They write, upload and publish through the dashboard, and content types are built visually without code. A developer is needed only to build or adapt the frontend that shows the content, and the included Next.js starter gives them a head start.

4. Can I install it on shared hosting?
Yes. Upload the files, point your domain to the public/ folder and create an empty database. The web installer then checks your server, saves your database details and creates your admin account. Composer isn’t needed because the PHP dependencies are included. It also runs locally on XAMPP.

5. What are the server requirements?
You need PHP 8.3+ (with pdo_mysql, mbstring, openssl, fileinfo, gd and xml), MySQL 8+ or MariaDB 10.11+, and Apache with mod_rewrite or Nginx. Node.js 20.9+ is needed only for the Next.js starter. No Redis, queue worker or paid service is required.

6. Is the API free to use? Are there per-request charges?
Yes, it’s free. The API runs on your own server, nothing is sent to a third party, and there are no per-request fees. The only limits are the ones you set: plan-based monthly quotas, and rate limits of 120 requests per minute per key and 240 per IP address by default.

7. Which frontends can use the content?
Any frontend that can make an HTTP request can use it, including Next.js, Nuxt, Astro, React, Vue, mobile apps and other servers. Every response has the same JSON shape, and the built-in API reference shows ready-to-copy cURL and JavaScript examples for each content type.

8. How secure is the API?
The API is private and every request needs an API key. Keys are stored hashed and can be rotated, revoked or set to expire. Rate limits and quotas protect your server, roles are enforced on the server, and uploads are checked for their real file type, with executables rejected. There are no default passwords.

9. Can I run it as a SaaS and sell it to my own customers?
Yes. It includes a public website with live pricing, plans with limits (content types, entries, members, storage and API requests), trials and a super-admin console for managing workspaces, plans and users. Payment collection isn’t built in: take payment with your own tool or gateway, then assign the plan in the admin panel.

10. Can I manage several clients from one installation?
Yes. Each client gets their own isolated workspace with separate content, media, API keys and members. Tenant isolation is covered by automated tests.

11. What user roles are available?
There’s a Super Admin for the whole platform, plus five roles inside each workspace: Owner, Admin, Editor, Author and Viewer. Authors write drafts for Editors to publish, though you can let Authors publish directly with one setting. One person can hold different roles in different workspaces.

12. Can I preview drafts before publishing?
Yes. You can preview an entry inside the dashboard, or open it on your real website through a signed preview link that expires after 60 minutes. Drafts are never visible through the public API.

13. Does it include a demo or sample content?
Yes. Tick “demo content” during installation to start with sample articles, authors and categories. A command also adds sample team members, so you can test each role.

14. What’s not included in version 1.0?
Version 1.0 doesn’t include GraphQL, webhooks, built-in payment checkout, multilingual content, scheduled publishing, version history, custom roles, SSO, image resizing or real-time collaboration. These were left out to keep Content Pro focused and easy to run.

15. Do I get the full source code? Is it encrypted?
You get the complete source code, with no encryption and no domain limitations. You can rebrand, customize and extend it, and documentation for customization and architecture is included.

16. How is it tested?
It ships with 104 automated tests covering tenant isolation, roles, the API, uploads and the installer.

17. What does the license allow?
A regular license lets you use Content Pro in one project, for personal or commercial use, by you or on behalf of a client. You can’t resell it or redistribute the source files.

18. How and when will I receive it?
It’s a one-time payment. We send the download link within 2–4 hours on working days (Monday–Friday) and within 4–8 hours on weekends.

19. Do you provide support and updates?
Yes. You get unlimited email support for one year and free updates for one year.

20. Do you offer installation?
Installation isn’t free. We can install it for you for a small fee of 5–10, depending on your server setup.

More details & download link:
https://www.coderobotics.com/product/laravel-headless-cms-and-content-api
