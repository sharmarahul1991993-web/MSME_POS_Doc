# MSME POS PRO

A highly responsive, offline-first Desktop ERP system for Indian retail shops. Built with Rust and Slint framework, this application provides comprehensive inventory management, billing, customer ledger, and financial reporting.

## 🚀 Key Features (May 2026 Update)

### 📊 Tax & Compliance
- **GSTR-1 JSON Export**: Generate official JSON files for direct upload to the GST portal.
- **Smart GST Engine**: Automatic classification of B2B/B2C and Intra/Interstate (CGST/SGST/IGST) tax logic.
- **HSN Summary**: Table 12 compliant reporting bifurcated by registration type.

### 🛡️ Security & Risk Management
- **Hardware-Locked Licensing (New)**: Software bound to a unique Machine ID (HWID) to prevent unauthorized transfers.
- **Role-Based Access (RBAC)**: Strict isolation of Settings, Inventory, and User management for Admin roles.
- **Credit Limit Enforcement**: Real-time blocking of "Udhaar" (Credit) sales that exceed customer limits.
- **Shift Reconciliation**: 'Blind close' audit process to detect cash leakage at point-of-sale.

### 💰 Payments & CRM
- **Dynamic UPI QR**: Real-time QR generation with pre-filled Bill Amount and Shop Name.
- **Loyalty Points Engine**: Automated rewards based on purchase value with 1-click redemption.
- **WhatsApp Recovery**: Automated debt recovery messages with UPI deep-links for instant payment.

### 📦 Inventory & Operations
- **Stability Tested**: Optimized for 2000+ items with server-side search and lazy loading.
- **FIFO Batch Tracking**: Expiry-based stock depletion logic.
- **Mobile Scanner Feedback**: Audio 'Beep' and Haptic vibration on successful scans.

## 🛠️ Development Setup

1. **Prerequisites**: Rust (1.75+), MinGW-w64 (Windows).
2. **Environment**: Use `$env:SANDBOX=1` for development to protect live data.
3. **Build**: `cargo run --release`

## 🔮 Future Roadmap
- **Track 1**: E-Invoicing API integration (Government IRN/QR).
- **Track 2**: Thermal Printer (ESC/POS) direct byte-stream integration.
- **Track 3**: Cloud Backup & Mobile Owner Dashboard for remote monitoring.

---
**Version**: 1.3.2  
**Last Major Update**: May 16, 2026 (Stable Release)  
**Repository**: https://github.com/sharmarahul1991993-web/MSME.git
