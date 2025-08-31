# 🎨 Portfolio Customization Guide - Colors & Images

## 🌈 **How to Change Colors**

### **1. Main Color Scheme**
Edit the CSS variables in the `<style>` section of `index.html`:

```css
:root {
    --primary-color: #ff4444;        /* Main brand color - CHANGE THIS! */
    --secondary-color: #ff6666;      /* Secondary color */
    --accent-color: #ff8888;         /* Accent color */
    --text-dark: #ffffff;            /* Main text color */
    --text-light: #cccccc;           /* Light text color */
    --bg-dark: #0a0a0a;              /* Main background */
    --bg-darker: #000000;            /* Darker background */
    --bg-card: #1a1a1a;              /* Card background */
    --bg-light: #2a2a2a;             /* Light background */
    --border-color: #333333;         /* Border color */
}
```

### **2. Popular Color Themes**

**🔵 Blue Theme:**
```css
--primary-color: #3b82f6;
--secondary-color: #1d4ed8;
--accent-color: #60a5fa;
```

**🟢 Green Theme:**
```css
--primary-color: #10b981;
--secondary-color: #059669;
--accent-color: #34d399;
```

**🟣 Purple Theme:**
```css
--primary-color: #8b5cf6;
--secondary-color: #7c3aed;
--accent-color: #a78bfa;
```

**🟠 Orange Theme:**
```css
--primary-color: #f97316;
--secondary-color: #ea580c;
--accent-color: #fb923c;
```

**🟡 Yellow Theme:**
```css
--primary-color: #f59e0b;
--secondary-color: #d97706;
--accent-color: #fbbf24;
```

**🔴 Red Theme (Current):**
```css
--primary-color: #ff4444;
--secondary-color: #ff6666;
--accent-color: #ff8888;
```

### **3. Light Theme Option**
If you want a light theme instead of dark:

```css
:root {
    --primary-color: #3b82f6;
    --secondary-color: #1d4ed8;
    --accent-color: #60a5fa;
    --text-dark: #1f2937;
    --text-light: #6b7280;
    --bg-dark: #ffffff;
    --bg-darker: #f8fafc;
    --bg-card: #ffffff;
    --bg-light: #f1f5f9;
    --border-color: #e5e7eb;
}
```

## 🖼️ **How to Change Images & Icons**

### **1. Project Icons**
Replace the Font Awesome icons in the project cards:

**Current Icons:**
```html
<i class="fas fa-comments"></i>      <!-- Social Media Analytics -->
<i class="fas fa-chart-line"></i>    <!-- Data Analysis -->
<i class="fas fa-brain"></i>         <!-- Machine Learning -->
<i class="fas fa-database"></i>      <!-- Database Projects -->
```

**Popular Data Science Icons:**

**📊 Data Analysis:**
- `fas fa-chart-bar` - Bar chart
- `fas fa-chart-line` - Line chart
- `fas fa-chart-pie` - Pie chart
- `fas fa-chart-area` - Area chart
- `fas fa-analytics` - Analytics

**🤖 Machine Learning:**
- `fas fa-brain` - Brain/AI
- `fas fa-robot` - Robot
- `fas fa-cogs` - Gears/Processing
- `fas fa-network-wired` - Neural network
- `fas fa-microchip` - AI chip

**🗄️ Database:**
- `fas fa-database` - Database
- `fas fa-server` - Server
- `fas fa-hdd` - Hard drive
- `fas fa-cloud` - Cloud storage

**💬 Social Media:**
- `fas fa-comments` - Comments
- `fas fa-users` - Users
- `fas fa-share-alt` - Share
- `fas fa-hashtag` - Hashtag
- `fas fa-thumbs-up` - Like

**🌐 Web Development:**
- `fas fa-code` - Code
- `fas fa-laptop-code` - Laptop with code
- `fas fa-globe` - Globe/Web
- `fas fa-mobile-alt` - Mobile app

### **2. Skill Icons**
Change the skill section icons:

**Current Icons:**
```html
<i class="fab fa-python skill-icon"></i>     <!-- Python -->
<i class="fab fa-python skill-icon"></i>     <!-- Excel (should be different) -->
<i class="fas fa-database skill-icon"></i>   <!-- SQL -->
<i class="fas fa-chart-bar skill-icon"></i>  <!-- Visualization -->
<i class="fas fa-brain skill-icon"></i>      <!-- Machine Learning -->
```

**Better Skill Icons:**
```html
<i class="fab fa-python skill-icon"></i>     <!-- Python -->
<i class="fas fa-file-excel skill-icon"></i> <!-- Excel -->
<i class="fas fa-database skill-icon"></i>   <!-- SQL -->
<i class="fas fa-chart-bar skill-icon"></i>  <!-- Visualization -->
<i class="fas fa-brain skill-icon"></i>      <!-- Machine Learning -->
```

### **3. Add Custom Images**

**Option A: Replace Icons with Images**
```html
<div class="project-image">
    <!-- Remove the icon and add image -->
    <img src="path/to/your/project-image.jpg" alt="Project Image" style="width: 100%; height: 100%; object-fit: cover;">
</div>
```

**Option B: Add Background Images**
```css
.project-image {
    background-image: url('path/to/your/image.jpg');
    background-size: cover;
    background-position: center;
}
```

### **4. Profile Picture**
Add your profile picture to the hero section:

```html
<!-- Add this in the hero section -->
<div class="col-lg-6 text-center mb-4">
    <img src="path/to/your/profile-picture.jpg" alt="Ramesh Bagi" style="width: 200px; height: 200px; border-radius: 50%; border: 4px solid var(--primary-color); object-fit: cover;">
</div>
```

## 🎯 **Step-by-Step Customization**

### **Step 1: Change Colors**
1. Open `index.html`
2. Find the `:root` section in the `<style>` tag
3. Change `--primary-color` to your preferred color
4. Update other colors as needed

### **Step 2: Change Icons**
1. Find the project cards in the HTML
2. Replace `fas fa-comments` with your preferred icon
3. Use the Font Awesome icon list above

### **Step 3: Add Images**
1. Place your images in a folder (e.g., `images/`)
2. Update the `src` attribute in the HTML
3. Make sure images are optimized (web-friendly format and size)

## 📁 **File Structure for Images**
```
portfolio/
├── index.html
├── student_cv.html
├── images/
│   ├── profile-picture.jpg
│   ├── project1.jpg
│   ├── project2.jpg
│   └── project3.jpg
└── README.md
```

## 🎨 **Color Palette Generator**
Use these tools to create your own color palette:
- [Coolors.co](https://coolors.co/)
- [Adobe Color](https://color.adobe.com/)
- [Color Hunt](https://colorhunt.co/)

## 💡 **Pro Tips**

1. **Consistency**: Use the same color scheme throughout
2. **Contrast**: Ensure text is readable on your background
3. **Accessibility**: Consider color-blind users
4. **Branding**: Match your personal brand colors
5. **Testing**: Test on different devices and browsers

## 🔧 **Quick Color Changes**

**For a Professional Blue Theme:**
```css
--primary-color: #2563eb;
--secondary-color: #1d4ed8;
--accent-color: #3b82f6;
```

**For a Modern Green Theme:**
```css
--primary-color: #059669;
--secondary-color: #047857;
--accent-color: #10b981;
```

**For a Creative Purple Theme:**
```css
--primary-color: #7c3aed;
--secondary-color: #6d28d9;
--accent-color: #8b5cf6;
```

---

**Ready to customize your portfolio?** 🚀

Start with changing the primary color and then experiment with different icons and images!
