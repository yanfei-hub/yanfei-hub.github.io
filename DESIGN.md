# DESIGN.md

## 1. Visual Theme and Atmosphere

This website should feel like an academic editorial site rather than a personal blog template or a software landing page.

Core mood:
- calm
- rigorous
- modern
- high-credibility
- highly readable
- visually structured, but not flashy

The site should communicate:
- methodological seriousness
- clarity of thought
- selective emphasis
- editorial confidence
- research identity

The site should not feel:
- cluttered
- corporate
- overly decorative
- startup-marketing heavy
- dense like a CV dump
- visually noisy

Design direction:
- academic minimalism with light editorial influence
- closer to Notion plus a restrained WIRED-style hierarchy
- strong spacing rhythm
- sparse but intentional accent color
- clear content blocks
- featured work should stand out without looking like ads

## 2. Color Palette and Roles

### Base palette

Background:
- Canvas: #FAFAF7
- Surface: #FFFFFF
- Muted surface: #F3F4F1

Text:
- Primary text: #151515
- Secondary text: #4B5563
- Tertiary text: #6B7280

Accent:
- Primary accent: #1F4E79
- Soft accent: #DCE8F3
- Link hover accent: #163A5A

Borders:
- Light border: #E5E7EB
- Strong border: #D1D5DB

Optional research accent colors for small tags only:
- Target trial emulation: #1F4E79
- Longitudinal modeling: #5B6C5D
- Real-world evidence: #7A4E2D

### Usage rules

- Use mostly neutral backgrounds.
- Accent color should be used sparingly for links, small labels, and section emphasis.
- Do not use large saturated color blocks.
- Do not use gradients.
- Do not use more than one strong accent on the same screen.
- Keep the overall experience light, quiet, and readable.

## 3. Typography Rules

### General typography

The site should feel highly readable and editorial.

Preferred font direction:
- Sans-serif primary
- Clean, neutral, academic
- No futuristic or playful fonts

Recommended stack:
- ui-sans-serif
- system-ui
- -apple-system
- BlinkMacSystemFont
- "Segoe UI"
- sans-serif

### Hierarchy

H1:
- large, calm, confident
- not oversized
- strong weight
- generous top and bottom spacing

H2:
- clear section divider
- slightly darker or heavier than body
- strong spacing above

H3:
- used for project cards, featured publications, and subsections
- compact but distinct

Body:
- medium size
- comfortable line height
- optimized for long-form reading

Metadata:
- smaller
- muted color
- never compete with titles

Links:
- use accent color
- underlines only on hover or where needed for clarity

### Typography behavior

- Paragraphs should be short.
- Avoid walls of text.
- Break content into scannable units.
- Use bold sparingly and strategically.
- Avoid too many italicized lines.
- Keep reading width narrow enough for sustained attention.

## 4. Content Structure Principles

This site should prioritize scanning before deep reading.

Each page should have:
- one clear page purpose
- one featured block near the top
- limited repeated framing text
- strong visual separation between sections

### Page roles

Home:
- establish research identity quickly
- show 3 major themes
- highlight one featured paper or project
- offer clear paths into Research, Publications, Insights, and Software

Research:
- structured around a few representative projects
- each project should feel like a card or module
- image first, then 1 sentence summary, then 3 to 4 bullets, then links

Publications:
- selected and curated
- not a full CV wall
- show featured publications first
- each featured item should include title, venue, short significance line, and links

Insights:
- should feel like an ideas and notes hub
- emphasize active thinking, not static description
- show featured notes, selected talks, and methodological reflections

Software:
- should feel like proof of implementation
- compact, card-based, with direct links to code and paper

CV:
- simple and utility-focused
- direct PDF access
- no visual clutter

## 5. Layout Principles

### Overall layout

- wide but not too wide
- generous whitespace
- content should breathe
- avoid stacking too many text-heavy sections back to back

### Spacing rhythm

- large space between major sections
- moderate space between subsection title and content
- small consistent space within cards or lists

### Recommended page rhythm

Use this sequence often:
1. short intro
2. featured block or image
3. 2 to 4 structured content modules
4. concise navigation or next-step links

### Width behavior

- body text should not span too wide
- featured images should be medium to large
- cards should have enough internal padding to feel intentional

## 6. Component Styling

### Navigation

Top navigation should be minimal.

Use only core internal pages:
- Research
- Publications
- Insights
- Software
- CV

Do not place external links like GitHub or Google Scholar in the main navigation.
Those belong in the sidebar, footer, or home page link cluster.

Navigation should feel quiet, precise, and easy to scan.

### Buttons and calls to action

Buttons should be used sparingly.

Preferred style:
- soft border
- white or muted surface
- dark text
- subtle hover state

Primary CTA:
- small accent background or border
- only one per screen

Avoid:
- oversized buttons
- bright marketing-style buttons
- too many CTAs in one section

### Cards

Cards are essential for this site.

Use cards for:
- research themes
- featured publications
- software projects
- insights categories

Card style:
- white surface
- subtle border
- slight corner radius
- no heavy shadows
- comfortable padding
- optional small label at top

Cards should feel editorial and structured, not product-dashboard style.

### Publication items

Each featured publication should contain:
- title
- authors
- venue and year
- 1 sentence on why it matters
- compact links: DOI, PDF, Code

Avoid long numbered lists at the top of the page.

### Research project modules

Each project module should contain:
- image
- one-line summary
- 3 to 4 bullets
- paper link
- code link if available

Do not place long paragraphs directly under every image.

### Images

Images should be:
- simple
- diagrammatic
- clean
- high contrast
- label-driven
- consistent in style

Preferred image types:
- conceptual flow diagrams
- pipeline illustrations
- 2 or 3 color schematic figures
- simplified decision flow visuals

Avoid:
- busy screenshots
- low-resolution figures
- overly detailed academic panels
- decorative stock photos

## 7. Depth and Elevation

Use very restrained depth.

- Minimal shadow or none
- Let spacing, borders, and hierarchy carry the design
- Surfaces should feel layered through spacing, not effects

This is an academic site, not a SaaS dashboard.

## 8. Page-specific Design Notes

### Home page

The home page should answer:
- who is this researcher
- what is the core problem space
- what are the major themes
- where should I go next

Structure:
- short introduction
- 3 theme cards
- featured project or publication
- concise exploration links

Avoid:
- too much repeated explanation
- long bullet inventories
- excessive self-description

### Research page

Should feel like a visual research portfolio.

Preferred structure:
- short framing paragraph
- 3 featured project sections
- each project anchored by image
- short summary plus bullets
- direct paper and code links

### Publications page

Lead with 4 to 6 featured publications.
Then a shorter secondary list.
Then link out to Google Scholar for the full list.

### Insights page

Should feel alive.
Avoid using the page only to explain what Insights means.
Show pathways into writing and talks immediately.

### Software page

Should feel concrete and proof-based.
One strong software card is better than several weak text blocks.

## 9. Do and Do Not

### Do

- prioritize readability
- reduce repeated language across pages
- create strong visual hierarchy
- use cards and images to break up long reading
- make featured work easy to identify
- make the site feel curated rather than exhaustive

### Do not

- repeat the same research summary on every page
- rely on long paragraphs as the default layout
- crowd the top navigation
- use too many external links in high-attention locations
- overload pages with every publication and every idea at once
- use decorative visuals that do not support the content

## 10. Brand Voice in Visual Form

This site should visually communicate:
- careful thinking
- methodological depth
- clarity under complexity
- seriousness without stiffness
- openness to evolving ideas

The design should suggest:
"This researcher builds rigorous methods for complex longitudinal clinical data, and explains them clearly."

## 11. First Implementation Priorities

When applying this design system, prioritize these changes first:

1. Simplify the home page and reduce repeated text
2. Convert Research into image-led project modules
3. Turn Publications into a curated featured-publication page
4. Make Insights a real entry point, not a definition page
5. Remove external links from the top navigation
6. Add 3 simple, consistent research diagrams
