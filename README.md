A responsive personal portfolio website for Rithikasri Murugavel,
showcasing graphic design, illustration, branding, advertising,
food/menu design, and webtoon-style visual storytelling.

The portfolio is designed as a dark, modern visual experience with
animated effects, interactive project filtering, project lightboxes, a
featured webtoon section, awards, and a contact form.

✨ Features

Responsive portfolio layout for desktop, tablet, and mobile

Sticky navigation with mobile menu

Animated aurora-style background

Cursor-following spotlight effect

Scroll-reveal animations

Animated portfolio statistics

Filterable project gallery

Interactive project lightbox

Featured webtoon section with external Canva link

Awards and achievements section

Contact section with:

Email

Phone

LinkedIn

Client inquiry form

Reduced-motion support using prefers-reduced-motion

SEO-friendly page title and meta description

🎨 Portfolio Categories

The work gallery currently includes:

Illustration

Branding

Ad & Social

Food & Menu

Award-Winning

Featured projects include:

Accessibility for All --- Award-winning poster

The Face Behind the Myth --- Original Krishna illustration and
streaming-poster concept

Krishna Janmashtami --- Original Krishna illustration and
festive social media design

Whale --- Logo Design --- Branding concept

Time to Travel --- Travel promotion poster

Encounter Love --- Café advertisement

Liege Waffle --- Menu poster

Everything Has Beauty --- Typography/illustration poster

Happy Hour --- Café promotion

Delicious Burger --- Food advertising poster

🖌️ Featured Creative Work

Original Illustration

Several portfolio pieces use original character artwork created by
Rithikasri, including the Krishna illustrations featured in:

The Face Behind the Myth

Krishna Janmashtami

These illustrations are combined with typography, colour systems,
composition, and promotional layouts to demonstrate both illustration
and graphic-design skills.

Webtoon

The portfolio includes an original webtoon project titled:

One Second of Distraction, A Lifetime of Regret

The project covers concept development, storyline, character design,
sequential art, and panel illustration.

The full webtoon is published through Canva and is linked directly from
the portfolio.

🛠️ Tech Stack

HTML5 --- Page structure and semantic content

CSS3 --- Layout, responsive design, gradients, animations,
glassmorphism, and visual effects

JavaScript --- Interactions, filtering, lightbox, navigation,
counters, scroll animations, and form validation

Google Fonts

Unbounded

Plus Jakarta Sans

JetBrains Mono

📁 Project Structure

The website expects the HTML file and portfolio assets to be available
in the same project directory.

Example:

portfolio/
├── index.html
├── rithika.png
├── youngindians.jpeg
├── hi.png
├── d.png
├── whale.png
├── travel.png
├── coffee.png
├── waffle.png
├── beauty.png
├── happy.png
└── burger.png

The image filenames above correspond to the assets referenced by the
current HTML.

🚀 Running the Portfolio

No framework or build tool is required.

Option 1 --- Open directly

Open index.html in a modern web browser.

Option 2 --- Use a local server

For a more reliable development environment, run the project through a
local HTTP server.

For example, with Python:

python -m http.server 8000

Then open:

http://localhost:8000

✏️ Customization

Update personal information

Edit the following sections in index.html:

Hero introduction

About section

Education details

Toolkit

Contact information

LinkedIn profile

Footer

Add or edit portfolio projects

Each project is represented by a .g-item element containing:

data-cat --- gallery category

data-accent --- hover accent

data-title --- project title

data-desc --- project description

Image source

Accessibility alt text

Example:

<article class="g-item"
  data-cat="branding"
  data-accent="cyan"
  data-title="Project Name"
  data-desc="Project description.">

  <div class="g-thumb">
    <img src="project.png" alt="Project description">
  </div>

</article>

Add a new category

Add a new filter button:

<button class="filter-btn" data-filter="new-category">
  New Category
</button>

Then assign the same value to a project's data-cat attribute.

📱 Responsive Design

The portfolio includes responsive breakpoints for smaller screens.

The layout adapts by:

Converting multi-column sections into single-column layouts

Switching the desktop navigation to a mobile menu

Adjusting the project gallery

Reorganizing the webtoon section

Adapting the lightbox layout

Scaling typography and spacing

♿ Accessibility Considerations

The website includes:

Descriptive image alt attributes

A labelled mobile navigation button

Keyboard support for closing the project lightbox with Escape

prefers-reduced-motion support

Semantic sectioning and form labels

📬 Contact Form

The contact form performs client-side validation for:

Name

Email

Message

After successful validation, it opens the visitor's default email client
using a mailto: link.

The current destination email is configured in the HTML.

Note: This is a client-side contact form and does not use a backend
server or database.

🏆 Recognition

The portfolio currently highlights:

First Prize --- Web Design Competition

Competition organised by PGP Engineering College

Second Prize --- Poster Making Competition

Organised by Young Indians

₹1,000 cash award

🔗 External Resources

The website uses:

Google Fonts for typography

Canva for the published webtoon

The webtoon link is included directly in the Featured Project section.

📌 Design Direction

The visual identity of the portfolio uses:

Dark background

Violet, cyan, amber, rose, and emerald accent colours

Glass-style panels

Gradient treatments

Monospace labels

Large display typography

Aurora background effects

Subtle grain texture

Motion-based interactions

The design direction is intended to balance a professional
graphic-design portfolio presentation with a distinctive visual
identity.

👤 About the Designer

Rithikasri Murugavel is a graphic designer and final-year Computer
Science student working across:

Graphic design

Branding

Typography

Layout design

Visual storytelling

Illustration

UI/UX

Web design

The portfolio combines commercial design work with original illustration
and sequential storytelling.

📄 License

This portfolio is a personal project. Portfolio artwork, illustrations,
personal branding, and written content belong to Rithikasri Murugavel
unless otherwise stated.

Do not reuse the artwork or personal content without permission.

Designed & built by Rithikasri Murugavel --- 2026
