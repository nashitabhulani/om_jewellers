# Om Jewellers • Luxury Bridal & Fine Heritage Website

A modern, royal champagne-gold digital experience for **Om Jewellers** (Mumbai), faithfully recreated with exact 1-to-1 visual fidelity from the Stitch design system. Built with performance, mobile optimization, and seamless Vercel deployment in mind.

---

## 🌟 Highlights & Features

1. **Pure Cinematic Hero Carousel**
   - 8 high-resolution luxury bridal & campaign banners without intrusive text overlays.
   - Smooth transform animations, minimal golden indicator dots, and responsive arrow navigation.
   - **Touch swipe gestures** on mobile devices (`touchstart`, `touchend`).
   - Autoplay (5s cycle) with intelligent pause-on-hover & pause-on-touch.

2. **Atelier Om Jewellers (Bespoke Jewellery)**
   - Dedicated hero banner with instant CTA linking to `customise.html` and the consultation form.
   - Comprehensive **6-step Interactive Design Brief**:
     1. *Jewellery Category Selection* (Rings, Earrings, Necklaces, Bracelets, Bangles, Pendants, Sets).
     2. *Style Curation* (Classic, Contemporary, Traditional, Minimal, Statement, Custom Sketches).
     3. *Material & Karatage Customizer* (18K/22K, Yellow Gold, Rose Gold, Platinum, Natural Solitaires, Polki).
     4. *Tiered Luxury Budget Selection* (₹50K to ₹10L+).
     5. *Reference Inspiration Uploader* (drag-and-drop or browse files).
     6. *Client Details & Preferred Mumbai Salon Booking*.
   - Interactive confirmation modal with instant WhatsApp concierge follow-up.

3. **Iconic Campaign Spotlight: "Marry Their Imperfections"**
   - Chapter 01: *"She Doesn't Know How to Cook"* (Bridal Polki).
   - Chapter 02: *"She Earns More Than Him"* (Solitaire Rings).
   - Chapter 03: *"She is Divorced"* (Heritage Bridal Sets).

4. **Omnichannel Impact: "Campaign Media Rollout • Where It Ran"**
   - **Movie / Cinema Ad**: PVR, INOX, and Cinepolis multiplex screenings with interactive preview modal lightbox.
   - **Statics & Print Media**: Times of India front covers, Bombay Times, and Western Express Highway billboards with press kit view.
   - **Instagram & Social**: Real community engagement metrics (5.2M+ Views, 120K+ Likes).

5. **Signature Heritage Collections**
   - Interactive category filter tabs (**All**, **Gold**, **Diamond**, **Polki & Jodha**, **Platinum**) with smooth transition.
   - Interactive Wishlist heart toggle with micro-animations.
   - "Inquire" button automatically scrolls and prefills the bespoke appointment form.

6. **Mumbai Boutiques Locator**
   - Showcase for **Borivali West** (Flagship Salon), **Mulund West** (Bespoke Studio), **Ghatkopar East** (Diamond Lounge), and **Bandra West** (Turner Road Luxury Salon).
   - Click-to-call (`tel:`) and direct Google Maps navigation links.

7. **Fully Mobile-Optimized**
   - Responsive fixed header with live gold rates ticker.
   - Slide-out luxury drawer navigation on mobile with smooth backdrop blur.
   - Floating WhatsApp concierge button and back-to-top smooth scroll.

---

## 🎨 Design System: Modern Royal Champagne & Gold

- **Royal Maroon Dark**: `#3D0C10`
- **Royal Maroon Base**: `#5B1318`
- **Radiant Gold**: `#D4AF37`
- **Antique Gold**: `#C5A059`
- **Canvas Cream**: `#FAF7F2`
- **Champagne Subtle**: `#F6F0E6`
- **Typography**: `Playfair Display` (Headlines, Serifs) & `Plus Jakarta Sans` (Clean, modern body typography).

---

## 🚀 Running Locally

You can preview the website locally using any standard static server:

```bash
# Using npx serve
npx -y serve . -p 3000

# Or with Python
python -m http.server 3000
```

Open [http://localhost:3000](http://localhost:3000) in your browser.

---

## ☁️ Deployment on Vercel

This repository is pre-configured with `vercel.json` for zero-configuration, instant Edge CDN deployment:

1. Push your repository to GitHub:
   ```bash
   git push -u origin main
   ```
2. Log in to [Vercel](https://vercel.com).
3. Click **"Add New Project"** -> **"Import Git Repository"**.
4. Select `om_jewellers`.
5. Click **"Deploy"** (no build command needed, static files are deployed globally in seconds).

---

## 🔗 Repository Information

- **GitHub Remote**: `https://github.com/nashitabhulani/om_jewellers.git`
- **Main Landing Page**: `index.html`
- **Bespoke Atelier Page**: `customise.html`
- **Configuration**: `vercel.json`
