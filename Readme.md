# ImageAddiction Website

A modern IT services website for ImageAddiction ICT Services.

**Live Site:** [iaenterprise.com](https://iaenterprise.com)

**Contact:** imageaddictionictservices@gmail.com

---

## Recent Updates (February 2026)

### Design Modernization

- **Hero Section**: Modern design with tagline pill, clear headline, and dual CTA buttons
- **Navigation**: Single navigation bar with Services dropdown menu and "Get in Touch" CTA
- **Service Cards**: 6 modern service cards with icons and hover effects
- **Footer**: 4-column layout with company info, services, company links, and newsletter signup
- **Typography**: Inter font for headings, improved visual hierarchy

### Pages Updated

| Page | Changes |
|------|---------|
| `index.html` | New hero, navigation, services section, footer |
| `about.html` | Updated navigation and footer |
| `technology.html` | Updated navigation and footer |
| `contact.html` | Formspree integration, contact info cards, updated addresses |
| `Blog.html` | Updated navigation and footer |
| `Recharge.html` | Removed broken pagination, updated navigation and footer |
| `tutorial.html` | Complete redesign as resources hub with filtering |
| `blog_smile.html` | Professional article layout, removed placeholder content |
| `paypalpage.html` | Complete rebuild with step-by-step payment flow |

### New Features

#### Contact Form (contact.html)
- Formspree integration for email delivery
- Fields: First/Last name, Email, Phone, Subject dropdown, Message
- Honeypot spam protection
- Success message after submission

#### Resources Hub (tutorial.html)
- Filter tabs: All, Articles, Videos, Guides, External Links
- Card templates with clear comments for adding content
- Featured Git branching tutorial preserved
- JavaScript-based filtering

#### Payment Page (paypalpage.html)
- Step-by-step flow: Select service → Choose plan → Enter details → Pay
- Service types: IPTV, Smile Data, SmileVoice, Custom amount
- **IPTV Plans:**
  - 12 Months: €60
  - 24 Months: €100 (Best Value)
- Dynamic PayPal integration (charges actual selected amount)
- Bank transfer alternative (GTBank 0165422496)
- Help sidebar with contact info

#### New Article
- `article-it-infrastructure.html` - IT Infrastructure setup guide

---

## Project Structure

```
imageaddiction/
├── index.html              # Homepage
├── about.html              # About page
├── technology.html         # IT Services page
├── contact.html            # Contact form (Formspree)
├── Blog.html               # Blog listing
├── blog_smile.html         # SmileVoice article
├── tutorial.html           # Resources hub
├── article-it-infrastructure.html  # IT Infrastructure article
├── Recharge.html           # Recharge services
├── paypalpage.html         # Payment page
├── css/
│   └── style.css           # Compiled CSS
├── scss/
│   ├── _site-base.scss     # Base styles, footer
│   ├── _site-blocks.scss   # Content blocks, cards
│   └── _site-navbar.scss   # Navigation styles
├── js/                     # JavaScript files
├── images/                 # Image assets
└── fonts/                  # Icon fonts (icomoon, flaticon)
```

---

## Contact Information

**Germany Office**
Mozartstrasse, Leverkusen, Germany

**Nigeria Offices**
- 13 Ebenezer Crescent, Bwaji Across, Abuja
- 66 Oshodi Road, Ile Film Busstop, Lagos

**Phone:** +234 806 036 9525

**WhatsApp:** +234 806 036 9525

**Email:** imageaddictionictservices@gmail.com

---

## Development

### Local Testing
```bash
# Start local server
python3 -m http.server 8080

# View at http://localhost:8080
```

### SCSS Compilation
CSS is pre-compiled. If editing SCSS files, compile with:
```bash
sass scss/style.scss css/style.css
```

---

## Third-Party Integrations

- **Formspree** - Contact form submissions
- **PayPal** - Payment processing
- **Facebook Pixel** - Analytics (on Recharge page)
- **Plausible** - Analytics

---

© 2026 ImageAddiction ICT Services. All rights reserved.
