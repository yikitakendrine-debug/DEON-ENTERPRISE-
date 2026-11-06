# DEON ENTERPRISE — Website Image Assets & Replacement Guide

All images on your website have been neatly organized into the dedicated folder:
📂 `/public/deon-assets/` (and root shortcuts `img1.jpg` – `img6.jpg`, `logo.jpg`).

You can replace any image at any time by dropping your own photo into the folder with the same name, or by updating the `src` attribute in `index.html`.

---

## 📸 Image Directory & Placement Map

| # | Filename | Website Placement | Description & Dimensions |
|---|----------|-------------------|--------------------------|
| **01** | `01_logo_deon.jpg` (or `logo.jpg`) | **Navbar, Mobile Menu, Admin, Footer, Favicon** | Circular DEON Logo with eagle emblem (1:1 Square, 500x500px). |
| **02** | `02_hero_admission_flyer.jpg` (or `img2.jpg`) | **Hero Section Showcase & Portfolio** | Hands of Grace Nursery & Primary School Admission Flyer (4:3 or 4:5, 1200x900px). |
| **03** | `03_service_large_format.jpg` | **Services: Large Format Printing Card** | Pull-up roll banners, teardrop flags, and backdrop banners (4:3, 1200x900px). |
| **04** | `04_service_digital_printing.jpg` | **Services: Digital Printing Card** | Business cards, brochures, flyers, and gold-foiled certificates (4:3, 1200x900px). |
| **05** | `05_service_material_branding.jpg` | **Services: Material Branding Card** | Branded cotton t-shirts, embroidered caps, ceramic mugs, and lanyards (4:3, 1200x900px). |
| **06** | `06_about_printing_workshop.jpg` (or `img6.jpg`) | **About Us: Who We Are & Portfolio** | Industrial wide-format roll printer workshop at Zebra House, Nasser Road (16:9 or 4:3). |
| **07** | `07_portfolio_umoja_salon_sign.jpg` (or `img1.jpg`) | **Portfolio: UMOJA Unisex Salon** | Yellow & black illuminated acrylic lightbox sign (4:3, 1200x900px). |
| **08** | `08_portfolio_bishop_willigers_school.jpg` (or `img3.jpg`) | **Portfolio: School Signage** | Bishop Willigers Memorial School 3D illuminated letters on facade (4:3, 1200x900px). |
| **09** | `09_portfolio_neiglow_skincare_glass.jpg` (or `img4.jpg`) | **Portfolio: NeiGlow Skin Care** | Double frosted glass entrance doors with gold lettering (4:3, 1200x900px). |
| **10** | `10_portfolio_beauty_by_gisel_shop.jpg` (or `img5.jpg`) | **Portfolio: Beauty by Gisel** | 3D illuminated channel letters "Bags, Wigs, Shoes" at boutique arcade (4:3, 1200x900px). |

---

## 🛠️ How to Replace Any Image with Your Own

### Method 1: Drop & Replace (Easiest)
1. Rename your new photo to match the exact filename in the table above (e.g., `07_portfolio_umoja_salon_sign.jpg` or `img1.jpg`).
2. Copy or drag-and-drop your photo into `public/deon-assets/` (or into the root folder for `img1.jpg`–`img6.jpg`).
3. Refresh your browser (Ctrl+Shift+R or Cmd+Shift+R) and your new photo will automatically appear!

### Method 2: Upload to Any Folder and Update `index.html`
1. Save your image anywhere inside `public/` (e.g. `public/my-photos/new_sign.jpg`).
2. Open `index.html` and search for the image tag you want to change:
   ```html
   <!-- Example: Updating Portfolio Card 1 -->
   <img src="/my-photos/new_sign.jpg" alt="My New Signage" class="..." />
   ```
3. Save the file.

---

## 📐 Recommended Image Specifications

- **Format**: `.jpg`, `.jpeg`, `.png`, or `.webp`
- **Resolution**: Between **800px to 1600px width** (72 to 150 DPI is ideal for web performance).
- **Aspect Ratios**:
  - **Logo**: 1:1 (Square)
  - **Service & Portfolio Cards**: 4:3
  - **Hero Showcase**: 4:5 or 4:3
  - **Workshop Banner**: 16:9 (Landscape)
