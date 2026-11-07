# MK Laundry PWA — first working version

This mobile-friendly prototype includes the TZS price catalogue, quantity selector, estimated bill, customer details, service choice, pickup/delivery, preferred date, payment preference and special instructions. It creates a pre-filled WhatsApp request to +255755177435.

## Test and publish
1. Upload `index.html`, `manifest.webmanifest`, and `sw.js` to a GitHub repository.
2. Enable GitHub Pages in Settings > Pages > deploy from branch > main / root.
3. Open the resulting HTTPS link on a phone.
4. Android Chrome: menu > Install app / Add to Home screen. iPhone Safari: Share > Add to Home Screen.

## Important limitations
This is a first front-end version, not yet a full real-time multi-user system. Requests are handed off to WhatsApp; there is no shared cloud database, owner login, central order dashboard, automatic status updates, or mobile-money payment processing. The payment field records preference only. Those capabilities require a secure backend and payment-provider setup before public launch.
