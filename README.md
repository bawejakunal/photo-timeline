# Photo Timeline (2011–2026)

Interactive monthly histogram of **18,855 unique photos** captured across dedicated cameras, phones, and Ray-Ban Meta Smart Glasses — merging Lightroom Classic catalog metadata with a Google Photos Takeout archive.

**Live chart:** https://bawejakunal.github.io/photo-timeline/

![Monthly Photo Histogram Preview](preview.png)

## Dataset Breakdown
- **Sources:** 12,623 photos from Lightroom Classic (through Oct 2026) + 6,232 deduplicated additions from Google Photos Takeout (through Sep 13, 2025)
- **By Device Category:**
  - **Dedicated Cameras:** 12,317 (Canon EOS 6D Mark II, Canon EOS 600D, Sony α7R III, Sony DSC-W830, etc.)
  - **Phones:** 6,105 (Pixel 6, Pixel 9 Pro XL, Nexus 5X, Pixel 3a, Pixel 5a, Pixel 4a 5G, Moto G6, etc.)
  - **Ray-Ban Meta Smart Glasses:** 433
- **Deduplication & Cleaning:** Excludes virtual copies, videos, screenshots, WhatsApp/social/Snapseed saves, Google Photos auto-compositions, shared-album photos from others, Pixel RAW+JPEG / Portrait companion duplicates, and Lightroom exports uploaded to Google Photos.

## Interactive Features
- **Monthly, Yearly, and Jan–Dec seasonality views**
- **Click any year** to zoom into its 12-month breakdown
- **Filter by source** (All / Lightroom Classic / Google Photos), **device category or model**, and **Lightroom rejected (`X`) flag**
- **Dark / Light theme toggle** with mobile touch tooltip support
- Zero external dependencies — single static `index.html`
