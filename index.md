# ClearScan Privacy Policy

**Last updated: October 9, 2026**

ClearScan is designed to process and store your documents locally on your device. The app requires no user account and performs no background cloud synchronization. This policy explains how your documents, OCR text, local preferences, optional merchant learning, and license information are handled.

## Document Storage & Export

Scanned page images, generated PDFs, OCR text, and metadata are saved in ClearScan's private app sandbox directory.

When a document is finalized or renamed, a public copy is exported to your device's `Documents/ClearScan` folder for file manager access.

Deleting a document inside ClearScan removes its private internal files and requests removal of its public `Documents/ClearScan` MediaStore entry. Copies you previously moved, renamed, or shared outside ClearScan remain beyond the app's control and must be managed manually.

## On-Device OCR & Document Naming

Text recognition is processed locally on your device using Google ML Kit libraries included in the app.

Extracted text is saved in private files inside each document's sandbox folder and is used for library search, automatic title suggestions, and address detection.

ClearScan does not transmit your document images or extracted text to external servers.

## Optional Merchant Learning

When renaming a document, checking **"Remember merchant name for future documents"** is optional and disabled by default.

When enabled, custom merchant titles and associated OCR keywords are saved locally on your device to improve future naming suggestions. This data remains on your device and is not used to train external models.

All learned merchant data can be removed by clearing app data or uninstalling ClearScan.

## Data Sharing & Transmission

ClearScan requires no account, contains no advertising or analytics SDKs, and performs no automatic cloud synchronization.

Document sharing (via email, messaging, or cloud storage) occurs strictly upon your explicit request through Android's native share sheet. Files sent to external applications are governed by those receiving applications' privacy policies.

## Data Retention & App Removal

Private document files, OCR index data, app preferences, and learned merchant data remain on your device until deleted inside ClearScan or cleared via Android system settings.

Uninstalling ClearScan removes all private app data. Public copies exported to `Documents/ClearScan` or files shared with other applications may remain on your device until manually deleted.

## License Verification & Security

ClearScan Full license keys are verified on-device using local cryptographic signature checks against a built-in public key.

License validation operates offline and makes no external network requests.
