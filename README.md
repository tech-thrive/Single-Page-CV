# Professional HTML CV / Resume

A clean, semantic, and production-ready single-page HTML resume template. This project sets up the structural foundation, search engine optimization (SEO), and social media preview configurations (Open Graph tags) for an online portfolio website.

## 🚀 Features

- **Semantic HTML5 Layout:** Utilizes meaningful structural elements (`<header>`, `<main>`, `<section>`, `<article>`, `<address>`) ensuring excellent accessibility, clean code hierarchy, and seamless future CSS styling.
- **SEO Optimization:** Pre-configured with essential search engine meta tags (title, description, keywords) to enhance visibility and search rankings.
- **Open Graph (OG) Integration:** Includes native OG tags to ensure professional, rich-media preview cards when sharing the CV link on platforms like LinkedIn, WhatsApp, Facebook, Slack, and X (Twitter).
- **Favicon Integration:** Ready-made configuration to link custom site branding directly in the browser tab.

## 📂 Project Structure

The project consists of a single standalone HTML document containing the following structural layout:
- **Header:** Full name, professional headline, and structural contact information enclosed in an `<address>` tag.
- **Skills Section:** A direct summary of core technical competencies and soft skills.
- **Education Section:** Chronologically ordered academic background highlighting institutions, degrees, and timelines.
- **Experience Section:** Structured work experience blocks wrapped in semantic `<article>` tags to cleanly isolate individual positions, achievements, and technologies utilized.
- **Across the Internet Section:** A dedicated area for professional social footprints including GitHub and LinkedIn profiles.

## 🛠️ Usage & Customization

1. **Clone or Copy the Code:** Save the provided code into an index file (e.g., `index.html`).
2. **Personalize the Content:** Replace the placeholder text (e.g., "Suriya", address details, college name, and job history) with your actual profile details.
3. **Configure Meta Metadata:**
   - Update the `content` attribute in `<meta name="description">` with your personal elevator pitch.
   - Adjust the comma-separated words within `<meta name="keywords">`.
4. **Link Live Assets:**
   - Change the `og:url` property content from `"pass"` to your live website URL once hosted.
   - Place your custom favicon in the project root directory and name it `profile.png` (or update the `<link rel="icon">` `href` path to match your asset file name).
   - Ensure an image named `profile.jpg` is present in your folder to serve as the banner background when your portfolio link is shared on social networks.

## 📋 Submission Checklist Requirements Satisfied

- [x] Semantically correct HTML structure.
- [x] Single-page layout containing specific sections for Education, Skills, and Career History.
- [x] Hidden SEO meta tags embedded cleanly inside the `<head>` block.
- [x] Interactive Open Graph tags optimized for professional social sharing cards.
- [x] Clean favicon links specified in the head configuration.
