# Personal Academic Website

This repository contains a one-page personal website for a PhD student in statistics.

## Edit your content

Open `index.html` and replace:

- `Your Name`
- `your.email@university.edu`
- `Your University`
- Google Scholar and CV links
- Publications, interests, and CV entries

## Top banner image

The top banner now uses a local image:

- `/Users/qqqq/MyWebsite/assets/xiji.png`

Put your selected artwork file at that path (same filename), and it will display automatically.

## Host on GitHub Pages

1. Create a new GitHub repository, for example `yourname.github.io`.
2. Push this folder to that repository.
3. In GitHub: **Settings -> Pages**.
4. Under **Build and deployment**, choose:
   - Source: `Deploy from a branch`
   - Branch: `main` and folder `/ (root)`
5. Save. Your site will appear at:
   - `https://yourname.github.io/`

If your repository is not named `yourname.github.io`, the URL will be:

- `https://yourname.github.io/repository-name/`

## Optional local preview

You can preview quickly with:

```bash
python3 -m http.server 8000
```

Then open `http://localhost:8000`.
