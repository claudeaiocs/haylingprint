# Hayling Print — Mobile App Concept

A mobile app concept for [Hayling Print Ltd](https://haylingprint.co.uk/), a print and design studio based on Hayling Island, Hampshire.

## 🖨️ What Is This?

A Flutter-based mobile app (iOS + Android) that puts Hayling Print's full product catalogue, ordering, artwork upload, proof approval, and order tracking in their customers' pockets.

## 📱 Key Features

### 🛒 Mobile Ordering
Browse and configure every product on the go — business cards, banners, booklets, stationery, clothing, signage, merchandise. Full product configurator: paper type, finish, quantity, size, single/double sided. Instant pricing.

### 📤 Artwork Upload
Upload print-ready artwork directly from phone — camera, gallery, or cloud storage (Google Drive, Dropbox, iCloud). File validation checks (resolution, bleed, colour space) before submission.

### ✅ Proof Approval
Review, zoom, and approve design proofs on phone. Comment directly on proofs — "Make the logo bigger", "Change this colour". Version history so nothing gets lost. Push notification: "Your proof is ready for review!"

### 📦 Order Tracking
Real-time order status: Received → Artwork Check → Printing → Finishing → Dispatched. Push notifications at every stage. Delivery tracking integration.

### 🔄 One-Tap Reorder
Repeat customers can reorder previous jobs in seconds. Same specs, same artwork — just tap and go. Perfect for businesses who order stationery regularly.

### 💬 Quick Quote
Describe what you need, upload a reference image, get a quote back. In-app chat with the Hayling Print team for bespoke jobs.

### 🎨 Design Request
Don't have artwork? Request Hayling Print's design service directly through the app. Upload your brief, logo, brand colours — they create it for you. Approve in-app.

### 🔔 Push Notifications
- "Your proof is ready to review!"
- "Order #4521 has been dispatched"
- "Spring Sale: 20% off all banners this week"
- "Your business cards are running low — reorder?"

### 🏷️ Trade / Account Pricing
Logged-in trade customers see their discounted pricing. Account management, order history, invoices all in one place.

## 💰 Business Value

| Benefit | Impact |
|---------|--------|
| Mobile ordering | Captures orders from customers on the go |
| Proof approval | Eliminates email ping-pong, speeds up turnaround |
| Reorder | Increases repeat business with zero friction |
| Push marketing | Drives sales with targeted promotions |
| Artwork upload | Reduces admin, files arrive correctly formatted |
| Order tracking | Fewer "where's my order?" phone calls |
| Trade accounts | Locks in B2B customers with convenience |
| 1-day express | Urgent orders placed instantly from anywhere |

## 📱 Tech Stack

- **Framework:** Flutter (Dart)
- **Platforms:** iOS + Android from single codebase
- **Backend:** API integration with existing ordering system
- **Storage:** Cloud file upload for artwork (S3/Firebase Storage)
- **Notifications:** Firebase Cloud Messaging
- **Payments:** Stripe integration

## 📂 Project Structure

```
haylingprint/
├── README.md
├── PITCH.md          # Sales pitch document
├── mockups/          # App screen mockups
│   ├── home-screen.png
│   ├── product-config.png
│   ├── order-tracking.png
│   └── proof-approval.png
└── lib/              # Flutter source (TBD)
```

## 🖼️ Mockups

See the `mockups/` folder for initial screen concepts:
- **Home Screen** — Dashboard with quick access to ordering, uploads, and tracking
- **Product Configurator** — Business card builder with specs, pricing, and express options
- **Order Tracking** — Live order status with reorder capability
- **Proof Approval** — Review, comment, and approve proofs on mobile

## Status

🟡 **Pitch phase** — Mockups and sales materials ready. Awaiting client meeting.

---

Built by OCS Consulting
