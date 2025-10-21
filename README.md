# Week 2 Project: Build the charity: water Landing Page
To get started, create a new Codespace from this repo.

In this Project, you’ll transform your Canva mockup into a fully functional landing page using HTML and CSS. This is your chance to take your creative concept — with your brand visuals, your messaging, and your imagery — and make it real. You'll build a site that not only looks great, but also educates, inspires, and drives action.

With help from AI to jumpstart your layout, you'll focus on structuring your content, applying your brand style, and creating a polished final product that reflects your vision. By the end of this Project, you’ll have a live, interactive page deployed to the web. You can share this work when you want to showcase your technical skills and your passion for digital storytelling. 

## charity: water Brand Colors & Fonts

### Primary Colors:
- Yellow:     `#FFC907`
- Blue:       `#2E9DF7`

### Secondary Colors:
- Light Blue: `#8BD1CB`
- Green:      `#4FCB53`
- Orange:     `#FF902A`
- Red:        `#F5402C`
- Dark Green: `#159A48`
- Pink:       `#F16061`

### Fonts:
- Proxima Nova
- Avenir

## Quick local preview & image workflow

Follow these steps to preview the site locally and add images into the project.

1. Start a simple local server from the repository root (Python 3):

```bash
python3 -m http.server 8000
```

2. Open your browser and go to:

```
http://localhost:8000
```

This serves the files so images load correctly and relative paths work in all browsers.

Preview an image before adding it
- Open `add-image.html` in the browser (via the same server). Use the file input to preview a JPG from your computer without copying it into the repo.

Add an image to the project
- Copy or drag your file into the `img/` or `img2/` folder in VS Code.
- Use a simple terminal command to copy a file into the project:

```bash
cp /path/to/your-file.jpg img/your-file.jpg
```

Use the image in an HTML file

```html
<img src="img/your-file.jpg" alt="Description" class="placeholder-img">
```

Commit images to Git (optional)

```bash
git add img/your-file.jpg
git commit -m "Add image: your-file.jpg"
git push
```

Tips
- Keep image filenames lowercase with dashes (no spaces).
- Add descriptive `alt` text for accessibility.
- Optimize images for web (aim for under 200–300 KB when possible).

If you'd like, I can add an example image into `img2/`, or insert a selected image into `index.html` for you.