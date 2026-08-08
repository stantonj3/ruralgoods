# Kunekune Piglets Website Research

## Purpose
This document summarizes what it takes to create a static website hosted on GitHub Pages, how to design a modern website, and what information is best to include for advertising Kunekune piglets for sale.

---

## 1. Why GitHub Pages for a static website

- GitHub Pages is free for public repositories.
- It hosts static sites directly from a GitHub repository.
- You can use plain HTML/CSS/JavaScript or a static site generator such as Jekyll.
- Deployment is automatic when you push to the configured publishing source.
- You can host on `https://<username>.github.io` or a custom domain.

### Advantages
- No server management required.
- Fast content delivery from GitHub's CDN.
- Easy version control with Git.
- Reliable HTTPS support.
- Good for small business and farm advertisement sites.

### Limitations
- Only static content; no server-side processing.
- If you need contact forms, you must use a third-party service or email link.
- GitHub Pages build environment restricts unsupported Jekyll plugins.

---

## 2. GitHub Pages options

### Option A: User or organization site
- Repository name must be `username.github.io`.
- Site URL: `https://username.github.io`.
- Best for a single main website.

### Option B: Project site
- Repository can be any name.
- Site URL: `https://username.github.io/repo-name`.
- Good for a site that is part of a broader project or brand.

### Publishing sources
- Publish from a branch root (`/`) or `/docs` folder.
- Common simple setup: use `main` branch and root folder.
- For build processes or custom generators, use GitHub Actions.

### Jekyll support
- GitHub Pages supports Jekyll out of the box.
- `jekyll` can convert Markdown to HTML and apply site templates.
- You can add a `_config.yml` to configure themes, metadata, and plugins.
- To use unsupported plugins, build locally and push compiled static output.

---

## 3. Recommended setup approach

### Simple static site
- Use HTML/CSS/JavaScript files directly in the repository.
- Add `index.html` at the root.
- Push the repository to GitHub.
- Configure Pages source to `main` branch and root folder.

### Jekyll site (recommended if you want templates)
- Create `_config.yml` and optionally `_layouts`, `_includes`, and `_posts`.
- Use Markdown pages like `index.md`, `about.md`, `contact.md`.
- Choose a lightweight theme or custom CSS.
- Push to GitHub and let Pages build the site.

### Custom domain
- Optionally use your own domain.
- Add a `CNAME` file with your custom domain.
- Configure DNS records at your domain registrar.
- This makes the site look more professional.

---

## 4. Building a modern website design

### Visual design principles
- Clean, minimal layout.
- Strong photography of the piglets and farm.
- Use a simple color palette that reflects your farm brand.
- Ensure good whitespace and easy reading.
- Use a responsive layout for mobile and desktop.

### Navigation and structure
- Keep navigation short and clear.
- Use a top menu or hero section with major pages.
- Example page structure:
  - Home
  - About the farm
  - Piglets for sale
  - Care and breed information
  - Contact
  - Gallery or photos

### Typography and readability
- Use legible fonts and large headings.
- Keep paragraph lines short.
- Use contrast between text and background.

### Performance and accessibility
- Optimize images for web delivery.
- Use descriptive `alt` text for all photos.
- Ensure buttons and links are easy to tap on mobile.
- Keep page weight low by avoiding large scripts.

---

## 5. Content to include for selling Kunekune piglets

### Hero / landing section
- One sentence explaining what you offer.
- Example: “Healthy Kunekune piglets raised on pasture, ready for sale.”
- Add a strong call to action like “View available piglets” or “Contact us today.”

### Piglet details
- Breed: Kunekune.
- Age or birth date of available litters.
- Number available and gender if known.
- Price or pricing note.
- Health status, vaccinations, and vet checks.
- Registration status (if registered or purebred).
- What the piglets are raised on (pasture, family farm, local feed).
- Delivery or pickup options.

### Farm and animal care
- Farm location or service area.
- Description of the farm environment.
- How the piglets are socialized.
- Feeding and care practices.
- Why Kunekune are a good choice (easy-going, friendly, good for small farms).

### Photos and videos
- High-quality images of piglets, sows, boars, and facilities.
- Close-up photos of the pigs and lifestyle shots.
- If available, short video clips or social proof.
- Use a gallery or a few hero images on the landing page.

### Contact information
- Phone number and email address.
- Preferred contact method and response hours.
- A contact form if you use a third-party form service.
- Social media or farm listing links if available.

### Trust and credibility
- Mention experience raising pigs and years on the farm.
- Include references, testimonials, or customer feedback.
- Share any memberships or certifications.
- Explain your health and safety practices.

### FAQs
- Typical questions buyers will have.
- Example questions:
  - “What age are the piglets when they leave?”
  - “Do you offer weaning or delivery?”
  - “What supplies will buyers need?”

### Legal and ethics notes
- Emphasize responsible breeding and animal welfare.
- Mention that buyers should comply with local regulations.
- Note that site visitors should book appointments in advance.

---

## 6. Recommended pages and sections

### Home page
- Quick overview of your Kunekune piglets and farm.
- Strong imagery and clear call to action.
- Links to listings and contact.

### Available piglets page
- Current available litters and details.
- Status updates (e.g., reserved, sold, available).
- Easy-to-scan card or table layout.

### About page
- Farm story and values.
- Information about Kunekune breed.
- Why your farm is a good source.

### Gallery page
- Photo gallery of piglets and farm.
- Optional short video or slideshow.

### Contact page
- Clear contact details and inquiry instructions.
- Map or approximate location if relevant.
- A form or email link if using external form service.

---

## 7. SEO and discovery tips

- Use descriptive title tags and headings.
- Write a meta description for the site.
- Include keywords naturally: “Kunekune piglets for sale”, “Kunekune piglets NZ”, “farm-raised piglets”.
- Add alt text for every image.
- Use concise page URLs like `/piglets`, `/about`, `/contact`.
- Submit the site to Google Search Console if using a custom domain.

---

## 8. Implementation checklist

1. Create a GitHub repository.
2. Choose `username.github.io` for a user site, or any name for a project site.
3. Add `index.html` or Jekyll site files and commit.
4. Configure GitHub Pages in repository settings.
5. Set publishing source to `main` branch root or `/docs`.
6. Add site content and images.
7. Optimize for mobile and accessibility.
8. Optionally add a `CNAME` for a custom domain.
9. Push updates and confirm the live URL.

---

## 9. Practical recommendation for this project

For a farm advertising Kunekune piglets, the best approach is:
- Start with a simple, clean static HTML/CSS site.
- Use a GitHub Pages user site if you want a permanent domain at `username.github.io`.
- Use strong photos and clear selling information.
- Keep the page easy to update when litters change.
- Add or link to a contact method rather than complex online booking.

## 10. Next steps

- Choose repository and GitHub Pages type.
- Collect photos, piglet details, pricing, and contact information.
- Decide whether you want a custom domain.
- Build the first version with a homepage, available piglets, about, and contact.
- Review the site on desktop and mobile before sharing.
