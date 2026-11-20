# XML Sitemap Validator | TAVARDT New Zealand

[![XML Sitemap Validator](https://img.shields.io/badge/TAVARDT-Sitemap%20XML-5b3cf5.svg)](https://tools.tavardt.com/nz/xml-sitemap-validator/)
[![Jurisdiction](https://img.shields.io/badge/Jurisdiction-New%20Zealand-00C853.svg)](https://ag.tavardt.com/nz/)
[![Python](https://img.shields.io/badge/Python-3.8%2B-blue.svg)](https://www.python.org/)

Independent XML sitemap audit suite for New Zealand digital assets, checking XML compliance, URL cleanliness, and search engine directives.

Engineered and maintained by the digital integrity and search systems division at **[TAVARDT New Zealand](https://ag.tavardt.com/nz/)**.

---

## XML Sitemap Validation Capabilities

* **Sitemaps.org Specification Checks**: Full compliance auditing for `<urlset>` and nested `<sitemapindex>` files.
* **Element Attribute Verification**: Verifies `<loc>` canonical targets, `<lastmod>` timestamps, and update intervals.
* **URL Integrity and Scheme Safety**: Detects mixed content, redirect chains, and XML encoding anomalies.
* **Volume Quota Monitoring**: Enforces standard 50,000 URL file limits to prevent crawler abandonment.
* **Index Readiness Rating**: Objective 0 to 100 score detailing prioritized XML optimizations.

---

## Installation and Execution

Requires Python 3.8 or higher with standard library.

```bash
git clone https://github.com/TAVARDT-New-Zealand/xml-sitemap-validator-nz.git
cd xml-sitemap-validator-nz
python sitemap_validator.py https://example.co.nz/sitemap.xml
```

For JSON format:

```bash
python sitemap_validator.py https://example.co.nz/sitemap.xml --json
```

---

## Online Diagnostic Platform

For recurring audits and real-time sitemap validation:

* **[Official XML Sitemap Validator](https://tools.tavardt.com/nz/xml-sitemap-validator/)**
* **[TAVARDT New Zealand Portal](https://ag.tavardt.com/nz/)**

---

## New Zealand Digital Architecture Advisory

For enterprise search indexing and compliance with NZ Web Standards and Sitemaps.org Protocol, contact the specialists at **[TAVARDT New Zealand](https://ag.tavardt.com/nz/contact/)**.
