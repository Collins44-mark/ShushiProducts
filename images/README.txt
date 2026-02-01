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
  These 6 images are used everywhere a product is shown. Use the EXACT filenames:

  product-0.png  →  Rose Elixir Serum
  product-1.png  →  Green Tea Cream
  product-2.png  →  Vitamin C Drops
  product-3.png  →  Lavender Cleanser
  product-4.png  →  Rose Mist Toner
  product-5.png  →  Honey Glow Mask

  Format:   PNG or JPG
  Size:     Recommended 600×750px or similar (portrait or square). Minimum ~400px
            on the shorter side for sharp display on all devices.

  Where each product image appears:
  • Hero slideshow (home page)     — The main rotating carousel at the top.
  • Products grid (home page)      — "Our Products" section cards.
  • Product detail page            — Large image when you click a product.
  • Similar products               — Thumbnails on the product detail page.
  • Collections screen             — Each set has a swipeable slide; each slide
                                    shows one product image filling the box.
  • Cart drawer                    — Small thumbnails next to each line item.

  If a product image file is missing, the site shows a default graphic for that
  product instead (no broken image).


--------------------------------------------------------------------------------
3. HERO SLIDESHOW / CAROUSEL (home page)
--------------------------------------------------------------------------------
  What it is:  The rotating showcase at the top of the home page with 5 product
               cards (Rose Elixir, Green Tea Cream, Vitamin C Drops, Lavender
               Cleanser, Rose Mist Toner). Cards slide left/right; one is
               centered, others are slightly behind.

  Images used: product-0.png, product-1.png, product-2.png, product-3.png,
               product-4.png  (one image per card, in that order)

  How to update:  Replace product-0.png … product-4.png in this folder. Refresh
  the page (hard refresh: Ctrl+Shift+R or Cmd+Shift+R if needed). No code
  changes required.


--------------------------------------------------------------------------------
4. COLLECTIONS SLIDESHOW (Collections page)
--------------------------------------------------------------------------------
  What it is:  On the Collections page, each "set" (e.g. Starter Set, Glow
               Routine) has its own horizontal slide. You swipe or drag to see
               each product in the set. Each slide is one product image in a
               fixed 4:3 box.

  Images used:  Same product images (product-0.png … product-5.png). Which
                image appears on which slide is determined by the set:
  • Starter Set:          product-3, product-4, product-0 (3 slides)
  • Glow Routine:          product-0, product-2, product-1 (3 slides)
  • Complete Collection:  product-0 … product-5 (6 slides)

  Display:  Each slide image is set to COVER the box (fills the frame; may
  crop edges). Use clear, well-centered product photos for best results.


--------------------------------------------------------------------------------
5. QUICK REFERENCE — FILE LIST
--------------------------------------------------------------------------------
  Put these files in the "images" folder (same folder as this README):

    logo.png
    product-0.png
    product-1.png
    product-2.png
    product-3.png
    product-4.png
    product-5.png

  No spaces in filenames. Use lowercase. Format: .png or .jpg for products.


--------------------------------------------------------------------------------
6. TROUBLESHOOTING
--------------------------------------------------------------------------------
  • Images don’t show / I still see default icons
    — Use a local server to open the site (e.g. Live Server in VS Code, or
      run: python3 -m http.server 8000 in the project folder, then open
      http://localhost:8000). Opening index.html as file:// can block images.
    — Check filenames: exactly product-0.png, product-1.png, … (no space, no
      capital P).
    — Hard refresh: Ctrl+Shift+R (Windows/Linux) or Cmd+Shift+R (Mac).

  • Collection slide image is cropped or looks wrong
    — Collection slides use “cover” so the image fills the box. Use a
      portrait or square image with the product centered for best result.

  • Logo too big or too small
    — The site limits logo height (about 48px). Use a wide or square logo
      image; width can be up to about 200px on large screens.

================================================================================
