# Images Folder Guide

## 📁 Folder Structure

```
rishidhandi.github.io/
├── index.html
├── README.md
├── QUICK_GUIDE.md
└── assets/
    └── images/
        ├── profile.jpg        ← Your main profile photo
        ├── project1.jpg       ← Project screenshots (optional)
        ├── project2.jpg       ← Project screenshots (optional)
        └── background.jpg     ← Background images (optional)
```

---

## 🖼️ How to Change Your Profile Photo

### **Easy Method (GitHub Web):**

1. **Go to your repository:**
   - https://github.com/rishi559/rishidhandi.github.io

2. **Navigate to the images folder:**
   - Click `assets` folder
   - Click `images` folder

3. **Delete old photo:**
   - Click on `profile.jpg`
   - Click trash icon (🗑️)
   - Commit deletion

4. **Upload new photo:**
   - Go back to `images` folder
   - Click "Add file" → "Upload files"
   - Upload your new photo
   - **Important:** Name it exactly `profile.jpg`
   - Commit changes

5. **Done!** Wait 2 minutes and refresh your site

---

## 📸 Photo Requirements

### **Profile Photo:**
- **Size:** 800x800 pixels (square)
- **Format:** JPG or PNG
- **File size:** Under 2MB
- **Name:** `profile.jpg` (exactly this name!)

### **Project Screenshots (Optional):**
- **Size:** 1200x800 pixels (landscape)
- **Format:** JPG or PNG
- **File size:** Under 1MB each
- **Names:** `project1.jpg`, `project2.jpg`, etc.

---

## 🎨 Adding Project Images

Want to add screenshots to your projects?

### **Step 1: Upload Project Image**

1. Go to `assets/images/` folder
2. Upload your project screenshot
3. Name it something descriptive: `customer-segmentation.jpg`

### **Step 2: Add to HTML**

Edit `index.html` and add this inside a project card:

```html
<div class="bg-white p-6 rounded-lg shadow-md border-2 border-[#4682b4]">
  <!-- Add this image line -->
  <img src="assets/images/customer-segmentation.jpg" alt="Customer Segmentation" class="w-full h-48 object-cover rounded-lg mb-4" />
  
  <h4 class="text-xl font-semibold">Customer Segmentation Engine</h4>
  <p class="mt-2">Your description...</p>
  <!-- rest of project card -->
</div>
```

---

## 📂 Organizing Many Images

As you add more images, organize them:

```
assets/
└── images/
    ├── profile.jpg              ← Your photo
    ├── projects/                ← Project screenshots
    │   ├── segmentation.jpg
    │   ├── ab-testing.jpg
    │   └── dashboard.jpg
    ├── logos/                   ← Company logos (optional)
    │   ├── jazwares.png
    │   └── alliant.png
    └── icons/                   ← Custom icons (optional)
        └── custom-icon.svg
```

**To use subfolders:**
- Path: `assets/images/projects/segmentation.jpg`

---

## 🔄 Batch Upload Multiple Images

**Upload many images at once:**

1. Go to `assets/images/` folder
2. Click "Add file" → "Upload files"
3. Drag multiple images at once
4. Commit all changes together

---

## 💾 Best Practices

### **Do:**
- ✅ Use descriptive filenames: `ab-testing-dashboard.jpg`
- ✅ Keep images under 1-2MB
- ✅ Use square photos for profile (800x800)
- ✅ Compress images before uploading
- ✅ Use lowercase filenames with dashes

### **Don't:**
- ❌ Use spaces in filenames: `my photo.jpg` ❌
- ❌ Upload huge files (5MB+)
- ❌ Use special characters: `photo@2024.jpg` ❌
- ❌ Change profile photo filename

---

## 🛠️ Image Optimization Tools

**Free tools to compress images:**
- **TinyPNG:** https://tinypng.com/
- **Squoosh:** https://squoosh.app/
- **ImageOptim:** (Mac users)

**Tip:** Compress images before uploading to make your site faster!

---

## 🖼️ Where Images Are Used

### **Current Usage:**
- `profile.jpg` → Hero section (main photo)

### **Future Usage (Optional):**
You can add images to:
- Project cards (screenshots)
- Company logos in experience section
- Achievement badges
- Background images

---

## 📝 Image Path Reference

### **Current setup:**
```html
<img src="assets/images/profile.jpg" />
```

### **If you add subfolders:**
```html
<img src="assets/images/projects/dashboard.jpg" />
<img src="assets/images/logos/company.png" />
```

---

## 🆘 Troubleshooting

### **Image not showing?**

**Check 1:** Filename
- Must be exactly `profile.jpg` (lowercase)
- No spaces or special characters

**Check 2:** Location
- Must be in `assets/images/` folder
- Not in root folder
- Not in wrong subfolder

**Check 3:** Path in HTML
- Should be: `assets/images/profile.jpg`
- Case-sensitive!

**Check 4:** Browser cache
- Press Ctrl+Shift+R (hard refresh)
- Or clear browser cache

**Check 5:** Wait time
- Changes take 2-3 minutes
- Be patient!

---

## 📊 Folder Benefits

### **Why use a folder?**
- ✅ **Organized:** All images in one place
- ✅ **Professional:** Standard web development practice
- ✅ **Scalable:** Easy to add more images
- ✅ **Clear:** Know where to find/add images
- ✅ **Maintainable:** Easy to manage as site grows

---

## 🎯 Quick Command List

**Change profile photo:**
1. Go to `assets/images/`
2. Delete `profile.jpg`
3. Upload new `profile.jpg`
4. Done!

**Add project image:**
1. Upload to `assets/images/`
2. Note the filename
3. Add to `index.html`:
   ```html
   <img src="assets/images/your-image.jpg" />
   ```

**View all images:**
- Go to: `https://github.com/rishi559/rishidhandi.github.io/tree/main/assets/images`

---

## 📱 Mobile Upload

**Upload from phone:**
1. Open GitHub app or browser
2. Navigate to `assets/images/`
3. Tap "+" or "Add file"
4. Select photo from phone
5. Upload!

---

**Keep this guide handy for managing your images!** 🎨

Last Updated: January 2025
