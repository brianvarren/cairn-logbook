# CAIRN Field Log

Development logbook for CAIRN instruments.

## One-time setup

### 1. Push to GitHub

```bash
git init
git add .
git commit -m "Initial commit"
git remote add origin git@github.com:YOUR_USERNAME/cairn-blog.git
git push -u origin main
```

### 2. Deploy to Netlify

1. Go to [netlify.com](https://netlify.com) and sign in with GitHub
2. Click "Add new site" → "Import an existing project"
3. Select your `cairn-blog` repo
4. Build settings are auto-detected from `netlify.toml`. Click "Deploy"

### 3. Enable Identity (auth)

1. In Netlify, go to your site → "Integrations" → "Identity" → "Enable Identity"
2. Under "Registration", select "Invite only"
3. Under "Services" → "Git Gateway", click "Enable Git Gateway"
4. Go to "Identity" tab → "Invite users" → enter your email
5. Check your email, accept the invite, set a password

### 4. Done

Go to `yoursite.netlify.app/admin` and log in. Write posts. They auto-deploy.

---

## Local development

```bash
npm install
npm start
```

Site runs at `http://localhost:8080`

---

## Structure

```
src/
  posts/       ← Your log entries (markdown)
  images/      ← Uploaded images
  admin/       ← CMS config
  css/         ← Styles
  _includes/   ← Templates
```

## Adding video embeds

In a post, paste the embed code directly:

```markdown
Here's a demo:

<iframe width="560" height="315" src="https://www.youtube.com/embed/VIDEO_ID" frameborder="0" allowfullscreen></iframe>
```

The CMS markdown editor supports raw HTML.
