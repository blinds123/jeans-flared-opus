# Landing Page Build Plan: Flared Denim Jeans (jeans-flared-opus)

## Project Overview

**Product:** Flared Denim Jeans inspired by LOVA FLARED DENIM
**Target Audience:** Gen Z Girls (18-24)
**Competition Analysis:** alobhalabel.com - 699 KR (~$66), 80% cotton/17% polyester/3% spandex, sold out across all sizes

**Deployment Target:**
- **GitHub Repo:** NEW - `jeans-flared-opus`
- **Netlify Site:** NEW - `jeans-flared-opus.netlify.app`
- **CRITICAL:** DO NOT overwrite existing sites

---

## Current Directory Analysis

**Template Location:** `/Users/nelsonchan/Downloads/rebuild-landing-template Jeans Opus`

**Assets Found:**
- Product Images: 4 images in `images/product/`
  - `prodsneaker12341 (7) copy.jpg`
  - `Gemini_Generated_Image_kniughkniughkniu copy.png`
  - `Gemini_Generated_Image_6nmnib6nmnib6nmn copy.png`
  - `Gemini_Generated_Image_2q2h7d2q2h7d2q2h copy.png`

- Testimonial Avatars: 22 images in `images/testimonials/`
  - Various Gemini generated images

- Worn by Favorites: 3 influencers (pre-included)
  - `alix-earle.webp`
  - `monet-mcmichael.webp`
  - `alex-cooper.webp`

---

## Execution Plan

### Phase 1: Pre-Deployment Setup (1 minute)

1. **Pricing Configuration**
   - Use DEFAULT pricing: $59 Order / $19 Pre-order / $29 Pre-order+Bump
   - Pool server: `https://simpleswap-automation-1.onrender.com` (ready)

2. **Testimonial Count Verification**
   - Count: 22 testimonial images found
   - Will generate exactly 22 product-specific testimonials

### Phase 2: Parallel Agent Execution (3-4 minutes)

Run all agents simultaneously for maximum speed:

**Agent 1: Color Extraction**
- Input: Product images (flared denim jeans)
- Output: Primary color palette (likely navy/denim blue tones)
- Colors for: CTAs, badges, accents, social proof elements

**Agent 2: Order Bump Stylist**
- Product: Flared Denim Jeans
- Choose matching accessory (silver belt, chain earrings, or vintage chain necklace)
- Source from Pexels (fashion accessory that complements jeans)

**Agent 4: Testimonial Generator**
- Count: 22 testimonials (matching avatar count)
- Style: Gen Z native language (lowercase, casual, TikTok-native)
- Platform distribution: TikTok (40%), Instagram (25%), Others (35%)
- Focus: Flared denim fit, stretch comfort, versatility

**Agent 5: Product Tabs Generator**
- Shipping info
- Returns policy
- Care instructions (denim-specific)
- Size guide (with sizing similar to competition: 32-44)

**Agent 6A: Page Builder**
- Build complete index.html from template
- Replace all {{PLACEHOLDERS}}
- Link all 22 testimonial images correctly
- Apply extracted color palette

**Agent 6B: Image Optimizer**
- Convert all images to WebP
- Generate responsive sizes (600px, 800px, 1200px)
- Target: Sub-1.8s mobile load time

### Phase 3: Content Generation Details

**Product Copy Focus (Gen Z Voice):**
- Product Name: "Flared Denim Jeans"
- Tagline: "the flare that's taking over your fyp"
- Description: Stretch comfort, vintage-inspired flare, all-day wearability

**Testimonial Voice Examples:**
- "obsessed. literally got 3 compliments in one hour"
- "the stretch is *chef's kiss* - so comfy for all day"
- "no bc why does flare hit so different"
- "my new go-to jeans for literally everything"

**Urgency Elements:**
- XL/XXL sold out (scarcity)
- XS sells out after 15 seconds (dynamic)
- Live viewer count
- Stock counter

### Phase 4: Deployment (2 minutes)

**GitHub:**
1. Initialize new git repo in directory
2. Set remote: `github.com/blinds123/jeans-flared-opus`
3. Initial commit with all files
4. Push to main

**Netlify:**
1. Create NEW site (not link to existing!)
2. Site name: `jeans-flared-opus`
3. Connect to GitHub repo
4. Deploy with build settings
5. Verify serverless functions work

### Phase 5: Verification

1. Load page in mobile viewport
2. Verify all 22 testimonial images load
3. Verify color palette matches denim aesthetic
4. Test checkout flow (both $59 and $19 tiers)
5. Confirm load time < 1.8s

---

## Expected Deliverables

| Item | Details |
|------|---------|
| **Live URL** | `https://jeans-flared-opus.netlify.app` |
| **GitHub** | `https://github.com/blinds123/jeans-flared-opus` |
| **Testimonials** | 22 product-specific reviews |
| **Load Time** | < 1.8s mobile |
| **Pricing** | $59 Order / $19 Pre-order / $29 w/ Bump |

---

## Gen Z Design Focus

1. **Color Palette:** Extracted from denim product images
2. **Copy Voice:** Lowercase, casual, friend energy
3. **Social Proof:** Platform badges (TikTok, Instagram focus)
4. **Trust Elements:** 30-day returns, free shipping
5. **Urgency:** Sold-out sizes, low stock warnings
6. **Worn by Favorites:** Alix Earle, Monet McMichael, Alex Cooper

---

## Critical Reminders

- **NEW** GitHub repo (do not use existing)
- **NEW** Netlify site (do not overwrite)
- **Exact** 22 testimonials (match image count)
- **Gen Z** language throughout
- **Mobile-first** optimization
- **Sub-1.8s** load time target

---

## Estimated Timeline

| Phase | Duration |
|-------|----------|
| Setup & Pricing | 1 min |
| Agent Execution (parallel) | 3-4 min |
| Page Assembly | 1 min |
| Deployment | 2 min |
| Verification | 1 min |
| **Total** | **~8 minutes** |

---

**Ready to execute upon approval.**
