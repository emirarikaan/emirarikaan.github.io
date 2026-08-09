# Privacy Policy — Mrs. Gadget: Face Search AI

_Last updated: August 9, 2026_

Mrs. Gadget: Face Search AI is a face-focused, public-web visual search utility for adults (18+).

## 1. How a search handles your photo
- Face detection/cropping happens on device; metadata (EXIF, location) is stripped before upload.
- The prepared face crop goes encrypted to our backend (Google Cloud, EU region), which holds it in memory only for the provider call — it is never written to our storage.
- The crop is forwarded to the search provider (currently SerpApi / Google Lens) to run the search; provider retention is governed by their policies (https://serpapi.com/legal).
- Result links are kept as short-lived server job records that auto-expire within about one hour.
- Search history (including a small face thumbnail) lives only on your device and can be deleted in Settings.

## 2. What we store
An anonymous account ID (Firebase Auth), your credit balance and purchase ledger, short-lived search job metadata, crash/diagnostic data (Firebase), and anti-abuse rate-limit counters. We do **not** permanently store searched photos and we do **not** retain biometric templates or face-recognition profiles.

## 3. What we do not do
No advertising or marketing profiles from face data, no data sales, no dossier building, no unrelated model training.

## 4. Purchases
Apple processes payments; RevenueCat manages entitlements; Firebase keeps the credit ledger. These services never receive your photos.

## 5. Age policy
18+. We do not knowingly process minors' data; uploading photos of minors is prohibited.

## 6. Deletion
Clear local history in Settings; request account/server data deletion from Settings or by email. Some transaction records may be retained where legally required.

## 7. Contact
eacompany947@gmail.com
