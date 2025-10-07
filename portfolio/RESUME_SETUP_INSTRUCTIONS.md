# Resume Setup Instructions

## ✅ What You Need to Do

### 1. **Add Your PDF Resume File**
   - Place your resume PDF file in the `image` folder
   - Name it: `resume.pdf`
   - Full path should be: `portfolio/image/resume.pdf`

### 2. **Keep Your Resume Image (Optional but Recommended)**
   - Keep `resume.jpg` in the `image` folder for mobile fallback
   - This ensures mobile users can still view your resume if PDF doesn't load

### 3. **File Structure Should Look Like:**
```
portfolio/
├── image/
│   ├── resume.pdf    ← Your PDF resume (ADD THIS)
│   ├── resume.jpg    ← Your resume image (KEEP THIS)
│   └── ... (other images)
├── index.html
├── resume.html
└── style.css
```

## 🎯 How It Works

### **On Desktop/Laptop:**
- Shows your PDF in an embedded viewer
- Users can scroll through pages
- Professional PDF viewing experience

### **On Mobile:**
- Shows the resume image (resume.jpg)
- Better mobile compatibility
- Faster loading

### **Download Button:**
- Downloads the PDF file (`resume.pdf`)
- Works on all devices

## 🔗 Navigation Flow

1. User clicks **"View Resume"** button on homepage
2. Goes to `resume.html` page
3. Sees PDF viewer (desktop) or image (mobile)
4. Can click **"Back to Home"** to return
5. Can click **"Download Resume"** to save PDF

## 📝 Notes

- The homepage button (`index.html` line 65) already links to `resume.html` - no changes needed!
- PDF file must be named exactly: `resume.pdf`
- Image file must be named exactly: `resume.jpg`
- Both files go in the `image` folder

## 🚀 You're All Set!

Just add your `resume.pdf` file to the `image` folder and everything will work automatically!
