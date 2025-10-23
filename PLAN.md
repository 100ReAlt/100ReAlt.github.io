# ActiveStride Web Plan

## 1. Current Experience Audit
- **Hero Campaign:** Verify hero copy, CTA buttons, and background imagery align with Spring Collection 2025 asset library.
- **Performance Metrics:** Confirm marketing-approved statistics (50K+ athletes, 500+ products, 98% satisfaction, 24/7 support) each quarter.
- **Product Highlights:** Ensure "New Arrivals" card data (pricing, discount labels, color counts) is synchronized with the e-commerce catalog.
- **Storytelling Block:** Keep video thumbnail, headline "Performance Meets Innovation," and narrative focused on innovation and sustainable materials.
- **Category Navigation:** Footwear, Apparel, and Equipment cards should link to their respective category landing pages.
- **Testimonials:** Refresh quotes, headshots, and roles at least biannually to maintain authenticity.
- **Brand Trust Bar:** Validate partner logos licensing and reorder as needed to reflect strategic partnerships.
- **Service Guarantees:** Audit iconography and supporting copy for Free Shipping, Secure Payment, 24/7 Support, and Quality Guarantee.
- **Newsletter CTA:** Confirm subscription form integrates with the current CRM and honors privacy commitments.
- **Footer:** Update support links (Contact Us, Size Guide, Shipping & Returns, FAQ) when site architecture changes.

## 2. Near-Term Enhancements (Next 1-2 Sprints)
1. **Localization Prep:** Externalize all marketing copy into a JSON/ARB resource file to support upcoming Spanish translation.
2. **Dynamic Catalog Feed:** Replace hard-coded "Latest Drops" with data pulled from a headless commerce API.
3. **Video Modal:** Implement a modal or lightbox that plays the brand story video when the track thumbnail play button is pressed.
4. **Accessibility Review:** Conduct WCAG 2.1 AA audit, focusing on color contrast in hero overlay, CTA buttons, and testimonial cards.
5. **Performance Budget:** Target <2.5s Largest Contentful Paint on mid-tier mobile devices by optimizing image delivery.

## 3. Long-Term Roadmap
- **Personalized Recommendations:** Tailor product cards based on user browsing history or referral source.
- **Athlete Stories Hub:** Create a dedicated section aggregating long-form stories linked from the hero and newsletter.
- **Retail Events Calendar:** Add an interactive calendar highlighting pop-up events and demo runs.
- **Loyalty Program Integration:** Surface reward tiers and points balance for authenticated customers.
- **Progressive Web App Enhancements:** Leverage service worker updates for offline catalog browsing and push notifications.

## 4. Workflow Notes
- Maintain Flutter source in a separate repository and treat this repo as the deployable artifact.
- Document all copy changes with marketing approval dates.
- Capture desktop and mobile screenshots after each major visual update for historical reference.
- Use feature branches per enhancement and follow the contribution guidelines in `AGENTS.md`.
