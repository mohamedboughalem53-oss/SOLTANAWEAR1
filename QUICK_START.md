# 🚀 QUICK START GUIDE - Soltana Wear

## ⚡ Get Started in 3 Steps

---

## 1️⃣ **INSTALL**

```bash
npm install
```

---

## 2️⃣ **DEVELOP**

```bash
npm run dev
```

Open http://localhost:5173 in your browser

---

## 3️⃣ **BUILD FOR PRODUCTION**

```bash
npm run build
```

Deploy the `dist/` folder to your hosting

---

## 🎯 **CUSTOMIZATION GUIDE**

### **Change Products:**
Edit `src/App.tsx` - lines 38-135 (products array)

### **Change WhatsApp Number:**
Edit `src/App.tsx` - line 29
```typescript
const whatsappNumber = '+22249904310'; // Change this
```

### **Change Brand Colors:**
Edit `src/index.css` - Color variables section

### **Add More Products:**
Copy a product object in the products array and modify:
```typescript
{
  id: 9, // Increment ID
  name: 'Your Product Name',
  nameAr: 'اسم المنتج بالعربية',
  price: 15000,
  originalPrice: 20000,
  category: 'pajamas', // or 'abayas', 'jellabas'
  image: '/images/your-image.jpg',
  rating: 5,
  reviews: 100,
  badge: 'New',
  inStock: true,
  description: 'Product description'
}
```

### **Change Contact Info:**
Edit footer section in `src/App.tsx` (around line 1100)

---

## 📁 **PROJECT STRUCTURE**

```
soltana-wear/
├── public/
│   └── images/          # Product images
├── src/
│   ├── App.tsx          # Main application
│   ├── index.css        # Global styles
│   └── main.tsx         # Entry point
├── dist/                # Production build
├── index.html           # HTML template
└── package.json         # Dependencies
```

---

## 🎨 **KEY FILES**

- **src/App.tsx** - All website content and functionality
- **src/index.css** - Custom styles and animations
- **public/images/** - Product and hero images
- **index.html** - Meta tags and title

---

## 📸 **ADDING IMAGES**

1. Add images to `public/images/` folder
2. Name them consistently (e.g., product1.jpg, product2.jpg)
3. Reference in products array:
```typescript
image: '/images/product1.jpg'
```

---

## 🌐 **DEPLOYMENT**

### **Netlify:**
```bash
npm run build
# Drag dist/ folder to Netlify
```

### **Vercel:**
```bash
npm run build
# Connect GitHub repo
```

### **Traditional Hosting:**
```bash
npm run build
# Upload dist/ folder via FTP
```

---

## 📱 **TESTING**

### **Mobile:**
- Use browser DevTools (F12)
- Toggle device toolbar
- Test on actual devices

### **Performance:**
- Google Lighthouse
- PageSpeed Insights
- GTmetrix

---

## 🔧 **COMMON CUSTOMIZATIONS**

### **Change Hero Background:**
Replace `/images/hero.jpg` with your image

### **Update Logo:**
Edit navbar section (line ~200)

### **Modify Colors:**
Find and replace color classes:
- `amber-500` → your color
- `green-600` → your color

### **Add Categories:**
Add to category filter (line ~450)

---

## 💡 **PRO TIPS**

1. **Images:** Use WebP format for smaller size
2. **SEO:** Update meta tags in index.html
3. **Analytics:** Add Google Analytics code
4. **Speed:** Optimize images before uploading
5. **Testing:** Test on real devices
6. **Backup:** Keep original images

---

## 🆘 **TROUBLESHOOTING**

### **Build Errors:**
```bash
rm -rf node_modules
npm install
npm run build
```

### **Images Not Showing:**
- Check file paths
- Ensure images are in public/images/
- Use correct case (product1.jpg not Product1.jpg)

### **Styles Not Updating:**
```bash
# Clear cache
npm run dev -- --force
```

---

## 📞 **NEED HELP?**

- Check documentation files
- Read PREMIUM_FEATURES.md
- Review COMPLETE_SUMMARY.md

---

## ✅ **LAUNCH CHECKLIST**

Before going live:

- [ ] Test all links
- [ ] Update WhatsApp number
- [ ] Add real product images
- [ ] Update contact information
- [ ] Test on mobile devices
- [ ] Check loading speed
- [ ] Verify all CTAs work
- [ ] Test shopping cart
- [ ] Confirm pricing
- [ ] Add analytics code
- [ ] Set up domain
- [ ] Test WhatsApp messages
- [ ] Backup website files

---

## 🎉 **YOU'RE READY!**

Your luxury e-commerce website is ready to launch and start selling!

**Good luck with your business!** 🚀💰

---

**Need updates? Edit `src/App.tsx` and rebuild!**
