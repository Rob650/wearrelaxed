# Wear Relaxed — landing page

One static page. No build step, no server, no dependencies.

## What's in here

| File | What it does |
|---|---|
| `index.html` | The entire website. Everything lives in this one file. |
| `favicon.svg` | The little icon in the browser tab. |
| `CNAME` | Tells GitHub Pages the site lives at wearrelaxed.com. Leave it alone. |
| `.nojekyll` | Stops GitHub from processing the files. Leave it alone. |
| `robots.txt` | Lets Google index the page. |
| `sitemap.xml` | Helps Google find the page. |

---

## Put it online — GitHub Pages

**1. Create the repository**
Go to github.com → sign in → click **New repository** (green button).
Name it `wearrelaxed`. Set it to **Public**. Click **Create repository**.

**2. Upload the files**
On the new repo page, click **uploading an existing file**.
Drag in *all* the files from this folder — including the ones starting with a dot.
Click **Commit changes**.

*(If `.nojekyll` won't drag, skip it. Everything still works.)*

**3. Turn on Pages**
In the repo, click **Settings** → **Pages** in the left sidebar.
Under "Build and deployment," set Source to **Deploy from a branch**, branch to **main**, folder to **/ (root)**. Save.

Wait about a minute. Your site is live at `yourusername.github.io/wearrelaxed`.

**4. Connect wearrelaxed.com**
Still in Settings → Pages, under "Custom domain," type `wearrelaxed.com` and Save.

Then log in wherever you bought the domain and open its DNS settings. Add these:

| Type | Name | Value |
|---|---|---|
| A | @ | 185.199.108.153 |
| A | @ | 185.199.109.153 |
| A | @ | 185.199.110.153 |
| A | @ | 185.199.111.153 |
| CNAME | www | yourusername.github.io |

Replace `yourusername` with your actual GitHub username.

**5. Turn on HTTPS**
Back in Settings → Pages, wait for the domain check to pass (can take 15 minutes to a few hours), then tick **Enforce HTTPS**.

Done. The site is live.

---

## Making changes later

Open `index.html` on GitHub, click the pencil icon, edit, click **Commit changes**. The live site updates in under a minute.

Things you'll likely want to change:
- The Instagram handle — search the file for `wearrelaxed` and replace both links.
- The year in the footer — search for `© 2026`.
- Adding an email signup — that gets added back later when you pick a provider.
