# shrimpi-public

Shrimpi Public Media - A CDN-ready repository for hosting images and videos via jsDelivr.

## 📁 Repository Structure

```
shrimpi-public/
├── images/          # Image files (PNG, JPG, GIF, SVG, etc.)
└── videos/          # Video files (MP4, WEBM, etc.)
```

## 🚀 Usage with jsDelivr

jsDelivr is a free CDN that can serve files directly from this GitHub repository. Files are automatically cached and distributed globally.

### Basic URL Format

```
https://cdn.jsdelivr.net/gh/dannysombrero/shrimpi-public@latest/<path-to-file>
```

### Examples

**Images:**
```html
<!-- Using specific commit (recommended for production) -->
<img src="https://cdn.jsdelivr.net/gh/dannysombrero/shrimpi-public@ed6c506/images/banner.jpg" alt="Banner">

<!-- Using specific version/tag (recommended for production) -->
<img src="https://cdn.jsdelivr.net/gh/dannysombrero/shrimpi-public@v1.0.0/images/icon.svg" alt="Icon">

<!-- Using latest version (development only) -->
<img src="https://cdn.jsdelivr.net/gh/dannysombrero/shrimpi-public@latest/images/logo.png" alt="Logo">
```

**Videos:**
```html
<!-- Video element with specific commit -->
<video controls>
  <source src="https://cdn.jsdelivr.net/gh/dannysombrero/shrimpi-public@ed6c506/videos/intro.mp4" type="video/mp4">
</video>

<!-- Direct link with specific tag -->
<a href="https://cdn.jsdelivr.net/gh/dannysombrero/shrimpi-public@v1.0.0/videos/tutorial.mp4">Watch Tutorial</a>
```

### URL Options

- `@latest` - Always serves the latest version (main branch)
- `@<commit-hash>` - Serves files from a specific commit (immutable)
- `@<tag>` - Serves files from a specific release tag (immutable)
- `@<branch>` - Serves files from a specific branch

**Tip:** For production use, always use specific commits or tags to ensure immutability and prevent unexpected changes.

## 📦 Adding Files

1. Clone this repository
2. Add your media files to the appropriate directory:
   - Images go in `/images/`
   - Videos go in `/videos/`
3. Commit and push your changes
4. Wait a few minutes for jsDelivr to update its cache
5. Access your files via the CDN URL

## 🎯 File Organization

### Recommended Structure

```
images/
├── logos/
│   ├── logo-light.png
│   └── logo-dark.png
├── banners/
│   └── hero-banner.jpg
└── icons/
    └── favicon.ico

videos/
├── tutorials/
│   └── getting-started.mp4
└── demos/
    └── product-demo.mp4
```

## 📝 Best Practices

1. **File Naming:** Use lowercase with hyphens (e.g., `my-image.png`)
2. **File Size:** Optimize media files before uploading
   - Images: Use appropriate formats (WebP, PNG, JPG)
   - Videos: Compress videos for web delivery
3. **Organization:** Use subdirectories for better organization
4. **Versioning:** Tag releases for important updates
5. **Caching:** Remember that jsDelivr caches files - use specific commits for immediate updates

## 🔗 Useful Links

- [jsDelivr Documentation](https://www.jsdelivr.com/documentation)
- [jsDelivr GitHub Features](https://www.jsdelivr.com/features)
- [Purge Cache](https://www.jsdelivr.com/tools/purge) - Force cache refresh if needed

## 📄 License

This repository is public and the media files are intended for use with the associated website.
