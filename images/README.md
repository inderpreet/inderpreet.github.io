# 📸 Images Directory

## Structure

```
images/
├── posts/          # Images used within post content
│   ├── post-1/     # Organized by post
│   ├── post-2/
│   └── shared/     # Images used across multiple posts
└── featured/       # Featured images for post headers
```

## Usage

### Featured Images (Post Headers)

In your markdown frontmatter:

```yaml
image: "/images/featured/my-image.jpg"
```

### Content Images (Within Posts)

In your markdown content:

```markdown
![Description](/images/posts/my-post/diagram.png)
```

## Guidelines

- **Featured images**: 1200x630px recommended
- **Content images**: Max 1000px width
- **File size**: < 500KB per image
- **Formats**: JPG (photos), PNG (screenshots), SVG (diagrams)

## Optimization

Before adding images:
1. Resize to appropriate dimensions
2. Compress with [TinyPNG](https://tinypng.com/)
3. Use descriptive filenames
4. Add proper alt text

See `IMAGE-WORKFLOW.md` for complete documentation.

