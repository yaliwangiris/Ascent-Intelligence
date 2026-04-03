## Overview

This homepage is built as a **single HTML file** (`index.html`) using plain HTML, CSS, and JavaScript. No frameworks, no build tools, no dependencies. Any standard web hosting provider that supports static files can serve this site.

---

## File Structure

```
index.html       ← The entire website (HTML + CSS + JS, all in one file)
README.md        ← This file
```

---

## Deploying to Namecheap

Namecheap is one of the most common hosting providers for small business websites. The steps below apply to any Namecheap shared hosting plan with cPanel access.

Similar providers with the same process include **Bluehost**, **HostGator**, **SiteGround**, and **GoDaddy** — the steps are nearly identical across all of them.

### Step-by-Step

1. **Log in to your Namecheap account**
   Go to [namecheap.com](https://www.namecheap.com) and sign in.

2. **Open cPanel**
   From your dashboard, find your hosting plan and click **Go to cPanel**.

3. **Open File Manager**
   Inside cPanel, locate the **File Manager** icon and click it.

4. **Navigate to `public_html`**
   This is the root folder of your website. Any file placed here is publicly accessible via your domain.

5. **Back up the existing site**
   Before making changes, right-click the existing `index.html` and download a copy to your computer. Keep it somewhere safe.

6. **Upload the new file**
   - Rename your homepage file to `index.html` before uploading
   - Click **Upload** in the File Manager toolbar
   - Select your `index.html` and upload it
   - If prompted, confirm that you want to overwrite the existing file

7. **Verify the site is live**
   Open your domain in a browser (e.g., `ascentintelligence.ai`). The new homepage should appear immediately. If it doesn't, try a hard refresh (`Cmd + Shift + R` on Mac, `Ctrl + Shift + R` on Windows).

---

## Making Updates

To update the site in the future:

1. Edit the `index.html` file locally
2. Upload it to `public_html` via File Manager, overwriting the previous version
3. Refresh the browser to confirm changes

Because everything is in one file, updates are straightforward — there are no separate CSS or JS files to manage.

---

## Disclaimer

> This guide is provided for **educational and instructional purposes only**. It is intended to assist with the deployment of a personally developed web project. No proprietary tools, licensed platforms, or third-party assets are redistributed herein. All trademarks, service names, and brand references (including Namecheap, Calendly, and others) are the property of their respective owners and are referenced solely for illustrative purposes. This document does not constitute legal, commercial, or professional advice. Use of this guide is at your own discretion and responsibility.

---

*Last updated: April 2026*
