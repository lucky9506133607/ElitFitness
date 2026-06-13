# Elite Fitness Gym 🏋️

A modern, responsive single-page website for **Elite Fitness Gym** built with HTML, Tailwind CSS, and minimal vanilla JavaScript. Production-ready with a premium black + red + white theme.

![Elite Fitness Gym](https://images.unsplash.com/photo-1534438327276-14e5300c3a48?w=1200)

## ✨ Features

- 🎨 **Premium Design** — Black + red + white theme with subtle animations
- 📱 **Fully Responsive** — Looks great on mobile, tablet, and desktop
- ⚡ **Fast Loading** — CDN-based Tailwind, lazy-loaded images, optimized assets
- 🎬 **Smooth Animations** — Scroll-reveal effects, hover transitions, shimmer buttons
- 🔍 **SEO Optimized** — Meta tags, Open Graph, Twitter cards
- ♿ **Accessible** — ARIA labels, semantic HTML, keyboard-friendly

## 📂 Project Structure

```
elite-fitness-gym/
└── index.html        # Single-file website (HTML + Tailwind + JS)
```

## 🛠️ Tech Stack

| Layer        | Technology               |
| ------------ | ------------------------ |
| Markup       | HTML5 (semantic)         |
| Styling      | Tailwind CSS (CDN)       |
| Typography   | Google Fonts (Inter, Oswald) |
| Scripting    | Vanilla JavaScript (minimal) |
| Imagery      | Unsplash (placeholders)  |

## 📋 Sections Included

1. **Sticky Navbar** — Logo, navigation, mobile menu, CTA
2. **Hero** — Full-width background, heading, subheading, CTAs, stats
3. **About** — Highlights: Certified Trainers, Modern Equipment, Clean Environment, Flexible Timings
4. **Services** — Weight Training, Cardio, Personal Training, CrossFit, Diet Guidance, Yoga
5. **Membership Plans** — Basic ($29), Standard ($59, popular), Premium ($99)
6. **Trainers** — 3 trainer cards with social links
7. **Testimonials** — 3 customer reviews with 5-star ratings
8. **Contact** — Phone, email, address, working hours + contact form
9. **Footer** — Social links, quick links, newsletter signup, copyright

## 🚀 How to Use

1. Open `index.html` directly in any modern browser — that's it!
2. To deploy: upload the folder to any static host (Netlify, Vercel, GitHub Pages, etc.)

### Local Development (Optional)

For Tailwind customization beyond the included `tailwind.config`:

```bash
# Install Tailwind CLI
npm install -D tailwindcss

# Build a custom CSS file
npx tailwindcss -i ./input.css -o ./output.css --minify
```

## 🎨 Customization

- **Colors** — Edit the `tailwind.config` script (top of `index.html`)
- **Content** — All text is in plain HTML for easy editing
- **Images** — Replace Unsplash URLs with your own
- **Fonts** — Swap Google Fonts links in `<head>`

## 📝 Notes

- Uses Tailwind CSS via CDN — for production, consider building with the Tailwind CLI for a smaller bundle
- All images are lazy-loaded except the hero (eager)
- The contact form simulates submission — wire it to your backend or service like Formspree
- Fully commented code for easy maintenance

---

**Built with ❤️ for fitness enthusiasts.**
