# Sushanth Roy Portfolio

A self-contained, responsive portfolio page. Open `index.html` in a browser to view it. It uses Geist from Google Fonts and Lenis from jsDelivr for the reference-style smooth scrolling; if Lenis cannot load, the page falls back to browser scrolling.

## Add your work

The four project cards in `index.html` use a split preview-and-details layout on desktop and stack on narrow screens. Project 01 uses `media/model-shoot-cover.png` as the Bharatanatyam reel cover; Projects 02–04 use the supplied Creative Portrait, College Cultural Fest, and Candid Portrait photos. The Creative Portrait uses `media/creative-portrait-cover.png`, centered and shown uncropped. Project 03 uses `media/college-visual-story-cover.png` as its college fest cover. Services pairs Cinematography, Video Editing, and Photography with their own images; hovering, focusing, or tapping a service changes the preview. About places the biography, toolkit, and a short visual-approach list side by side on wide screens and stacks them on mobile. Its copy reveals sentence by sentence as visitors scroll. The dark sections use a fine animated white-grain texture that shifts subtly with the pointer, while the warm hero background slowly drifts and responds to pointer movement. The large footer wordmark starts with its two name parts apart, then centers and joins them as visitors scroll into the footer.

- For a video, put the file in a `media` folder next to `index.html`, then add its relative path to that card's `data-video` attribute. Example: `data-video="media/portrait-film.mp4"`. A muted loop starts when the cursor enters a frame without an image gallery; clicking the frame opens the larger video preview.
- Projects 01–04 cycle through their additional stills on hover and return to their covers when the pointer leaves. Project 01's reel opens when its frame is clicked; Project 02 has five gallery stills, Project 03 has four, and Project 04 has two.
- For a hosted video, use a direct MP4 URL in `data-video`. A Google Drive clip can also set `data-video-embed` to its `/file/d/FILE_ID/preview` URL so the larger dialog uses Drive's player.
- For a project photo, add or update an image element with the `project-cover` class inside the card's `.project-frame` button. Keep the file in the local `media` folder and use a relative path. Use `project-cover--contain` when the full image must remain visible without cropping.
- Update each card's title, discipline, label, and alt text to match the actual project before publishing.

## Add contact and social links

The footer links to Sushanth's Instagram, LinkedIn, and Facebook profiles and opens an email to `sushanthroy.bavana@gmail.com`. The footer includes the reference-style Privacy label; add a privacy policy destination when its URL is available.

## Customize

All styling and interactions are inside `index.html`: the opening reveals, smoothly cursor-responsive moving hero atmosphere, staggered letter-roll navigation and contact-button hovers, high-contrast header as the oversized name passes beneath it, scroll-split transition into a grain-textured second section whose background shifts with the headline sequence, smooth scrolling, project-frame parallax, scroll reveals, interactive Services preview, an About text reveal, accessible FAQ accordion, and hover and dialog video previews. The headline keeps its scroll reveal without cursor lighting or a dot background. The location line uses Geist Mono to match the reference site's compact uppercase caption. The page respects the visitor's reduced-motion preference and adapts to mobile screens.
