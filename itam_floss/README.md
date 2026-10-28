# ITAMFloss for Odoo 19.0

ITAMFloss is an installable Odoo 19.0 application for IT Asset Management (ITAM), including hardware assets, custody assignments, handover PDF forms, maintenance, spare parts & toner inventory, software licenses, and reports.

## Compatibility

- **Odoo 19.0** (Odoo.sh, Enterprise, and Community)
- Native integration with `hr.employee` and `hr.department`
- Bilingual interface: Arabic (RTL) and English (LTR)
- Pre-built frontend assets included (`itam_floss/static/app`) — no Node.js or build step required on Odoo.sh or on-premise servers

## Installation

### Option 1: Odoo.sh (19.0)
1. Add this repository (`Odoo-ITAM`) as a submodule or push the `itam_floss` folder to your Odoo.sh custom addons branch.
2. In Odoo, enable Developer Mode, go to **Apps → Update Apps List**.
3. Search for **ITAMFloss** and click **Activate / Install**.

### Option 2: On-Premise / Custom `addons_path`
1. Download `itam_floss-19.0.1.0.0.zip` from the **Releases** page.
2. Extract the `itam_floss` folder directly into your Odoo `addons_path` directory.
3. Restart the Odoo service, go to **Apps → Update Apps List**, and install **ITAMFloss**.

## License

Odoo Proprietary License v1.0 (OPL-1). Copyright Basheer.
