# Opened Scripture — GitHub Pages Setup Guide

A complete step-by-step guide to publishing your website live for free using GitHub Pages.

-----

## What You Have

|File             |Purpose                                      |
|-----------------|---------------------------------------------|
|`index.html`     |Your main website (homepage + subscribe form)|
|`newsletter.html`|Your private newsletter writing tool         |
|`README.md`      |This guide                                   |

-----

## STEP 1 — Create a Free GitHub Account

1. Go to **https://github.com**
1. Click **“Sign up”** in the top right
1. Enter your email, create a password, and choose a username
- Tip: Your username becomes part of your URL, e.g. `yourusername.github.io`
1. Verify your email and complete setup

-----

## STEP 2 — Create a New Repository

A “repository” (repo) is just a folder on GitHub that holds your website files.

1. Once logged in, click the **”+”** icon in the top right corner
1. Click **“New repository”**
1. Fill in the form:
- **Repository name:** `opened-scripture` *(or any name you like)*
- **Description:** “Opened Scripture newsletter website” *(optional)*
- Set visibility to **Public** *(required for free GitHub Pages)*
- Check **“Add a README file”** — this creates the repo automatically
1. Click **“Create repository”**

-----

## STEP 3 — Upload Your Files

1. On your new repository page, click **“Add file”** → **“Upload files”**
1. Drag and drop (or click “choose your files”) to upload:
- `index.html`
- `newsletter.html`
1. Scroll down and click **“Commit changes”**
- Leave the commit message as-is, or type something like “Initial upload”
- Click the green **“Commit changes”** button

Your files are now saved in GitHub.

-----

## STEP 4 — Enable GitHub Pages

This is what makes your site go live on the internet — for free.

1. On your repository page, click the **“Settings”** tab (near the top)
1. In the left sidebar, scroll down and click **“Pages”**
1. Under **“Branch”**, click the dropdown that says “None” and select **“main”**
1. Leave the folder as **”/ (root)”**
1. Click **“Save”**

GitHub will now build your site. This takes about 1–2 minutes.

-----

## STEP 5 — Find Your Live URL

1. After saving, stay on the Pages settings page
1. Refresh after 1–2 minutes
1. A green banner will appear at the top saying:

> **“Your site is live at https://yourusername.github.io/opened-scripture/”**
1. Click that link — your Opened Scripture website is now live!

**Your two pages will be at:**

- `https://yourusername.github.io/opened-scripture/` → Main website
- `https://yourusername.github.io/opened-scripture/newsletter.html` → Newsletter editor

-----

## STEP 6 — Update Your Files (When You Make Changes)

When you want to update content or fix something:

1. Go to your repository on github.com
1. Click on the file you want to edit (e.g. `index.html`)
1. Click the **pencil icon** (Edit) in the top right of the file view
1. Make your changes
1. Scroll down and click **“Commit changes”**
1. Your live site updates automatically within 1–2 minutes

Or, to replace the whole file:

1. Click **“Add file”** → **“Upload files”**
1. Upload your updated file (same filename)
1. Check **“Commit changes”** — it will overwrite the old version

-----

## HOW TO WRITE & SEND YOUR NEWSLETTER

### Every Tuesday, here’s your workflow:

**1. Open your newsletter editor:**

- Go to `https://yourusername.github.io/opened-scripture/newsletter.html`

**2. Fill in the form on the left:**

- Issue number and date
- Opening verse and reference
- Your articles (title, body, verse for each)
- Deep Dive section
- Closing note

**3. Click “Update Preview” to see it render**

**4. When ready, click “Copy HTML”**

- A box pops up with your complete newsletter HTML
- Click “Copy to Clipboard”

**5. Paste into Beehiiv (RECOMMENDED — free up to 2,500 subscribers):**

- Go to **https://beehiiv.com** and create a free account
- Click **“New Post”**
- In the editor, look for the **”<> HTML”** or **“Custom HTML”** block option
- Paste your copied HTML
- Add your subject line (e.g. “Issue #13 — Anxiety & the Sovereignty of God”)
- Click **“Send”** or **“Schedule”**

-----

## CONNECTING YOUR SUBSCRIBE FORM TO BEEHIIV

Right now the subscribe form on your website shows a confirmation message but doesn’t actually save emails. Here’s how to connect it to Beehiiv so subscribers are real:

1. In Beehiiv, go to **Settings → Publication Settings → Subscribe Page**
1. Copy your **Beehiiv embed code** or **subscribe URL**
1. In your `index.html`, find this line:
   
   ```html
   <form class="subscribe-form" onsubmit="handleHeroSubscribe(event)">
   ```
1. Replace the `onsubmit` action with Beehiiv’s form action URL, OR
1. Replace the entire form with Beehiiv’s embed snippet

Beehiiv provides copy-paste embed code — no coding knowledge needed.

-----

## OPTIONAL: GET A CUSTOM DOMAIN

Instead of `yourusername.github.io/opened-scripture`, you can use `openedscripture.com` or similar.

1. Buy a domain from **Namecheap** (~$10/year) or **Google Domains**
1. In GitHub Pages settings, enter your custom domain under “Custom domain”
1. Follow GitHub’s DNS setup instructions (they walk you through it)

-----

## TIPS

- **Keep your newsletter editor private** — only share `index.html` publicly. Your `newsletter.html` editor is just for you.
- **Back up your issues** — after writing each issue, save the copied HTML to a folder on your computer.
- **Subject lines matter** — the best open rates come from subject lines that name the topic, e.g. “What the Bible Says About Anxiety” beats “Issue #13.”
- **Consistency wins** — pick a day (Tuesday works well) and stick to it.

-----

## NEED HELP?

- GitHub Pages docs: https://docs.github.com/en/pages
- Beehiiv help: https://support.beehiiv.com
- GitHub beginner guide: https://docs.github.com/en/get-started

-----

*“He opened their minds to understand the Scriptures.” — Luke 24:45*
