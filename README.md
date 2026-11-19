# Delta Electric Services: Website, Local SEO & DNS Migration Case Study

Portfolio case study by **Elizabeth Pisarek**: an SEO-optimized Webflow website for Delta Electric Services, a licensed electrician in Red River, New Mexico. I handled strategy, UX/UI design, local SEO, the Webflow build, the domain transfer, the DNS migration, 301 redirects and Core Web Vitals tuning.

**View the case study:** https://lizpisarek2.github.io/delta-electric-case-study/
**View the site as launched (archived copy):** https://lizpisarek2.github.io/delta-electric-case-study/#launch-site

## Results at launch (Google PageSpeed Insights, Nov 18, 2026)

| Category | Mobile | Desktop |
|---|---|---|
| Performance | 98 | 100 |
| Accessibility | 98 | 98 |
| Best Practices | 100 | 100 |
| SEO | 100 | 100 |
| Agentic Browsing | 2/2 | 2/2 |
| Largest Contentful Paint | 1.5 s | 0.4 s |
| Cumulative Layout Shift | 0.088 | 0.001 |
| Total Blocking Time | 0 ms | 0 ms |

Original reports: [mobile](https://pagespeed.web.dev/analysis/https-www-deltaelectricservices-com/sp3p3g5dxn?form_factor=mobile) · [desktop](https://pagespeed.web.dev/analysis/https-www-deltaelectricservices-com/sp3p3g5dxn?form_factor=desktop)

## The project

The client's site was a Duda template bundled with Housecall Pro. The vendor held the domain, the DNS lived in an AWS Route 53 zone the owner couldn't access, and the site had no structured data, a generic headline and leftover template text. In two weeks I:

- **UX / UI:** turned five thin pages into one mobile-first landing page with click-to-call, anchor navigation and an accessible FAQ accordion, using the existing brand.
- **SEO:** rewrote the copy around local search ("electrician Red River NM"), added an Electrician + FAQPage JSON-LD schema, and set the title, meta description and Open Graph tags.
- **Marketing:** wrote copy for second-home and cabin owners, property managers and local businesses, and routed leads into the owner's Buildertrend account.
- **Webflow build:** built the page from native, editable Webflow elements with scoped classes and custom code embeds.
- **Domain & DNS:** recovered the domain to Namecheap (2FA, domain lock, WHOIS privacy), switched nameservers off Route 53, added the Webflow A, CNAME and TXT records, set www as the primary domain over SSL, and mapped every legacy URL with a 301 redirect.
- **Performance & QA:** removed layout shift (reserved logo space, `font-display: optional`), optimized the form embed, and tested every breakpoint, redirect and form submission.

## Tools & platforms

Webflow · HTML5 · CSS3 · JavaScript · JSON-LD / Schema.org · Namecheap · AWS Route 53 · Buildertrend · Google Fonts · Google PageSpeed Insights · Lighthouse · Chrome DevTools · MXToolbox · DNSChecker · WHOIS/RDAP · Wix (evaluated) · Duda & Housecall Pro (legacy) · Claude (Anthropic) with the Webflow MCP connector

## About this repository

`index.html` is a single self-contained page that GitHub Pages serves as-is. The archived copy of the site is a static snapshot from launch day (Nov 18, 2026), so it doesn't change when the client edits the live site. Its contact form doesn't send, so it never reaches the client.

## Contact

**Elizabeth Pisarek**: full-stack web developer, UX/UI, SEO and project management
lizpisarek@gmail.com · [lizpisarek.wixsite.com/portfolio](https://lizpisarek.wixsite.com/portfolio)
