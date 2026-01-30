# Hugo Template

A Hugo starter template with a dev container environment and a minimal "under construction" placeholder theme.

## First Steps

### 1. Preview the Site

Start the Hugo development server to see the placeholder page:

```bash
hugo server
```

Visit [http://localhost:1313](http://localhost:1313) to view your site.

### 2. Choose a Theme

Browse the official Hugo themes gallery to find a theme that fits your needs:

👉 **[https://themes.gohugo.io/](https://themes.gohugo.io/)**

### 3. Add a Theme as a Git Submodule

Once you've chosen a theme, add it to your project as a git submodule:

```bash
git submodule add <theme-repo-url> themes/<theme-name>
```

**Example** (adding the PaperMod theme):

```bash
git submodule add https://github.com/adityatelange/hugo-PaperMod.git themes/PaperMod
```

### 4. Update Configuration

Edit `hugo.yaml` to use your new theme:

```yaml
baseURL: "https://your-site-url.com/"
languageCode: "en-us"
title: "Your Site Title"
theme: PaperMod  # Change this to your theme name
```

Each theme has its own configuration options—refer to the theme's documentation for details.

### 5. Add Content

Create your first post:

```bash
hugo new posts/my-first-post.md
```

### 6. Build for Production

Generate the static site files:

```bash
hugo
```

The output will be in the `public/` directory.

---

## Switching Back to Under Construction

Need to take your site offline temporarily? Simply change the theme back in `hugo.yaml`:

```yaml
theme: under-construction
```

## Useful Commands

| Command | Description |
|---------|-------------|
| `hugo server` | Start development server with live reload |
| `hugo server -D` | Include draft content |
| `hugo new <path>` | Create new content |
| `hugo` | Build the site |

## Resources

- [Hugo Documentation](https://gohugo.io/documentation/)
- [Hugo Themes](https://themes.gohugo.io/)
- [Hugo Discourse Forum](https://discourse.gohugo.io/)
