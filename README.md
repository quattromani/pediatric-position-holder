# Pediatric Position Holder: review concept

Review site for the inventors and partners, published separately through GitHub Pages. The current website and its domain remain unchanged.

- Repository: https://github.com/quattromani/pediatric-position-holder
- Review site: https://quattromani.github.io/pediatric-position-holder/
- Status: design concept, not final product copy. The site is public; noindex requests search exclusion but is not access control.

## Brief

Help clinicians and prospective partners quickly understand the positioning problem, recognize the device, and start a conversation. Primary audience: radiology, emergency, and outpatient clinicians, with transport professionals as an exploratory audience. Occasional visits following referrals or search, on desktop or mobile. This is a tangible clinical device: use literal, existing product illustration rather than invented photography. Qualities: clear, calm, humane, practical, credible. The current site is academic and exhaustive; the concept is concise and product-led. Soft green, warm white, dark teal, and a serif headline balance clinical credibility with warmth. The original blue illustration provides continuity.

The mockup is intentionally one page. The eventual site can move clinical background, supporting evidence, and resources onto dedicated pages. Native expandable sections demonstrate progressive disclosure now.

## Source and claim boundaries

- Existing public website reviewed October 30, 2026: https://pediatricpositionholder.com/
- Material change only: Max clarified that the device design is unchanged. Originally developed with inexpensive material for single use, it now uses more durable material for reuse. Existing drawings and illustrations still represent the design.
- Ground and air transport interest: supplied by Max, reporting the inventor's conversations. Interest is not clinical validation or clearance.
- Existing illustration and inventor portrait: downloaded from the current website. The existing illustration remains representative of the unchanged design; new imagery is optional.
- Current intended use, availability, materials, dimensions, cleaning validation, reuse limits, current regulatory status remain to be confirmed by inventors before final product-site publication.
- No superiority, radiation reduction, repeat-procedure reduction, anxiety reduction, transport suitability, or approval claims adopted.
- Omitted the four requested blocks: Yearly Procedural Need; Additional Context and Sources for These Estimates; Estimated Number of Pediatric Patients Annually; Which Medical Professionals Would Benefit from the Pediatric Position Holder.
- Removed old video, single-use positioning, speculative retail availability, market estimates, testimonials pending permissions/version confirmation, regulatory table pending verification, and unsupported categorical claims from concept.
- Do not use the website's “not a restraint” claim as settled status. The existing page's classification definition uses restraint language. Resolve before publishing classification copy.
- Both phone numbers are drawn from the current page. Its second phone link points to a different number than the visible text; this mockup uses the visible number, (806) 241-0373. Confirm before final product-site launch.

## Review criteria

Lead with the child's need to remain still. Show the device immediately. Make reuse prominent. Preserve child-centered clinical judgment. Make transport's exploratory status explicit. Avoid the four removed content blocks. Offer concise introductions with accessible native disclosures. Provide working internal links and phone links, responsive layouts, and visible keyboard focus. No external scripts or frameworks.

## Files

`index.html` and `styles.css` are the reviewable mockup. `assets/positioning.jpeg` illustrates the unchanged holder design and `assets/frank.jpg` is the inventor portrait. These assets retain their existing ownership. No AI-generated clinical images are used.

Run any local static web server in this folder. This is a design artifact rather than approved medical-device advertising or instructions for use.


## Publishing and maintenance

GitHub Pages serves the root of `main`. The `.nojekyll` file keeps this a buildless static site. Push reviewed changes to `main` to publish updates. Relative asset paths support the project URL. No CNAME file or custom domain is configured.

Run locally with `python3 -m http.server 8765`, then open http://localhost:8765/. No packages or build step are required.

To roll back a published change, revert its commit and push the revert to `main`. Keep the review banner and noindex directive until the user explicitly approves a final public launch. The production domain and Network Solutions configuration must remain unchanged unless separately authorized.

## Validation

October 30, 2026: local desktop and narrow mobile viewport checks; no horizontal overflow; images loaded; internal links resolved; native disclosures worked with mouse and keyboard. These are bounded review-site checks, not a complete accessibility conformance audit or clinical validation. Phone calls were not placed. The positioning illustration represents the unchanged design, transport suitability remains exploratory, and the four removed content blocks remain absent.
