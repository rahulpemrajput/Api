# Api

## BigBasket Clone — Free Launch Plan

This repository can be used as the backend foundation for a low-cost grocery delivery MVP. Below is a practical launch plan focused on free tooling and fast validation.

### 1) Define MVP scope (Week 1)
- Must-have modules: product catalog, category filters, search, cart, checkout intent, and order placement.
- Start with Cash on Delivery (COD) only; add online payments after first traction.
- Keep service area limited to one pin-code cluster to simplify operations.

### 2) Backend readiness (Week 1–2)
- Stabilize product APIs (list, detail, category, stock, pricing).
- Add request validation and error formatting.
- Add environment-based config for database URI and app port.
- Add basic admin-only endpoints for inventory updates.

### 3) Free infrastructure stack (Week 2)
- Runtime: Render/Fly.io free tier (or Railway trial credits).
- Database: MongoDB Atlas free cluster.
- CDN/media: Cloudinary free tier for product images.
- Monitoring: UptimeRobot + free logging (platform logs).

### 4) Frontend MVP (Week 2–3)
- Build a simple responsive storefront (React/Next.js).
- Pages: Home, Category, Product Detail, Cart, Checkout, Order Success.
- Use API-first integration from this repo.
- Ship a basic PWA for “install app” experience without native app costs.

### 5) Operations setup (Week 3)
- Inventory source: start with 100–200 high-frequency SKUs.
- Fulfillment flow: order -> packing list -> rider dispatch.
- Customer updates via WhatsApp templates/manual messages.
- Maintain a daily stock and substitution sheet.

### 6) Free growth channels (Week 3–4)
- Hyperlocal acquisition: apartment groups, local influencers, referral coupons.
- SEO basics: index category and product pages.
- Content loop: “today’s offers” banner + shareable links.
- Referral mechanism: first-order discount + give/get credits.

### 7) Metrics to track from day one
- Daily active users, add-to-cart rate, checkout conversion.
- Average order value (AOV).
- Repeat purchase rate (7-day, 30-day).
- Delivery success rate and refund percentage.

### 8) 30-day rollout target
- Day 1–7: API hardening + data setup.
- Day 8–15: Frontend + internal order flow.
- Day 16–22: Soft launch in one locality.
- Day 23–30: Optimize retention and unit economics.

### 9) Post-MVP upgrades
- Online payments (Razorpay/Stripe).
- Slot-based delivery windows.
- Personalized recommendations.
- Multi-warehouse inventory and routing.

---

If you want, the next step is turning this plan into a task board (issues + milestones) directly in this repo.
