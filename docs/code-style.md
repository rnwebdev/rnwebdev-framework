# Code Style (PHP/JS/CSS)

- PHP 8.3, WPCS (WordPress Coding Standards)
- Prefixes: `tvm_` (Tourism) / `hcvg_` (Sports)
- Hooks over hardcoding; esc_html__, wp_nonce_field, capabilities
- DB: `$wpdb->prepare()` only; no inline SQL
- JS: modules where possible; no global leaks
- CSS: utility-first; BEM for custom blocks
