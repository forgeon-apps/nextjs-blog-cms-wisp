# ✨ Next.js 15 Blog + Wisp CMS for Forgeon

A polished, content-first blog starter powered by **Next.js 15**, **React Server Components**, and **Wisp CMS** — ready to launch on **Forgeon**.

[![Deploy with Forgeon](https://forgeon.io/images/button-deploy/png/deploy-to-forgeon-6.png)](https://forgeon.io/projects?import=1&no_upload=1&auto=0&git_url=https%3A%2F%2Fgithub.com%2FWisp-CMS%2Fnextjs-blog-cms-wisp)

Live Demo → **[https://nextjs-blog-cms-wisp.forgeon.io/](https://nextjs-blog-cms-wisp.forgeon.io/)**

---

## 🚀 Prerequisites

Before you begin:

* **Node.js** installed
* **npm / pnpm** installed
* A **Wisp CMS** account
* A valid **`NEXT_PUBLIC_BLOG_ID`** from your Wisp setup

---

## 🧪 Develop Locally

Install dependencies:

```bash
npm install
````

Create your environment file:

```bash
cp .env.example .env
```

Set your blog ID:

```env
NEXT_PUBLIC_BLOG_ID=your_blog_id_here
```

Then run the app:

```bash
npm run dev
```

Open:

```bash
http://localhost:3000
```

---

## 🏗️ Build Locally

Make sure your environment is set:

```bash
cp .env.example .env
```

Add your Wisp blog ID:

```env
NEXT_PUBLIC_BLOG_ID=your_blog_id_here
```

Then build:

```bash
npm run build
```

---

## 🌩️ Deploy to Forgeon

You can deploy this project directly on Forgeon.

### Option 1 — One-click import

Click the button below:

[![Deploy with Forgeon](https://forgeon.io/images/button-deploy/png/deploy-to-forgeon-6.png)](https://forgeon.io/projects?import=1&no_upload=1&auto=0&git_url=https%3A%2F%2Fgithub.com%2FWisp-CMS%2Fnextjs-blog-cms-wisp)

### Option 2 — Deploy with CLI

```bash
npm install
forge deploy
```

Before deploying, make sure you add this environment variable in Forgeon project settings:

```env
NEXT_PUBLIC_BLOG_ID=your_blog_id_here
```

Forgeon will:

* Detect your **Next.js** runtime
* Build and deploy your app
* Assign a preview domain
* Stream logs in real time

Minimal friction, maximum publishing energy.

---

## 🔑 Required Environment Variable

This starter needs the following variable to work correctly:

```env
NEXT_PUBLIC_BLOG_ID=your_blog_id_here
```

You can get this value from your **Wisp CMS** setup page.

Without it, the blog cannot fetch your content during build/runtime.

---

## ✨ Features

* Beautiful blog starter kit using **Next.js 15**
* **React Server Components**
* Responsive design for mobile and desktop
* Filter posts by tags
* About page
* Light & dark mode
* Automatic sitemap generation
* Automatic Open Graph image generation
* Related post suggestions
* RSS feed support

---

## 🧰 Technologies

* **Next.js 15**
* **React 19**
* **TypeScript**
* **Tailwind CSS**
* **Shadcn UI**
* **Wisp CMS**

---

## 📚 Helpful Links

* **Demo Blog** → [https://blog-demo.wisp.blog/](https://blog-demo.wisp.blog/)
* **Feature Walkthrough** → [https://youtu.be/7wVYAGhDmdY](https://youtu.be/7wVYAGhDmdY)
* **Editing Experience** → [https://youtu.be/uSKO8J38T98](https://youtu.be/uSKO8J38T98)
* **Documentation** → [https://www.wisp.blog/docs/next-js-blog-starter-kit/overview](https://www.wisp.blog/docs/next-js-blog-starter-kit/overview)

---

## 💡 Notes for Forgeon Users

If your project uses a custom Dockerfile and needs build-time access to `NEXT_PUBLIC_BLOG_ID`, make sure the Dockerfile builder stage includes:

```dockerfile
ARG NEXT_PUBLIC_BLOG_ID
ENV NEXT_PUBLIC_BLOG_ID=$NEXT_PUBLIC_BLOG_ID
```

That helps ensure the value is available during `next build`.

---

## 🔘 One-Click Deploy

Launch this blog on Forgeon instantly:

[![Deploy with Forgeon](https://forgeon.io/images/button-deploy/png/deploy-to-forgeon-6.png)](https://forgeon.io/projects?import=1&no_upload=1&auto=0&git_url=https%3A%2F%2Fgithub.com%2FWisp-CMS%2Fnextjs-blog-cms-wisp)

Write beautifully. Deploy shamelessly. Rule your content kingdom.

```

Kalau kamu mau, aku juga bisa bikin versi yang lebih:
- **lebih marketing**
- **lebih clean ala open-source**
- atau **lebih Forgeon banget** dengan section khusus `Environment Variables on Forgeon`.
```
