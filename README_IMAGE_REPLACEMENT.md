# DEON ENTERPRISE — Website Image Assets & Replacement Guide

All images on your website have been organized into the dedicated folder:
📂 `/public/deon-assets/`

---

## 📸 Image Directory & Placement Map

| # | Filename in `public/deon-assets/` | Website Placement | Description & Dimensions |
|---|-----------------------------------|-------------------|--------------------------|
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
2. Overwrite the file in `public/deon-assets/` or the root folder.
3. Refresh your browser (Ctrl+Shift+R or Cmd+Shift+R) and your new photo will automatically appear!

### Method 2: Update in `index.html`
Open `index.html` and search for the image tag you want to change, then update the `src` attribute to your new image path.
