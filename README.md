# Santa & Friends

A lightweight storefront for 3D-printed Christmas coasters and the Santa Belly cookie bowl. Customers choose quantities and place the order through a pre-filled WhatsApp message.

There's no build step: it's a single `index.html` plus the `img/` folder.

## Edit before going live
At the top of the `<script>` in `index.html`:
- `WHATSAPP_NUMBER`: country code + number, digits only (e.g. `919876543210`)
- `PRODUCTS`: names, prices, descriptions, tags
