# QRRQ — Free QR Code Generator

**Create dynamic QR codes** with real-time analytics, custom designs, password protection, and link pages.

🔗 **[Try it free → qrrq.io](https://qrrq.io)**

---

## What is QRRQ?

QRRQ is a modern **QR code generator** built for businesses, marketers, and developers who need more than a simple static QR code. Create **dynamic QR codes** that you can edit, track, and manage — all from one dashboard.

### Why QRRQ?

| Feature | Free | Starter | Pro | Business |
|---|:---:|:---:|:---:|:---:|
| Dynamic QR Codes | 3 | 50 | 200 | Unlimited |
| Static QR Codes | Unlimited | Unlimited | Unlimited | Unlimited |
| Scan Analytics | Basic | Full | Full | Full |
| Custom QR Designs | Limited | Full | Full | Full |
| Link Pages | — | 5 | 15 | Unlimited |
| Password Protection | — | ✓ | ✓ | ✓ |
| Bulk QR Creation | — | — | ✓ | ✓ |
| API Access | — | — | ✓ | ✓ |
| Custom Domain | — | — | — | ✓ |

---

## Supported QR Code Types

QRRQ supports **15+ QR code types** for every use case:

- **URL** — Link to any website with scan tracking
- **PDF** — Share documents via QR code
- **vCard** — Digital business cards
- **WiFi** — One-scan WiFi connection
- **Email** — Pre-filled email composer
- **Phone** — Instant dial
- **SMS** — Pre-written text messages
- **WhatsApp** — Direct WhatsApp chat
- **Location** — Google Maps pin
- **Event** — Calendar event with RSVP
- **Plain Text** — Any text content
- **Social Media** — All social profiles in one QR
- **Multi-URL** — Smart redirects by device, location, or time
- **App Store** — iOS & Android download links
- **Crypto** — Wallet address & payment requests

---

## Dynamic QR Codes vs Static QR Codes

| | Dynamic QR Code | Static QR Code |
|---|---|---|
| Edit after print | ✓ Change destination anytime | ✗ Fixed forever |
| Scan analytics | ✓ Real-time tracking | ✗ No data |
| A/B testing | ✓ Test different destinations | ✗ Not possible |
| Password protection | ✓ Secure access | ✗ Open to all |
| Expiration dates | ✓ Set start/end dates | ✗ Always active |
| Scan limits | ✓ Control usage | ✗ Unlimited scans |

**[Create your first dynamic QR code →](https://qrrq.io)**

---

## QR Code Design Customization

Make your QR codes stand out:

- **Colors** — Custom foreground & background colors
- **Logos** — Upload your brand logo to the center
- **Patterns** — Square, rounded, dots, and more
- **Eye shapes** — Customize corner markers
- **Frames** — Add call-to-action frames
- **Templates** — Save & reuse your designs

---

## Link Pages

Create beautiful **micro landing pages** with a single QR code:

- 12 block types: links, headers, social media, YouTube, Spotify, contact forms, maps, and more
- 12 premium themes with customizable colors
- Click tracking and visitor analytics
- Mobile-optimized responsive design

**[Explore Link Pages →](https://qrrq.io/features)**

---

## Real-Time Analytics

Track every scan with detailed analytics:

- **Total scans** — Daily, weekly, monthly breakdown
- **Location data** — Country, city, region
- **Device info** — Mobile vs desktop, OS, browser
- **Time analysis** — Peak scanning hours
- **Unique vs total** — Filter repeat scans
- **Export** — Download reports as CSV

---

## REST API

Integrate QR code generation into your workflow:

```bash
# Create a dynamic QR code
curl -X POST https://qrrq.io/api/v1/qr \
  -H "Authorization: Bearer YOUR_API_KEY" \
  -H "Content-Type: application/json" \
  -d '{
    "type": "url",
    "title": "My Website",
    "data": { "url": "https://example.com" }
  }'
```

```bash
# Get scan analytics
curl https://qrrq.io/api/v1/qr/{id}/analytics \
  -H "Authorization: Bearer YOUR_API_KEY"
```

Full API documentation available at **[qrrq.io/dashboard/api-docs](https://qrrq.io/dashboard/api-docs)**

---

## Use Cases

- **Restaurants** — Digital menus, WiFi QR codes, review links
- **Retail** — Product info, promotions, loyalty programs
- **Events** — Tickets, schedules, registration forms
- **Real Estate** — Property listings, virtual tours
- **Education** — Course materials, attendance tracking
- **Marketing** — Campaign tracking, A/B testing, UTM parameters
- **Business Cards** — vCard QR codes with full contact info
- **Packaging** — Product authentication, user manuals

---

## Getting Started

1. **Sign up free** at [qrrq.io](https://qrrq.io)
2. Choose your QR code type
3. Customize design and colors
4. Download in PNG, SVG, or PDF
5. Track scans in real-time

---

## Multi-Language Support

QRRQ is available in **5 languages**:

- 🇬🇧 English — [qrrq.io](https://qrrq.io)
- 🇹🇷 Türkçe — [qrrq.io/tr](https://qrrq.io/tr)
- 🇩🇪 Deutsch — [qrrq.io/de](https://qrrq.io/de)
- 🇪🇸 Español — [qrrq.io/es](https://qrrq.io/es)
- 🇷🇺 Русский — [qrrq.io/ru](https://qrrq.io/ru)

---

## License

This project is licensed under the [MIT License](LICENSE).

---

**[Create Free QR Code →](https://qrrq.io)** | **[Pricing →](https://qrrq.io/pricing)** | **[Features →](https://qrrq.io/features)** | **[Blog →](https://qrrq.io/blog)** | **[Contact →](https://qrrq.io/contact)**
