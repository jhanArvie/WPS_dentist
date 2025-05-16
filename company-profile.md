

### Company Profile Template

#### ✅ Constant Information
**Basic Info**
- Business Name: `[Your Business Name]`
- Type: `[Café, Store, etc.]`
- Tagline: `[Catchy Phrase]`
- Founded: `[Year]`

**Contact Info**
- Address: `[Complete Address]`
- Phone: `[Number]`
- Email: `[Business Email]`
- Operating Hours:
  - Mon–Fri: `[Start–End]`
  - Sat–Sun: `[Start–End]`
  - Holidays: `[Special Hours]`

**Social Media**
- Facebook: `[URL]`
- Instagram: `[URL]`
- Twitter: `[URL]`
- LinkedIn: `[URL]`
- TikTok: `[URL]`

---

#### 🌀 Dynamic Information

**Brand Identity**
- Primary Color: `[HEX or auto from logo]` if both are not provided use default 
- Secondary Color: `[HEX or default]` if both are not provided use default
- Accent Color: `[HEX or default]` if both are not provided use default
- Fonts:
  - Heading Font: `[Font or logo match or default]` if both are not provided use default
  - Body Font: `[Font or default]` if both are not provided use default
- Logo: Auto-check from `assets/logo/` or use Business Name as text if missing

**Business Description**
- Use provided text or auto-generate from business type
- Improve to be concise, compelling, and unique

**Key Features/Services <!-- Services Section -->**
1. Feature 1
2. Feature 2
3. Feature 3
- Add more as needed

**Pricing Section <!-- Pricing Section -->**
1. Package 1
2. Package 2
3. Package 3
- Add more as needed

**Menu or Product Categories**
1. Category 1
2. Category 2
- Extend as necessary

---

## 🖼️ Image Allocation Rules if no images are provided use default

| Section                 | Folder Path                            | Fallback      |
|-------------------------|----------------------------------------|---------------|
| Hero                    | `assets/hero/`                         | Default       |
| About                   | `assets/about/`                        | Default       |
| Gallery                 | `assets/gallery/`                      | Default       |
| Menu/Services           | `assets/menu-service/`                 | Default       |
| Customer Feedback       | `assets/customer-feedback/`           | Default       |
| Contact Section         | `assets/contact/`                      | Default       |
| Testimonials            | `assets/testimonials/`                | Default       |

---

## Testimonials if section provided <!-- testimonials -->
- testimonial 1: `[Write a testimonial]` or if not provided use the existing testimonial and default one
- testimonial 2: `[Write a testimonial]` or if not provided use the existing testimonial and default one
- testimonial 3: `[Write a testimonial]` or if not provided use the existing testimonial and default one





# 📄 AI Implementation Instructions for `index.html` Update

## 🎯 Task Overview
Update `index.html` and relevant assets to reflect the company's branding and content precisely. Follow the structured steps below to ensure accuracy, consistency, and functionality.

---

## 🧩 Step-by-Step Implementation

### 0. Separate JS and CSS files
- create a new script.js file in the scripts folder then move the <script> tag that is after the body tag to the new script.js file
- create a new style.css file in the css folder then move the <style> tag that is in the head tag to the new style.css file
- remove the <script> tag that is after the body tag and the <style> tag that is in the head tag
- link the new script.js file to the index.html file
- link the new style.css file to the index.html file

### 1. Company Profile Integration
- Replace **all placeholder text**, images, and metadata with the provided company details.
- Ensure **consistent branding**: name, slogan, color palette, and voice.
- Update all **headings, descriptions, and contact information** to reflect the company’s offerings.

---

### 2. File Structure & Asset Management
- All images must include: `loading="lazy"`.
- Replace images in `/assets` with official company versions.
- Rename image files logically (e.g., `company-logo.png`, `menu-item.jpg`).
- Update all `href` and `src` references in `index.html` to match new file paths.
- **Do not** add or remove folders; only modify contents of existing ones.

---

### 3. Metadata & SEO
- Update:
  - `<title>` and `<meta>` descriptions
  - OpenGraph tags (og:title, og:image, og:description, etc.)
- Use keywords relevant to the company’s niche.

---

### 4. Styling Adjustments see **Brand Identity** in update checklist below
- Modify CSS (inline or external) to reflect the brand’s:
  - Primary / Secondary / Accent Colors
  - Fonts for headings and body text
- Use defaults only if values are not provided.

---

### 5. Content Validation
- Ensure:
  - No broken links or missing assets
  - Fully responsive layout
  - Accessibility (ALT text, Area labels)

---

### 6. Form Integration (Netlify)
To make forms work via Netlify, apply the following format:
```html
<form name="{form name}" method="POST" data-netlify="true" data-netlify-honeypot="bot-field">
  <input type="hidden" name="form-name" value="{form name}" netlify-honeypot="bot-field" />
  <!-- Add your form fields here -->
</form>
```

---

### 7. Social Media Links
- Assign provided links to corresponding social media icons in `index.html`.
- **Remove** icons if links are missing.
    - **Facebook**: [URL]
    - **Instagram**: [URL]
    - **Twitter**: [URL]
    - **LinkedIn**: [URL]
    - **TikTok**: [URL]
    - **Youtube**: [URL]
    - **Whatsapp**: [URL]
---





## 📱 Mobile Navigation Menu

- **Animation Style**: `Slide`
- **Icon Style**: `Classic Three Lines`
- **Menu Behavior**: *(Choose one)*
  - [ ] Slide from Left
  - [ ] Slide from Right
  - [ ] Slide from Top
  - [ ] Slide from Bottom
  - [ ] Fade In Center
  - [ ] Full Screen Overlay

---

## ⚠️ Final Notes
- Do not duplicate any section.
- Do not create or delete folders.
- Validate changes before deployment.