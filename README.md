# 🧭 Tidal Assignment – Shopify Customizations

This assignment includes the implementation of **Quick View Popup** functionality on the Product Listing Page (PLP) and **Variant Color Filtering** on the Product Detail Page (PDP) using Shopify’s **Horizon** theme.

---

## 🚀 Features Implemented

### 1. Quick View Popup on PLP
**Enhancements:**
- Customizable popup elements (Title, Price, Variant Picker, Add to Cart).
- Configurable element order via theme settings.
- Quick View button placement configurable within the product card.
- Fully responsive design across all devices.

**Technical Notes:**
- Added `data-product-element` attributes for sorting elements.
- Used global JS object `quickview_elements_positions` to fetch order values from theme settings.
- Updated Liquid and schema files for button placement configuration.

---

### 2. Variant Color Filtering on PDP
**Enhancements:**
- Filters product images based on the selected color variant.
- Displays only images that match the chosen color.
- Dynamic filtering without page reload.

**Technical Notes:**
- Implemented filtering using image **alt tag** values.
- Reused and extended the product media gallery block for filtering logic.

---


---

## 📄 Documentation

Detailed documentation and client user guide are included in the repository under the `/documents` folder.

- **Project Documentation:** Explains implementation details and technical setup.
- **Client User Guide:** Describes how to manage settings for Quick View and Color Filtering.

---

---

### ✅ Notes
If you face any issues or have feedback, please contact me for clarification or updates.

---
