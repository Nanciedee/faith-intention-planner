# Design Specifications

## Color System

### Primary Colors
```css
--pastel-blue: #BFD8EB;
--pastel-lilac: #D9C1EB;
--blush: #F6D1D1;
--cream: #FFF5E1;
```

### Usage Guidelines
- **Blue**: January pages, calm reflection sections
- **Lilac**: February pages, spiritual focus areas
- **Blush**: March pages, emotional wellness sections
- **Cream**: Base backgrounds, neutral spaces

## Typography Scale

| Element | Font | Weight | Size |
|---------|------|--------|------|
| Cover Title | Georgia | Bold | 36pt |
| Page Headers | Georgia | Bold | 22-24pt |
| Section Headers | Georgia | Bold | 18-20pt |
| Body Text | Lato | Regular | 16pt |
| Labels | Lato | Semi-bold | 14pt |

## Layout Grid

### Page Dimensions
- Width: 8.5 inches
- Height: 11 inches
- Orientation: Portrait

### Margins
- Top: 0.75 inches
- Bottom: 0.75 inches
- Left: 0.5 inches
- Right: 0.5 inches

### Safe Print Area
- Inner margins ensure no important content is lost in binding or cutting
- All text stays 0.5" from edges minimum

## Decorative Elements

### Watercolor Effects
- Created using CSS gradients with blur
- Opacity: 15-30% for backgrounds
- Placed in corners or behind headers

### Motifs
- **Leaf 🌿**: Bottom right or left corners
- **Moon 🌙**: Top right corners or near headers
- **Sparkles ✨**: Cover page only

### Borders & Lines
- Writing lines: 1-2px solid #d1d5db
- Section dividers: 1px solid with 20% opacity
- Rounded corners: 8-12px radius on boxes

## Component Specifications

### Monthly Focus Tracker
- 5 focus areas per month
- 3 writing lines per area
- Checkbox on left (20px square)
- Pastel background matching month

### Weekly Rituals
- 7 days per page
- 4 tracking areas per day
- Alternating row backgrounds
- Compact spacing for full week view

### Daily Tracker
- 4 main tracking items
- Large writing space per item
- Notes section at bottom
- Clean, minimal design

### Emotional Success
- 3 main sections: Gratitude, Affirmations, Mood
- 5 lines per section
- Checkbox tracking
- Colorful section backgrounds

## Print Guidelines

### File Format
- Export as high-resolution PDF (300 DPI)
- Embed all fonts
- Convert colors to CMYK for printing

### Bleed
- Add 0.125" bleed on all sides if printing professionally
- Extend backgrounds to bleed edge

### Paper Recommendations
- Weight: 80-100 lb text weight
- Finish: Matte or uncoated for writing
- Color: Bright white for best color rendering
