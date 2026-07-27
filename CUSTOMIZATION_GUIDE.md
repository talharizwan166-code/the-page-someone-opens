# Crema Restaurant - Customization Guide

Your restaurant website is ready. Here's what to customize to make it your own.

## Quick Edit Instructions

Open `crema-restaurant.html` in a text editor (Notepad, VS Code, etc) and find these sections:

### 1. Restaurant Name & Details
**Find this line (around line 129):**
```html
<div class="logo">🍽️ Crema</div>
<div class="tagline">Old Town Restaurant</div>
```
**Change to:**
```html
<div class="logo">🍽️ Your Restaurant Name</div>
<div class="tagline">Your Tagline Here</div>
```

### 2. Phone Number (for WhatsApp & Call buttons)
**Find these lines (around 145-150):**
```html
<a href="https://wa.me/923001234567" class="btn btn-whatsapp">
```
and
```html
<a href="tel:+923001234567" class="btn btn-call">
```
**Change `923001234567` to your phone number** (keep the country code +92 for Pakistan)

Example: If your number is 300-1234567, use: `923001234567`

### 3. Menu Items & Prices
Find each section and update:
- Appetizers (starts around line 168)
- Main Course (around line 180)
- Rice & Bread (around line 205)
- Beverages (around line 220)
- Desserts (around line 235)

**Format:**
```html
<div class="menu-item">
    <span class="item-name">Item Name</span>
    <span class="item-price">PKR 450</span>
</div>
```

Just replace `Item Name` and the price number. Prices are already in PKR.

### 4. Hours
**Find (around line 250):**
```html
<div class="day">Monday – Friday</div>
<div class="time">7 AM – 8 PM</div>
```
Change times as needed. Keep the format the same.

### 5. Location
**Find (around line 270):**
```html
<strong>Crema Restaurant</strong><br>
Old Town Square, Building 42<br>
Downtown, Karachi<br><br>
```
Update with your actual restaurant name and address.

### 6. Eid Banner
**Find (around line 123):**
```html
<div class="eid-banner">
    🌙 Happy Eid! Celebrate with us 🌙
</div>
```
Change the text or emoji as you like. Or remove the entire section if you don't want it.

---

## How to Use

1. **Save your changes** to the HTML file
2. **Open it in any browser** - just double-click the file
3. **Test on your phone** - use WhatsApp and Call buttons to verify they work
4. **Share the link** - upload the HTML file to a web host, or simply email it to customers

## Sharing Options

### Option 1: Email (Simplest)
- Attach the HTML file to an email
- Recipients can open it directly in their browser

### Option 2: Free Web Hosting
- Upload to free services like:
  - **Netlify** (drag & drop, free)
  - **GitHub Pages** (free for public repos)
  - **Vercel** (free tier available)
  - **Firebase Hosting** (free tier)

### Option 3: Your Own Domain
- If you have a website, upload the file and link to it

---

## Features Already Included

✅ Mobile-optimized (works great on phones)
✅ WhatsApp ordering button
✅ Direct call button
✅ Eid banner
✅ Full menu with categories
✅ Operating hours
✅ Location with Google Maps link
✅ Professional design
✅ No external dependencies (single HTML file)
✅ Fast loading (no ads, trackers, or unnecessary code)

---

## Need Help?

If you get stuck:
1. Make sure you're editing the right section (use Ctrl+F to search)
2. Don't delete HTML tags like `<div>`, `</div>`, `<span>`, `</span>`
3. Only change the text between the opening and closing tags
4. Save the file and refresh your browser to see changes

---

**Your restaurant website is production-ready. Customize it, test it, and share it with your customers!**
