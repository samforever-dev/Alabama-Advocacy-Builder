# 🛡️ Alabama Disability Advocacy Ecosystem

**Free, open-source tools to help disabled people, families, educators, and allies advocate for change.**

- 🎯 **Campaign Builder** — Generate personalized advocacy plans in 5 minutes
- 📚 **PIPA Program** — Learn disability policy & advocacy training
- 🧩 **UCEED Resources** — National disability research & education network
- 🔗 **Resource Directory** — Alabama + national disability organizations
- 📱 **Mobile-friendly** — Works on phones, tablets, and laptops

---

## **Quick Start**

### **Deploy to GitHub Pages (3 minutes)**

1. Go to [github.com](https://github.com) → create a **free account** if you don't have one

2. Click **New repository** 
   - Name: `disability-advocacy`
   - Set to **Public**
   - Click **Create repository**

3. Click **Add file → Upload files**
   - Drag in all 3 files:
     - `index.html`
     - `builder.html`
     - `README.md`
   - Click **Commit changes**

4. Go to **Settings → Pages**
   - Under "Source," select **main branch**
   - Click **Save**

5. Wait ~60 seconds. Your URL will appear:
   ```
   https://[yourusername].github.io/disability-advocacy
   ```

✅ **You're live!** Share that link.

---

## **Files Included**

| File | Purpose |
|------|---------|
| `index.html` | Main hub: home, PIPA, UCEED, resources, builder |
| `builder.html` | Standalone campaign builder (can be embedded) |
| `SCALING_GUIDE.md` | How to expand to other states & organizations |
| `README.md` | This file |

---

## **Customization**

### **Change Your Organization Name**
In `index.html`, find:
```html
<a class="logo" onclick="showPage('home')"><span>🏛️</span> AL Disability Advocacy</a>
```
Replace with your organization name.

### **Update Resources**
In `index.html`, find the JavaScript section with:
```javascript
const alabamaResources = [...]
const autismResources = [...]
const nationalResources = [...]
```

Edit these arrays to add/remove organizations.

### **Change Colors**
In `index.html` `<style>` section, edit CSS variables:
```css
:root {
  --primary: #0F3172;      /* Dark blue */
  --accent: #2E6FD9;       /* Lighter blue */
  --success: #10B981;      /* Green */
  /* ... */
}
```

### **For Different States**
See `SCALING_GUIDE.md` for how to adapt this for Georgia, Texas, or any state.

---

## **What Users Can Do**

### **Campaign Builder**
1. Answer 5 questions about their issue
2. Get a personalized advocacy plan with:
   - Elevator pitch
   - Letter/testimony
   - Email template
   - Phone script
   - Op-ed draft
   - Social media posts
3. Copy & customize each piece
4. Send to targets

### **PIPA Program Page**
- Learn about UAB's Partners in Policymaking training
- Link to course portal & curriculum
- Info on how to apply

### **UCEED Page**
- Discover university disability research networks
- Find centers in your state
- Learn about employment & transition programs

### **Resource Directory**
- Browse Alabama advocacy organizations
- Autism-specific resources
- National advocacy & IEP tools
- Expandable folders for easy scanning

---

## **Mobile Optimization**

Tested on:
- ✅ iPhone (Safari, Chrome)
- ✅ Android (Chrome)
- ✅ iPad
- ✅ Desktop (Chrome, Firefox, Safari)

All forms, buttons, and text are readable on small screens.

---

## **Accessibility**

- ✅ High contrast (dark blue on white)
- ✅ Large readable fonts (16px minimum)
- ✅ Keyboard navigation (Tab through form)
- ✅ Semantic HTML
- ✅ Simple language, no jargon

**Tested with:**
- Screen readers (partial)
- Keyboard-only navigation
- Windows High Contrast mode

**To improve further:** Add ARIA labels, test with NVDA/JAWS.

---

## **Feedback & Issues**

### **Report a Bug**
1. Go to your repository on GitHub
2. Click **Issues → New issue**
3. Describe what happened

### **Suggest a Resource**
1. Open an issue with the resource
2. Include: Organization name, description, URL
3. We'll review and add it

### **Request a Feature**
- Need a different campaign tool?
- Want to add state-specific content?
- Open an issue and describe it

---

## **Analytics (Optional)**

To track visitors:

1. Create free account at [plausible.io](https://plausible.io)
2. Add your domain
3. Copy tracking code snippet
4. Paste in `<head>` of `index.html`:
```html
<script defer data-domain="[yourdomain]" src="https://plausible.io/js/script.js"></script>
```

You'll see:
- Monthly visitors
- Which pages they visit
- Time spent per page
- Traffic sources

---

## **Next Steps**

### **Right Now**
- [ ] Deploy to GitHub Pages
- [ ] Test all pages on phone
- [ ] Share link with 5 advocates

### **Week 1**
- [ ] Collect feedback from users
- [ ] Fix any broken links
- [ ] Update resources if needed

### **Month 1**
- [ ] Add 2-3 success stories
- [ ] Create template gallery page
- [ ] Consider analytics tracking

### **By Month 3**
- [ ] Extract data to JSON (see SCALING_GUIDE.md)
- [ ] Prepare for multi-state adaptation
- [ ] Write public docs for other organizations

---

## **Tech Stack**

- **Frontend:** Plain HTML + CSS + JavaScript (no dependencies)
- **Hosting:** GitHub Pages (free)
- **Fonts:** Google Fonts (DM Serif Display, Outfit)
- **No database, no backend, no build process**

**Why this stack?**
- Works anywhere (no server required)
- Fast load times
- Easy to customize
- Free forever
- Easy to fork & adapt

---

## **License**

This project is **open source** and free to use, customize, and share.

Feel free to:
- ✅ Fork and adapt for your state
- ✅ Use as a template
- ✅ Share with other organizations
- ✅ Modify the design
- ✅ Add your branding

We ask that you:
- ✅ Keep it free
- ✅ Credit the Alabama disability advocacy community
- ✅ Share improvements back (optional)

---

## **Questions?**

### **I want to customize this for [State]**
→ Read `SCALING_GUIDE.md`

### **How do I add a second campaign tool?**
→ Add a new section to `index.html` + `builder.html`, follow the pattern

### **Can I use this on my organization's website?**
→ Yes! Embed `builder.html` in an iframe:
```html
<iframe src="https://[yourdomain]/disability-advocacy/builder.html" 
        style="width:100%; height:800px; border:none;"></iframe>
```

### **Who built this?**
→ Alabama disability advocates + community input. See SCALING_GUIDE.md for philosophy.

---

## **Support**

Need help?

1. **Bug report:** Open issue on GitHub
2. **Feature request:** Open issue on GitHub
3. **Customization help:** DM on GitHub (we'll do our best)
4. **Deployment issues:** GitHub has great docs at github.com/pages

---

**🚀 Ready to scale? See `SCALING_GUIDE.md`**

**Made with ❤️ for the disability advocacy community. Free. Forever.**
