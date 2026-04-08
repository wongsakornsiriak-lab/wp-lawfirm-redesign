# Wongsakorn Law Office - Website Redesign Plan

## Date: April 8, 2026

---

## 1. Website Overview

**URL:** https://www.wongsakornsirilawfirm.com/

**Business:** Thai law firm with 10+ years experience

### Contact Information

- **Address:** 89/94 Moo 12 BangKaew, Bangpli, Samut Prakan, Thailand 10540
- **Phone:** 062-195-1661
- **Line:** @wongsakorn
- **Fax:** 02-136-7521

### Key Personnel

- **Attorney "Arm" Supasit Siri** - Lead lawyer, specializes in insurance law, civil litigation, criminal proceedings

### Practice Areas

- Consultant Attorney
- Family Lawyer
- Civil Lawyer
- Inheritance Lawyer
- Consumer Lawyer
- Insurance Lawyer
- Contract Drafting Services
- Attorney Certifies Signature
- Criminal Lawyer
- Defamation Lawyer
- Selected Court Documents in Bangkok and Vicinity

---

## 2. Current Website Technology

- **CMS:** WordPress
- **Theme:** Flatsome (child theme)
- **Language:** Multi-language (English, Thai, Chinese)

---

## 3. Redesign Requirements

### New Tech Stack

- **Theme:** Blocksy
- **Page Builder:** Elementor
- **E-commerce:** WooCommerce

### Goals

- Modern JS tech stack look and feel
- Preserve all existing media and posts
- Maintain SEO rankings
- No data loss

---

## 4. Recommended Approach

### Option A: Staging Site (Recommended)

1. Create staging environment (staging.wongsakornsirilawfirm.com or separate domain)
2. Clone production to staging
3. Install Blocksy + Elementor on staging
4. Build new design
5. Switch to production when ready

### Option B: Local Development with ddev

1. Clone production to local via ddev
2. Develop locally
3. Careful search & replace when pushing back
4. Export/import posts if issues arise

### SEO Protection Checklist

- [ ] Keep same URL structure
- [ ] Do not change slugs
- [ ] Export/import SEO plugin settings (Yoast/RankMath)
- [ ] Preserve all meta descriptions
- [ ] 301 redirect only if absolutely necessary

---

## 5. Next Steps

- [ ] Set up staging environment
- [ ] Clone production site
- [ ] Install Blocksy theme
- [ ] Install Elementor
- [ ] Install WooCommerce (if needed for any products)
- [ ] Begin redesign process
- [ ] Test all existing content
- [ ] Verify SEO settings
- [ ] Plan production switch

---

## Notes

- WordPress site with lots of media and posts
- Multi-language support must be maintained
- Insurance law specialization is a key differentiator for the firm
- Attorney Arm has unique perspective on human life valuation in legal cases

## Thing to remeber

- to update the this file according to what I ask and what you did in oder to make a proper session handoff for next time development resume
