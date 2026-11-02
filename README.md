# Eagra Labs public website

Static website for https://eagralabs.com, hosted by GitHub Pages from the main branch.

The public site focuses on FullPlan: home, product overview, company background and contact. Customer sign-in links point to https://fullplan.eagralabs.com/. Pricing is not published while the commercial structure is being finalised.

Root marketing content and assets were removed from this website in the FullPlan-focus change. Earlier versions remain in Git history for future reintroduction; the separate Root website and application are not modified.

Preview with `python3 -m http.server 8767 --bind 127.0.0.1`. There is no build step. Contact forms prepare an email in the visitor’s email application; they do not send messages automatically.

## Search visibility

Each public page has a unique search title and description, a self-canonical URL, Open Graph and Twitter preview metadata, and JSON-LD for the organisation, website and page. Interior pages include breadcrumb data; the product page describes FullPlan as a WebApplication without invented offers or ratings. The pull-planning guide provides an introduction and links to the product and demo enquiry.

The sitemap lists the five public canonical URLs. Update `lastmod` only when page content meaningfully changes. After publication, verify eagralabs.com in Google Search Console, submit `https://eagralabs.com/sitemap.xml`, and inspect the homepage, product and guide URLs. Search Console verification and sitemap submission are account-side steps, not performed by this repository. Structured data does not guarantee rich results or rankings.
