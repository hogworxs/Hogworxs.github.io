# Range Command — launch website and licensing specification (draft)

Status: planning only. Do not enable checkout, claim a release is available, or collect waitlist email addresses until approved services are configured.

## Public product positioning
Range Command is HOG WORX's advanced desktop field workstation, designed to work independently or alongside Range Forged. Windows and Linux releases are planned together. Planned v1 capabilities: online/offline mapping (subject to provider terms), GPS, supported Meshtastic communication, chronograph CSV import, equipment and session records, and optional manual synchronization.

## Proposed license terms
- $49.99 initial purchase, perpetual access to purchased software version and 12 months of feature updates.
- One license permits activation on up to two computers (e.g. home and portable range machine), on Windows and/or Linux.
- $10 optional, **manual** annual feature-update renewal; no automatic charges.
- No expiration of already purchased software or its included functionality if the user does not renew.
- Security, bug, and stability maintenance updates continue independently of annual feature releases.
- Key delivered by email after payment confirmation; activation service and signed offline-verifiable license token required. Provide recovery and device-deactivation options.
- Avoid promising impossible anti-piracy protection. Never embed signing private keys in client software.

## Manual sync & backups — product requirement
- **Never auto-sync on network connection.** Sync occurs only when user presses **Sync Now** and confirms a change preview.
- Paired computers discover one another over local Wi-Fi/LAN, authenticate and encrypt transfers; no cloud or internet required.
- Compare changes in rifle profiles, ammunition records, shooting sessions, chronograph data, and waypoints. Explicit conflict handling, no silent overwrite.
- Show last successful sync timestamp and status. Support optional USB export/import.
- Sync is not backup: maintain independent versioned backups with restoration, including protection against accidental deletions.
- Range Forged interoperability uses a shared, versioned data schema and optional import/sync; each product functions independently.
- Offline map packs can be transferred as a separate user-controlled operation, subject to map data licenses and storage limits.
- Manual sync and backups are core purchased features, not tied to update renewal.

## Website implementation sequence
1. Expand Range Command section with accurate 'planned/in development' features, platform targets, and proposed pricing.
2. Add privacy-conscious waitlist through a verified third-party form/backend (GitHub Pages is static); do not create fake signups.
3. Build secure payments, licensing backend, and email fulfillment before offering paid downloads. GitHub Pages alone cannot securely issue keys.
4. Provide signed Windows and Linux installers and license retrieval once releases are tested and approved.
5. Review copy and functionality before merging to live website.

Owner approval required before publishing new commercial claims, enabling payment collection, or changing customer-facing legal terms.
