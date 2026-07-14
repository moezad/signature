# Shopify theme files — ispiceyou.com

Files deployed to the Shopify theme copy **"iSpiceYou Production + Family of Brands section"**
(`gid://shopify/OnlineStoreTheme/144365944883`), duplicated from the live theme on 2026-07-14.

Preview: https://www.ispiceyou.com/?preview_theme_id=144365944883

## What's here

- `sections/index__logo-list.liquid` — the homepage "More From Our Network" logo list,
  rebuilt as a "One Family, Three Ways to Buy" card section. Renders three cards:
  iSpice You (retail, "You Are Here"), iSpice Foods (wholesale/private label), and
  iSpice Pros (food service). Keeps the legacy schema so the existing homepage template
  data and theme editor keep working. Section settings (texts, accent color, background,
  show/hide the iSpice You card) are editable in the theme customizer under
  "Our Network (Brand Cards)".
- `sections/family-of-brands.liquid` — standalone version of the same design as a new
  section type, available in the theme editor's "Add section" list. Not referenced by
  any template yet.

## Going live

Publishing must be done in Shopify Admin → Online Store → Themes → publish the
"iSpiceYou Production + Family of Brands section" theme. Alternatively, paste
`sections/index__logo-list.liquid` over the same file in the live theme via
Edit code — that applies the change without a theme swap.

## Rollback

Restore `sections/index__logo-list.liquid` from the live theme
(`gid://shopify/OnlineStoreTheme/124360392755`), which still has the original file.
