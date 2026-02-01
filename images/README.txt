================================================================================
  SHUSHI PRODUCTS — IMAGE FOLDER GUIDE
  Replace or add images here. Use the exact filenames below.
================================================================================

--------------------------------------------------------------------------------
1. LOGO (navigation bar)
--------------------------------------------------------------------------------
  Filename:   logo.png
  Where:      Top navigation bar, left side (next to "SHUSHI PRODUCTS" text)
  Format:     PNG (transparent background recommended)
  Size:       About 200–400px wide; height scales automatically (max ~48px tall)
  Notes:      If logo.png is missing, a default icon is shown instead.


--------------------------------------------------------------------------------
2. PRODUCT IMAGES (product-0.png through product-5.png)
--------------------------------------------------------------------------------
  These 6 images are used everywhere a product is shown. Use the EXACT
  filenames (no leading or trailing spaces):

  product-0.png  →  Whitening cream
  product-1.png  →  Shampoo & conditioner
  product-2.png  →  Face cleanser
  product-3.png  →  Body lotion
  product-4.png  →  Kojic Acid face cream
  product-5.png  →  Body oil

  Format:   PNG or JPG
  Size:     Recommended 600×750px or similar (portrait or square). Minimum
            ~400px on the shorter side for sharp display on all devices.

  Where each product image appears:
  • Hero slideshow (home page)     — The main rotating carousel at the top.
  • Products grid (home page)      — "Our Products" section cards.
  • Product detail page            — Large image when you click a product.
  • Similar products               — Thumbnails on the product detail page.
  • Collections screen             — Each set has a swipeable slide; each
                                    slide shows one product image filling
                                    the box.
  • Cart drawer                    — Small thumbnails next to each line item.

  If a product image file is missing, the site may show a blank or fallback
  area (no broken image icon).


--------------------------------------------------------------------------------
3. HERO SLIDESHOW / CAROUSEL (home page)
--------------------------------------------------------------------------------
  What it is:  The rotating showcase at the top of the home page with 5
               product cards (Whitening cream, Shampoo & conditioner, Face
               cleanser, Body lotion, Kojic Acid face cream). Cards slide
               left/right; one is centered, others are slightly behind.

  Images used:  SEPARATE hero images for the slideshow (you can use
                different images from the product grid):

    hero-0.png  →  Card 1 (Kojic acid serum)
    hero-1.png  →  Card 2 (Skin texture change)
    hero-2.png  →  Card 3 (shushi combo)
    hero-3.png  →  Card 4 (Skin needs)
    hero-4.png  →  Card 5 (Whitening cream)

  The hero slideshow uses only hero-0.png … hero-4.png (no product-image
  fallback).

  How to update:  Add or replace hero-0.png … hero-4.png in this folder
  with the images you want for the home-page slideshow. Refresh the page
  (hard refresh: Ctrl+Shift+R or Cmd+Shift+R if needed).


--------------------------------------------------------------------------------
4. COLLECTIONS SLIDESHOW (Collections page)
--------------------------------------------------------------------------------
  What it is:  On the Collections page, each "set" (e.g. Starter Set, Glow
               Routine, Complete Collection) has its own horizontal slide.
               You swipe or drag to see each product in the set. Each slide
               is one product image in a square box. Auto-slides slowly;
               slideshow pauses when the Details panel is open.

  Images used:  Same product images (product-0.png … product-5.png). Which
                image appears on which slide is determined by the set:
  • Starter Set:          product-3, product-4, product-0 (Body lotion,
                          Kojic Acid face cream, Whitening cream)
  • Glow Routine:         product-0, product-2, product-1 (Whitening cream,
                          Face cleanser, Shampoo & conditioner)
  • Complete Collection:  product-0 … product-5 (all 6 products)

  Display:  Each slide image is set to COVER the box (fills the frame; may
  crop edges). Use clear, well-centered product photos for best results.


--------------------------------------------------------------------------------
5. QUICK REFERENCE — FILE LIST
--------------------------------------------------------------------------------
  Put these files in the "images" folder (same folder as this README):

    logo.png
    product-0.png … product-5.png   (required for product grid, detail, cart)
    hero-0.png … hero-4.png         (optional; for home-page slideshow only)

  The home-page hero carousel uses hero-0.png … hero-4.png only (no
  product-image fallback).

  • No spaces in filenames (avoid " product-0.png" with a leading space).
  • Use lowercase. Format: .png or .jpg for products.


--------------------------------------------------------------------------------
6. TROUBLESHOOTING
--------------------------------------------------------------------------------
  • Images don’t show / I still see default icons or empty boxes
    — Use a local server to open the site (e.g. Live Server in VS Code, or
      run: python3 -m http.server 8000 in the project folder, then open
      http://localhost:8000). Opening index.html as file:// can block images.
    — Check filenames: exactly product-0.png, product-1.png, … (no leading
      or trailing space, no capital P).
    — Hard refresh: Ctrl+Shift+R (Windows/Linux) or Cmd+Shift+R (Mac).

  • Collection slide image is cropped or looks wrong
    — Collection slides use “cover” so the image fills the box. Use a
      portrait or square image with the product centered for best result.

  • Logo too big or too small
    — The site limits logo height (about 48px). Use a wide or square logo
      image; width can be up to about 200px on large screens.

================================================================================
