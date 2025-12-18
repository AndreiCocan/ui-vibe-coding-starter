## AI Design Style Reference
Use this reference to mix and match options when writing your design brief. Copy the terms that match your vision.

## Visual Style
| Category	| Options
| -------- | ------- |
|Modern/Clean |	Minimalist, Flat design, Material Design, Swiss/International style, Scandinavian
|Depth & Texture |	Glassmorphism, Neumorphism (soft UI), Skeuomorphic, Claymorphism, Frosted glass
|Bold & Experimental |	Neobrutalism, Brutalist, Cyberpunk, Vaporwave, Retro/Y2K, Memphis design
|Elegant |	Editorial, Magazine-style, Luxury, Art deco, Sophisticated
|Playful |	Illustrated, Cartoon-style, Rounded/Bubbly, Colorful, Whimsical
|Data-focused |	Dashboard-oriented, Analytics-first, Information-dense, Terminal/CLI aesthetic
|Layout patterns |	Bento box grid, Card-based, Asymmetric, Split-screen, Full-bleed
|Typography-first	| Big type, Kinetic typography, High-contrast type, Wide tracking, Clean sans + serif pairing
|Branding vibe | Startup SaaS, Enterprise/corporate, Boutique studio, Premium product-led, Developer-first
|Illustration styles |	Line illustrations, Duotone illustrations, Isometric, Hand-drawn, Gradient illustration
|3D & iconography |	3D icons, 3D clay, Soft 3D, Emoji-like icons, Outline-only icon set, Filled icon set
|Vintage & analog |	Retro UI, Film grain, Paper texture, Halftone, CRT/scanlines, VHS
|Nature & organic |	Earthy/organic, Soft gradients, Pastel, Warm neutrals, Botanical, Calm wellness
|Luxury & fintech |	Premium fintech, Institutional, Black + gold, Subtle shine, Minimal borders, Soft shadows

Example usage:
```
Style: Glassmorphism, modern, soft shadows, frosted glass effects, rounded corners
```

## Layout Structures
| Layout |	Best For |	Description
| -------- | ------- | ------- |
|Sidebar + Content |	Dashboards, admin panels |	Fixed left nav, main content area
|Top nav + Content |	Marketing, simple apps	| Horizontal nav, vertical content
|Sidebar + Top bar + Content |	Complex dashboards	|Both navigation types
|Three-column	| Email clients, feeds	|Nav + content + detail panel
|Split screen	| Comparison, editors	| Two equal or weighted halves
|Bento grid |	Modern dashboards	| Mixed-size card grid (Japanese style)
|Single column |	Mobile-first, articles	| Centered, flowing content
|Full-width cards |	Data-heavy apps	| Edge-to-edge content blocks
|Masonry |	Galleries, Pinterest-style |	Varied height cards
|Kanban |	Project management	| Draggable columns
|Master-detail	| CRMs, inboxes, admin tools	| List on the left + detail panel on the right
|Two-pane split |	Editors, diff tools	| Resizable panes for side-by-side comparison
|Tabs + content	| Settings, dashboards	| Switch between sections without route changes
|Filters + results |	Marketplaces, search |	Filter sidebar + grid/list results with sorting
|Wizard / stepper	| Onboarding, checkout	| Multi-step flow with a progress indicator
|Docs layout (TOC + content) |	Documentation, guides |	Sticky table of contents + reading pane
|Chat layout	| Support, assistants |	Sidebar threads + main chat + optional info panel
|Calendar layout |	Scheduling, bookings |	Month/week views + details drawer/panel
|Table-first |	Back-office, analytics	| Dense tables with sticky headers and row actions
|Timeline / activity feed	| Audits, ops, social |	Chronological feed with grouped events
|Map + list |	Real estate, delivery	| Map view paired with a scrollable results list

Example usage:
```
Layout: 3-column layout with collapsible left sidebar, top navigation bar, main content area with card grid
```

## Color Themes
|Theme	|Description	|Example Colors
| -------- | ------- | ------- |
Dark + Gold |	Luxury fintech, premium feel	|#0B0D10 background, #F5A623 accent
Dark + Green | Crypto, trading, growth	|#0F1419 background, #22C55E accent
Dark + Blue |	Tech, trust, security |	#111827 background, #3B82F6 accent
Dark + Purple |	Creative, Web3, modern	|#0D0D12 background, #8B5CF6 accent
Dark + Cyan	| Futuristic, neon, tech	|#0A0A0B background, #06B6D4 accent
Dark + Orange	| Energy, action, urgency	|#18181B background, #F97316 accent
Dark + Red	| Bold, alerts, gaming	|#1C1917 background, #EF4444 accent
Light + Blue |	Corporate, professional	|#FFFFFF background, #2563EB accent
Light + Green	|Health, eco, organic	|#F9FAFB background, #16A34A accent
Light + Purple	|Creative, modern SaaS	|#FAFAFA background, #7C3AED accent
Light + Warm	|Friendly, approachable	|#FFFBEB background, #D97706 accent
Monochromatic	|Grayscale + single accent	|Black/white/gray + one pop color
Gradient-based	|Modern, dynamic	|Purple→Blue, Orange→Pink, Teal→Green
Earth tones	|Natural, organic, calm |	Browns, tans, olive, terracotta
Pastel	|Soft, gentle, playful	|Muted versions of any palette
Neon/Vibrant	|Bold, energetic, gaming	|Bright saturated colors on dark

Example usage:
```
Colors: Dark mode, charcoal background (#0B0D10), gold/orange accent (#F5A623), white primary text, muted gray secondary
```

## Putting It Together
Here's a complete example combining all elements:
```
Style: Glassmorphism, modern, soft shadows, premium fintech aesthetic
Colors: Dark mode, near-black background (#0B0D10), gold accent (#F5A623), white/gray text hierarchy
Layout: Left sidebar + top bar + main content with bento grid
Components:
  - User greeting card with avatar and account info
  - Total balance card with large numbers and quick actions
  - Portfolio chart (line chart with area fill)
  - Holdings table with sparklines and 24h change
  - VIP status card with progress bar
  - Recent activity feed
  - Promotional banner for referral program
```
