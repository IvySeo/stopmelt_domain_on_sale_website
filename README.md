# **Domain For Sale – Website README**

This project contains a **minimal, polished one-page website** announcing that a domain is available for purchase.
The page includes a contact email button and clean modern styling using only HTML and CSS — no frameworks or external build tools.

---

## **📁 Project Structure**

```
domain-for-sale-site/
│
└── index.html     # Main and only file needed for deployment
```

There are **no dependencies**, **no JavaScript**, and **no build process**.
Any static hosting service can publish this site.

---

## **🌐 What the Website Does**

* Displays a modern message that the domain is available for sale.
* Shows a clean call-to-action button that opens a pre-filled email to the seller.
* Works on desktop and mobile with a responsive layout.
* Uses a light/dark adaptive color scheme.

---

## **✏️ How to Edit the Page**

Open `index.html` in any editor (VS Code, Notepad, etc.) and update:

### **1. Contact Email**

Search for:

```
ivyhrs27@gmail.com
```

Replace with your new contact email if needed.

---

### **2. Headline Text / Description**

Inside `<h1>` and `<p class="subtitle">`, change the wording to whatever message you prefer.

---

### **3. Domain Name**

If you want the domain name displayed on the page:

Search for:

```
This domain is currently for sale
```

Modify the text to:

```
example.com is currently for sale
```

---

## **🚀 How to Publish the Website (Free & Simple)**

You can publish this website **free** using Cloudflare Pages or GitHub Pages.

---

## **Option A – Cloudflare Pages (Recommended)**

Best if your domain is already in Cloudflare DNS.

### **1. Upload the site**

1. Log into Cloudflare
2. Go to **Pages**
3. Click **Create Project → Upload Assets**
4. Upload the whole folder (`domain-for-sale-site`)
5. Deploy

Cloudflare gives you a temporary URL like:

```
yourproject.pages.dev
```

---

### **2. Connect Your Domain**

1. Go to **Pages → Your Project → Custom Domains**
2. Add your domain (example: `yourdomain.com`)
3. Cloudflare automatically creates DNS records
4. Wait ~5 minutes for DNS to update

Your domain now shows the website.

---

## **Option B – GitHub Pages (Free)**

### **1. Create a repo**

1. Go to GitHub, create a repository
2. Upload `index.html`

### **2. Enable Pages**

1. Repo → **Settings → Pages**
2. Source: **Deploy from a Branch**
3. Select branch: `main`
4. Save

GitHub provides a URL like:

```
https://yourusername.github.io/domain-for-sale/
```

### **3. Add Your Domain**

1. Under **Pages**, add your custom domain
2. GitHub shows DNS records you need to add
3. Add them where your domain is managed (Cloudflare, GoDaddy, etc.)

---

## **🧹 Updating the Website Later**

To make changes:

1. Edit `index.html`
2. Re-upload to Cloudflare Pages **OR** push updates to GitHub
3. The published site updates instantly (Cloudflare) or within 1–2 minutes (GitHub)

---

## **🛠️ Troubleshooting**

### **Website not updating?**

* On Cloudflare Pages, redeploy by uploading the folder again.
* On GitHub Pages, make sure the updated file is on the `main` branch.

### **Domain not loading the page?**

* DNS may need a few minutes to update.
* Ensure the domain points to Cloudflare or GitHub correctly.
* Clear browser cache or use incognito mode.

---

## **✔️ Summary**

This project is intentionally simple:

* **1 file**
* **0 dependencies**
* **Free hosting options**
* **Instant updates**
* **Modern design**

Perfect for displaying a polished “domain for sale” landing page.
