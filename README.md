# 💖 To You — Interactive Romantic Love Message Web App

An adorable, aesthetic, and interactive romantic website to express your love, care, and appreciation to someone truly special.

Built with clean HTML5, CSS3 Glassmorphism, and Vanilla JavaScript with dreamy animations, custom music, adorable reaction stickers, and a personalized name prompt.

---

## ✨ Features

- 💌 **Personalized Touch**: Prompts for their name when tapping the glowing heart and personalizes the messages with glowing handwritten cursive typography.
- 🧸 **Cute Reaction Stickers**: Animated cute GIF stickers (pandas, cats, bunnies) that react and change with every slide.
- 📱 **Smooth Card Slideshow**: Romantic glassmorphic swipeable cards with slide indicators (`1 / 9`).
- 🎵 **Romantic Background Music**: Built-in music player with a floating toggle button (`Play / Pause`) and automatic graceful CDN fallback if offline or local file is missing.
- 💖 **Ambient Floating Hearts & Sparkles**: Continuous drifting hearts plus an interactive click-anywhere sparkle effect (`💖`, `✨`, `🌸`, `💕`).
- 🤗 **Self-Contained Romantic Ending**: No third-party redirects! Concludes with a heartfelt love letter card offering interactive options to **"Send a Virtual Hug 🤗"** or **"Read Again 🔄"**.
- 📱 **100% Mobile & Desktop Responsive**: Looks stunning on iPhones, Android phones, tablets, and desktop browsers.
- 🆓 **100% Free Hosting**: Ready to deploy in under 2 minutes on **GitHub Pages**.

---

## 🚀 How to Upload & Host on GitHub for FREE (Step-by-Step)

You can host this website completely for free with your own custom link using **GitHub Pages**! Follow these simple steps:

### Option A: Using the GitHub Website (Easiest — No coding or terminal needed!)

#### Step 1: Create a GitHub Account & New Repository
1. Go to [github.com](https://github.com/) and sign in (or create a free account).
2. Click the **`+`** icon in the top-right corner and select **"New repository"**.
3. Repository name: Enter something cute like `to-you` or `my-love`.
4. Set visibility to **Public** (required for free GitHub Pages).
5. Click **"Create repository"**.

#### Step 2: Upload Files
1. On your new repository page, click the link that says **"uploading an existing file"**.
2. Drag and drop all the files from this folder:
   - `index.html`
   - `README.md`
   - The entire `assets` folder (make sure all images and GIFs inside are included!)
   - *(Optional)* Your `thousand.mp3` song file
3. Click the green **"Commit changes"** button at the bottom.

#### Step 3: Turn on GitHub Pages (Free Hosting!)
1. In your GitHub repository, click on **Settings** (tab at the top).
2. In the left sidebar, click on **Pages** (under the "Code and automation" section).
3. Under **Build and deployment** > **Branch**:
   - Change `None` to **`main`** (or `master`).
   - Keep the folder as `/(root)`.
   - Click **Save**.
4. Wait about 1–2 minutes, then refresh the page.
5. You will see a banner at the top saying:
   > **"Your site is live at `https://<your-username>.github.io/<repository-name>/`"**
6. Copy that link and send it to your special someone! 💕

---

### Option B: Using Git Command Line (For developers)

If you have Git installed on your computer:

```bash
# 1. Initialize git
git init

# 2. Add all files
git add .

# 3. Commit
git commit -m "feat: Initial commit for romantic love message web app"

# 4. Link your GitHub repository
git branch -M main
git remote add origin https://github.com/<your-username>/<your-repo-name>.git

# 5. Push to GitHub
git push -u origin main
```

Then go to **Settings > Pages** on GitHub and enable deployment from the `main` branch.

---

## 🎨 How to Customize This Website

All settings and text can be easily customized inside [`index.html`](index.html):

### 1. Change the Slides & Messages
Open `index.html` and search for `<div id="pergeseran">`. Each slide is wrapped in a `<p>` tag:
```html
<!-- Message 2 -->
<p><b>
  <span>Don't forget to<br>always take care of your health 😍</span>
</b></p>
```
You can edit the text to say whatever you'd like!

### 2. Change the Song / Background Music
- Place any `.mp3` file named `thousand.mp3` directly in the root directory.
- Or open `index.html` and change the audio URL:
  ```javascript
  const localMusic = "your-song.mp3";
  ```

### 3. Change Background Wallpaper
- Replace `assets/wp.jpg` with your favorite photo or your picture together.
- Keep the filename `wp.jpg`, or update the path in `index.html` line `<img src="./assets/wp.jpg" id="wallpaper"/>`.

### 4. Change Stickers
Browse the `assets/` folder to see all included animated GIFs:
- `pusn.gif`, `hearthappy.gif`, `bunga.gif`, `cilukba.gif`, `ngumpet.gif`, `pandacoklat.gif`, `0906-peacegoma.gif`, `weee.gif`, `mmua.gif`, `ciumin.gif`, and more.
- In `index.html`, customize the `stickerList` array to choose which sticker appears on each slide!

---

## 📂 File Structure

```text
Toyou-main/
├── assets/
│   ├── 0906-peacegoma.gif
│   ├── bunga.gif
│   ├── cilukba.gif
│   ├── ciumin.gif
│   ├── hearthappy.gif
│   ├── mmua.gif
│   ├── ngumpet.gif
│   ├── pandacoklat.gif
│   ├── pusn.gif
│   ├── weee.gif
│   ├── wp.jpg          <-- Background wallpaper
│   └── ... (additional gifs & assets)
├── index.html          <-- Main website (HTML + CSS + JavaScript)
└── README.md           <-- Documentation & GitHub setup guide
```

---

## 💡 Tech Stack
- **HTML5**: Semantic layout & SEO friendly
- **Vanilla CSS**: Modern Glassmorphism, animations, keyframes, responsive design
- **Vanilla JavaScript**: Interactive modals, audio handling, particle physics
- **SweetAlert2**: Dreamy dialogs & customized prompts
- **Google Fonts**: Caveat & Poppins typography

---

## 💌 Made with Love
Created to spread smiles, warmth, and happiness. Feel free to star ⭐ this repository and share it with someone you love!
