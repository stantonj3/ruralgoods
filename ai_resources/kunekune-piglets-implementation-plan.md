# Rural Goods Kunekune Piglets GitHub Pages Implementation Plan

## Goal
Build a modern, mobile-friendly static website hosted on GitHub Pages for advertising Rural Goods Kunekune piglets for sale.

---

## Step 1: Decide the hosting model and repository setup

1. Choose whether to use a user/organization site or a project site:
   - User site: repository name must be `username.github.io`.
   - Project site: repository name can be any name, and the URL will be `https://username.github.io/repo-name`.
2. Choose a repository name:
   - If you want a simple main site for your farm, use `username.github.io`.
   - If you want the site as part of a multi-project workspace, use something like `kunekune-piglets`.
3. Decide whether to use a custom domain.
   - Add a `CNAME` file if you choose a custom domain.
   - Plan DNS records with your domain registrar.
4. Create the GitHub repository.
   - Make it public for GitHub Pages hosting.
   - Initialize with a `README.md` if desired.

---

## Step 2: Choose the site implementation approach

### Option A: Simple static HTML/CSS site (recommended)

1. Use plain HTML, CSS, and optionally JavaScript.
2. Create `index.html` as the home page.
3. Create additional pages such as `piglets.html`, `about.html`, `gallery.html`, and `contact.html`.
4. Use the repository root or `/docs` folder as the GitHub Pages publishing source.

### Option B: Jekyll-based site

1. Add `_config.yml` and optionally a `_layouts` folder.
2. Use Markdown pages like `index.md`, `about.md`, `piglets.md`, and `contact.md`.
3. Choose a lightweight Jekyll theme or custom CSS.
4. Keep the site simple to avoid unsupported plugins.

---

## Step 3: Define core pages and content

1. Home page (`index.html` or `index.md`):
   - Hero section with a clear value statement.
   - Short summary of available piglets.
   - Strong call to action: contact, view piglets, or learn more.
2. Available piglets page:
   - Current litters, ages, genders, and availability.
   - Price or pricing note.
   - Health status, vaccination details, and registration.
   - Delivery/pickup options.
3. About page:
   - Farm story, location, and animal care practices.
   - Why Kunekune are a good choice.
   - Experience raising pigs and credibility points.
4. Gallery page:
   - High-quality photos of piglets, sows, boars, and farm life.
   - Optional video or slideshow if available.
5. Contact page:
   - Phone number, email address, and best contact times.
   - External contact form service if desired.
   - Optional map or service area description.
6. FAQ section or page:
   - Typical buyer questions.
   - Piglet pickup/delivery, age at transfer, and supplies needed.

---

## Step 3.1: Rural Goods brand-specific page examples

1. Home page example:
   - Hero headline: “Rural Goods Kunekune piglets raised on pasture.”
   - Subheadline: “Healthy, friendly piglets ready for loving homes.”
   - Call to action: “View available piglets” and “Contact Rural Goods.”
   - Style notes: use `#0f5132` for headings/buttons, black text for body copy, and soft earth-tone backgrounds for section panels.

2. Available piglets page example:
   - Section heading: “Available Kunekune Piglets.”
   - Listing card fields: litter date, number available, gender, price, health details, registration, and pickup/delivery notes.
   - Visual style: card borders in earth-tone shades, callout badges in green, and accent lines in black.

3. About page example:
   - Opening statement: “Rural Goods is a family farm raising Kunekune pigs with care, respect, and sustainable practices.”
   - Paragraphs covering farm story, location, pasture-based care, and why Kunekune are ideal for hobby farms.
   - Design: use a soft earth-tone background with a green accent bar or heading underline.

4. Gallery page example:
   - Highlight hero image or slideshow of piglets.
   - Photo sections labeled “Our breeding stock”, “New litters”, and “Farm life.”
   - Use a subtle black overlay on hover captions and green text highlights.

5. Contact page example:
   - Section heading: “Contact Rural Goods.”
   - Fields: phone, email, best hours, and an optional third-party contact form.
   - Add a small note: “We respond quickly to serious buyers and farm visitors by appointment.”
   - Visual style: use a callout box in `#0f5132` or dark earth tone for contact details.

6. FAQ section example:
   - Questions: “What age are piglets ready to leave the farm?”, “Do you offer delivery?”, “What supplies should I prepare?”
   - Answers written with a supportive tone and practical buying advice.
   - Use black headings with green accent icons or bullets.

---

## Step 4: Gather assets and content

1. Collect photos:
   - Piglets in good lighting.
   - Farm environment and housing.
   - Parenting animals if relevant (sow, boar).
2. Write the copy:
   - A compelling headline and hero text.
   - Clear bullet points for piglet details.
   - Short farm story and care practices.
3. Prepare contact details:
   - Phone, email, and preferred contact method.
   - Social links or farm listings if available.
4. Prepare any legal or welfare notes:
   - Animal welfare commitments.
   - Local regulation guidance.
   - Responsible breeding practices.

---

## Step 5: Build the site structure in the repository

1. Create the website folder structure:
   - `index.html`
   - `piglets.html`
   - `about.html`
   - `gallery.html`
   - `contact.html`
   - `styles.css`
   - `images/` for photos
2. If using Jekyll, instead create:
   - `_config.yml`
   - `_layouts/default.html`
   - `index.md`, `piglets.md`, `about.md`, `gallery.md`, `contact.md`
   - `assets/css/styles.css`
   - `images/` for photos
3. Add basic navigation to every page.
4. Include metadata in the page head:
   - Title tag
   - Meta description
   - Open Graph tags (optional)

---

## Step 6: Use modern design and accessibility best practices

1. Choose a clean layout with a hero section, cards, and sections.
2. Use a green-centered brand palette with your main color `#0f5132`, plus black and earth tones for accents and backgrounds.
3. Use responsive CSS:
   - Mobile-first design.
   - Flexible grid or stacked sections.
4. Optimize images:
   - Resize images for web delivery.
   - Use `alt` text for accessibility.
5. Keep page weight low:
   - Avoid large JavaScript frameworks.
   - Use minimal CSS.
6. Make buttons and links easy to tap on mobile.

---

## Step 7: Configure GitHub Pages publishing

1. Push the initial site files to GitHub.
2. In repository Settings > Pages:
   - Select `main` branch and root folder, or `/docs` if you used it.
   - Save the publishing source.
3. If using a custom domain:
   - Create `CNAME` with your domain.
   - Update DNS records with your registrar.
4. Confirm the live URL and check for build errors.

---

## Step 8: Test and publish

1. Review the site on desktop and mobile.
2. Test all links and navigation.
3. Confirm images load, contact details are visible, and pages are readable.
4. If using Jekyll, optionally preview locally with `bundle exec jekyll serve` before pushing.
5. Publish and share the URL.

---

## Step 9: Maintain the site

1. Update the piglet availability page as litters sell out.
2. Add new photos and testimonials.
3. Keep contact details current.
4. Review performance and accessibility periodically.
5. Add new content when you have fresh litters or sales updates.

---

## Clarifying questions

1. Do you want this site to be a user site at `username.github.io` or a project site under a repository name like `kunekune-piglets`?
2. Do you already have a GitHub account and a preferred repository name?
3. Will you use a custom domain or just the default GitHub Pages URL?
4. Do you want a simple HTML/CSS site or a Jekyll site with Markdown pages?
5. Do you already have photos, pricing, piglet details, and contact information available?  
6. Do you want the site to include a contact form, or is a phone/email link enough?
