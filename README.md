# DESIGN.md App References

This repository contains Stitch-compatible `DESIGN.md` references distilled from real app/product surfaces. Each file combines parser-safe YAML design tokens with narrative guidance for coding agents and product/design implementation.

## Files

| File | App | Source |
|---|---|---|
| [`BITGET_WALLET_DESIGN.md`](./BITGET_WALLET_DESIGN.md) | Bitget Wallet | https://web3.bitget.com/en |
| [`PORTRAIT_DESIGN.md`](./PORTRAIT_DESIGN.md) | Portrait | https://portrait.so/ |
| [`MONAI_DESIGN.md`](./MONAI_DESIGN.md) | MonAi | https://get-monai.app/ |

## What Each File Includes

- YAML frontmatter tokens for colors, typography, spacing, radius, and components.
- Product-specific overview and design principles.
- Component guidance for buttons, cards, inputs, navigation, app surfaces, and signature product patterns.
- Responsive behavior, touch targets, iteration rules, and known gaps.
- Notes about inferred tokens when exact native app values are not publicly exported.

## Validation

Run the official design.md linter:

```bash
npm exec --yes --package @google/design.md -- design.md lint BITGET_WALLET_DESIGN.md
npm exec --yes --package @google/design.md -- design.md lint PORTRAIT_DESIGN.md
npm exec --yes --package @google/design.md -- design.md lint MONAI_DESIGN.md
```

The linter may report orphan-token warnings because these files intentionally include broader brand palettes than the compact component token set references directly.

## Notes

These are reference design-system documents, not official brand guidelines from the companies. They were created from publicly available product pages, app-store surfaces, screenshots, and extracted CSS tokens.
