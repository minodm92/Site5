# Design Tokens

Source: Figma `작업_공유 Copy` / node `4029:165` (`style`)

## Color

| Token | Value | Usage |
| --- | --- | --- |
| `color.primary.mint08` | `#167673` | Primary brand color, active tag |
| `color.primary` | `#167673` | Primary swatch |
| `color.natural` | `#D4F7F6` | Natural swatch, grid column fill |
| `color.secondary.coralDark` | `#FE6565` | Section labels and token captions |
| `color.grayscale.gray07` | `#5E6167` | Neutral tag background |
| `color.basic.black` | `#000000` | Main title |
| `color.text.default` | `#191919` | Body text |
| `color.white` | `#FFFFFF` | Page background, tag text |
| `color.divider` | `#D9D9D9` | Divider line |
| `color.border.default` | `#D6D8DC` | Grid preview border |

## Typography

Default font family: `Pretendard`

| Token | Font | Weight | Size | Line height | Letter spacing |
| --- | --- | --- | --- | --- | --- |
| `font.headline` | `Pretendard` | `700` | `20px` | `28px` | `0` |
| `font.title` | `Pretendard` | `700` | `16px` | `22px` | `0` |
| `font.body1` | `Pretendard` | `700` | `14px` | `20px` | `0` |
| `font.body2` | `Pretendard` | `500` | `14px` | `20px` | `0` |
| `font.body3` | `Pretendard` | `700` | `12px` | `16px` | `0` |
| `font.body4` | `Pretendard` | `500` | `12px` | `16px` | `0` |

## Effect

| Token | Value |
| --- | --- |
| `effect.elevation` | `0 4px 20px 0 rgba(0, 0, 0, 0.2)` |

## Radius

| Token | Value | Usage |
| --- | --- | --- |
| `radius.card` | `12px` | Color swatches, elevation sample |
| `radius.pill` | `100px` | Tags |

## Spacing

| Token | Value | Usage |
| --- | --- | --- |
| `space.tag-x.sm` | `18px` | Small tag horizontal padding |
| `space.tag-y.sm` | `16px` | Small tag vertical padding |
| `space.tag-x.lg` | `24px` | Main tag horizontal padding |
| `space.tag-y.lg` | `11px` | Main tag vertical padding |
| `space.title-gap` | `16px` | Title area vertical gap |
| `space.page-x` | `80px` | Main content left/right inset in style frame |

## Grid

| Token | Value | Note |
| --- | --- | --- |
| `grid.mobile.width` | `360px` | Mobile preview frame width |
| `grid.mobile.height` | `740px` | Mobile preview frame height |
| `grid.mobile.columns` | 확인 필요 | Figma context exposes the grid as an image asset, not numeric layout-grid values |
| `grid.mobile.gutter` | 확인 필요 | Confirm in Figma layout grid settings before CSS implementation |
| `grid.mobile.margin` | 확인 필요 | Confirm in Figma layout grid settings before CSS implementation |

## CSS Variables

```css
:root {
    --color-primary-mint08: #167673;
    --color-primary: #167673;
    --color-natural: #d4f7f6;
    --color-secondary-coral-dark: #fe6565;
    --color-grayscale-gray07: #5e6167;
    --color-basic-black: #000000;
    --color-text-default: #191919;
    --color-white: #ffffff;
    --color-divider: #d9d9d9;
    --color-border-default: #d6d8dc;

    --font-family-base: "Pretendard", sans-serif;

    --font-headline-size: 20px;
    --font-headline-line-height: 28px;
    --font-headline-weight: 700;

    --font-title-size: 16px;
    --font-title-line-height: 22px;
    --font-title-weight: 700;

    --font-body1-size: 14px;
    --font-body1-line-height: 20px;
    --font-body1-weight: 700;

    --font-body2-size: 14px;
    --font-body2-line-height: 20px;
    --font-body2-weight: 500;

    --font-body3-size: 12px;
    --font-body3-line-height: 16px;
    --font-body3-weight: 700;

    --font-body4-size: 12px;
    --font-body4-line-height: 16px;
    --font-body4-weight: 500;

    --effect-elevation: 0 4px 20px 0 rgba(0, 0, 0, 0.2);

    --radius-card: 12px;
    --radius-pill: 100px;

    --space-tag-x-sm: 18px;
    --space-tag-y-sm: 16px;
    --space-tag-x-lg: 24px;
    --space-tag-y-lg: 11px;
    --space-title-gap: 16px;
    --space-page-x: 80px;
}
```
