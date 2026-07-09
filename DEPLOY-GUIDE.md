# How to put this site live for FREE (GitHub Pages)

Your site will be live at: **https://YOUR-USERNAME.github.io** — publicly accessible, works for Amazon Associates application.

## Steps (15 minutes, one time)

1. **Make a GitHub account** at github.com (free). Pick a clean username — it becomes your site address. Example: `laptopsahi` → site becomes `laptopsahi.github.io`

2. **Create a new repository:**
   - Click the "+" (top right) → "New repository"
   - Repository name must be EXACTLY: `YOUR-USERNAME.github.io` (e.g. `laptopsahi.github.io`)
   - Keep it Public → click "Create repository"

3. **Upload the site files:**
   - On the repository page, click "uploading an existing file"
   - Drag ALL files and folders from this zip (index.html, about.html, disclosure.html, css folder, articles folder)
   - IMPORTANT: keep the folder structure same — css and articles must stay as folders
   - Click "Commit changes"

4. **Wait 2-3 minutes**, then open `https://YOUR-USERNAME.github.io` in your browser. Site is live.

## Before applying to Amazon Associates

- [ ] Replace `contact.laptopsahi@gmail.com` in about.html and disclosure.html with your real email
- [ ] Add 6-10 MORE articles over the next 2-3 weeks (Amazon likes to see an active site, not one made yesterday). Article ideas:
  - Best laptops under ₹40,000 / ₹50,000
  - ThinkPad T-series buying guide for students
  - How to check a used laptop's battery health (powercfg guide with screenshots)
  - Typing test practice: which keyboard type is best
  - Laptop vs tablet for online classes
  - How to make an old laptop faster (SSD + RAM upgrade guide)
- [ ] Add real photos from your shop/bench to articles — original photos massively boost credibility
- [ ] Then apply at affiliate-program.amazon.in with your github.io URL

## After Amazon approves

- Replace the placeholder text with real affiliate links using Amazon SiteStripe
- You MUST make 3 qualifying sales within 180 days or the account closes
- Keep the disclosure page — it's mandatory per Amazon's rules

## Later upgrade (optional, ~₹500/year)

Buy a .in domain from Hostinger/GoDaddy/BigRock, then in your GitHub repo:
Settings → Pages → Custom domain → enter your domain. Your site moves to yourdomain.in with zero rebuild.

## How to add a new article

1. Copy any file from the `articles` folder
2. Rename it (e.g. `battery-health-check.html`)
3. Edit the title, heading, and content (any text editor works, or ask Claude to write it)
4. Add a new `<a class="article-card">` block on index.html pointing to it
5. Upload the changed files to GitHub the same way as step 3 above
