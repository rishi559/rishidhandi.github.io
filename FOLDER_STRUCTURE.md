# 📁 Portfolio Folder Structure

## Complete Repository Layout

```
rishidhandi.github.io/
│
├── 📄 index.html                    ← Your portfolio website
├── 📖 README.md                     ← Main documentation
├── 📋 QUICK_GUIDE.md                ← Quick reference
├── 📁 FOLDER_STRUCTURE.md           ← This file
│
└── 📁 assets/                       ← All assets organized here
    │
    └── 📁 images/                   ← Image folder (YOU CHANGE IMAGES HERE!)
        │
        ├── 🖼️ profile.jpg            ← Your main photo
        ├── 📖 README_IMAGES.md       ← Image management guide
        │
        └── (future images)          ← Add more images here:
            ├── project1.jpg
            ├── project2.jpg
            └── background.jpg
```

---

## 🎯 Where to Do What

### **Change Your Photo:**
📍 Location: `assets/images/profile.jpg`
📖 Guide: `assets/images/README_IMAGES.md`

### **Edit Website Content:**
📍 Location: `index.html` (in root folder)
📖 Guide: `README.md` section "Update Text Content"

### **Add Project Screenshots:**
📍 Location: Upload to `assets/images/`
📖 Guide: `assets/images/README_IMAGES.md`

### **Read Documentation:**
📍 Main guide: `README.md`
📍 Quick reference: `QUICK_GUIDE.md`
📍 Image guide: `assets/images/README_IMAGES.md`

---

## 🗂️ Why This Structure is Better

### **Before (Messy):**
```
❌ All files mixed together:
   - index.html
   - profile.jpg
   - project1.jpg
   - project2.jpg
   - background.jpg
   - readme.txt
   (Hard to find things!)
```

### **After (Professional):**
```
✅ Everything organized:
   - Website files in root
   - All images in assets/images/
   - Clear documentation
   (Easy to manage!)
```

---

## 📂 How to Navigate on GitHub

### **Step 1: Start at root**
```
https://github.com/rishi559/rishidhandi.github.io
```
You see:
- index.html
- README.md
- QUICK_GUIDE.md
- assets/ (folder)

### **Step 2: Click `assets`**
```
https://github.com/rishi559/rishidhandi.github.io/tree/main/assets
```
You see:
- images/ (folder)

### **Step 3: Click `images`**
```
https://github.com/rishi559/rishidhandi.github.io/tree/main/assets/images
```
You see:
- profile.jpg ← Your photo is here!
- README_IMAGES.md

---

## 🎨 Adding More Images

### **Future Expansion:**
```
assets/
└── images/
    ├── profile.jpg              ← Current
    │
    ├── projects/                ← For project screenshots
    │   ├── segmentation.jpg
    │   ├── ab-testing.jpg
    │   └── dashboard.jpg
    │
    ├── logos/                   ← For company logos
    │   ├── jazwares.png
    │   └── alliant.png
    │
    └── backgrounds/             ← For background images
        └── hero-bg.jpg
```

### **To add subfolders:**
1. Go to `assets/images/`
2. Click "Create new file"
3. Type: `projects/placeholder.txt`
4. Commit (this creates the folder)
5. Upload images to that folder

---

## 📝 File Naming Rules

### **✅ Good Names:**
- `profile.jpg`
- `customer-segmentation.jpg`
- `ab-testing-dashboard.png`
- `company-logo.png`

### **❌ Bad Names:**
- `My Photo.jpg` (spaces)
- `project@2024.jpg` (special characters)
- `PROFILE.JPG` (all caps, won't match)
- `image (1).jpg` (spaces and parentheses)

**Rule:** Use lowercase, dashes instead of spaces, no special characters

---

## 🔗 Image Paths in HTML

### **Current structure:**
```html
<img src="assets/images/profile.jpg" />
```

### **If you add subfolders:**
```html
<!-- Project screenshot -->
<img src="assets/images/projects/dashboard.jpg" />

<!-- Company logo -->
<img src="assets/images/logos/jazwares.png" />

<!-- Background image -->
<img src="assets/images/backgrounds/hero-bg.jpg" />
```

---

## 💡 Pro Tips

### **Keep it organized:**
- ✅ Use folders for different image types
- ✅ Name files descriptively
- ✅ Delete unused images
- ✅ Keep main photo at `assets/images/profile.jpg`

### **Performance tips:**
- ✅ Compress images before uploading
- ✅ Keep images under 1-2MB
- ✅ Use JPG for photos, PNG for logos
- ✅ Optimize before uploading

### **Version control:**
- ✅ Commit images with descriptive messages
- ✅ Example: "Update profile photo" not "upload file"
- ✅ You can always revert to old versions

---

## 🆘 Common Questions

### **Q: Where do I upload new images?**
**A:** `assets/images/` folder

### **Q: Can I rename the profile photo?**
**A:** NO! Must stay `profile.jpg` or update `index.html`

### **Q: How many images can I add?**
**A:** Unlimited, but keep repo under 1GB total

### **Q: Can I add videos?**
**A:** Yes, but keep them small or link to YouTube/Vimeo

### **Q: What if I mess up the structure?**
**A:** Use Git to revert, or re-upload from backup

---

## 📊 Repository Size

**Current:** ~2-3 MB
**With 10 images:** ~15-20 MB
**Limit:** 1 GB (you're far from it!)

---

## 🎯 Quick Actions

**Change profile photo:**
```
assets/images/profile.jpg → Delete → Upload new
```

**Add project image:**
```
assets/images/ → Upload → Note filename → Add to HTML
```

**Organize later:**
```
Create: assets/images/projects/
Move images there
Update paths in HTML
```

---

**Bookmark this for easy navigation!** 📚

Last Updated: January 2025
