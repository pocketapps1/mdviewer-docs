# MDViewer FAQ

## Does the App collect any data?
No. MDViewer does not collect, store, or share personal data. See the [Privacy Policy](./privacy-policy.md).

## Why can’t I see subscriptions in Settings?
Only auto‑renewable subscriptions appear under Apple ID → Subscriptions. One‑time lifetime purchases do **not** appear there; restore them via **Restore Purchases** in the App.

## Why can’t I set MDViewer as the default app for `.md`?
iOS does not allow third‑party apps to force “always open with.” Use WeChat/Files “Open in…” to select MDViewer.

## Where are exported files?
- **PNG**: Saved to Photos (if permission granted).  
- **PDF**: Shared through the iOS share sheet (save to Files, send to apps, etc.).

## My PNG only shows part of the document
MDViewer exports the **full** document when generating PNG from HTML. For very long content, allow a moment for rendering.

## PDF is missing pages
MDViewer uses a print renderer with automatic pagination. If you still see missing pages, try re‑exporting after content finishes rendering on the Preview tab.

## I denied Photos permission. How do I enable it?
Go to **Settings → Privacy → Photos → MDViewer** and allow access. Without permission, PNG cannot be saved to Photos.

## TestFlight vs Sandbox
- **TestFlight** uses your real Apple ID to install builds (no charge).  
- **Purchases** should be tested with a **Sandbox tester** account (Set under Settings → App Store → Sandbox Account). This avoids real charges.

