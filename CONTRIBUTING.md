# Contributing Guidelines

Thank you for contributing to the Shrimpi Public Media repository!

## 🎯 Purpose

This repository hosts media files (images and videos) that are served via jsDelivr CDN for the Shrimpi website.

## 📋 Guidelines

### Before Adding Files

1. **Verify File Necessity:** Ensure the file is needed for the website
2. **Check File Size:** Keep files reasonably sized
   - Images: Preferably under 2MB
   - Videos: Preferably under 50MB
3. **Optimize Files:** Compress and optimize media before uploading
4. **Check Duplicates:** Ensure the file doesn't already exist

### File Requirements

#### Images
- **Formats:** PNG, JPG, GIF, SVG, WebP
- **Naming:** lowercase-with-hyphens.ext
- **Location:** `/images/` or appropriate subdirectory
- **Optimization:** Use tools like TinyPNG, ImageOptim, or Squoosh

#### Videos
- **Formats:** MP4 (preferred), WebM
- **Naming:** lowercase-with-hyphens.ext
- **Location:** `/videos/` or appropriate subdirectory
- **Optimization:** Use H.264/H.265 codec for MP4

### Adding Files

1. **Fork and Clone**
   ```bash
   git clone https://github.com/dannysombrero/shrimpi-public.git
   cd shrimpi-public
   ```

2. **Create a Branch**
   ```bash
   git checkout -b add-media-files
   ```

3. **Add Your Files**
   - Place files in the correct directory
   - Use subdirectories for organization

4. **Commit Changes**
   ```bash
   git add images/your-file.png
   git commit -m "Add: description of the media file"
   ```

5. **Push and Create PR**
   ```bash
   git push origin add-media-files
   ```
   Then create a Pull Request on GitHub

### Commit Message Format

- `Add: new-image.png for homepage hero`
- `Update: logo.svg with new branding`
- `Remove: unused-banner.jpg`
- `Optimize: compressed video files`

## ✅ Checklist

Before submitting your PR, ensure:

- [ ] Files are properly optimized
- [ ] File names follow the naming convention
- [ ] Files are in the correct directory
- [ ] Commit messages are descriptive
- [ ] No sensitive or copyrighted content

## 🚫 What Not to Include

- Copyrighted material without permission
- Sensitive or private information
- Extremely large files (>100MB)
- Duplicate files
- Unoptimized media files

## 📞 Questions?

If you have questions about contributing, please open an issue for discussion.

Thank you for helping maintain this repository!
