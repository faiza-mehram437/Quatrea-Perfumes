# Quatréa — Four seasons, one signature

A multipage scrollytelling website for **Quatréa**, a fictional perfume house with four fragrances, one for each season.

| Season | Perfume | Mood |
| --- | --- | --- |
| Spring | **Fleur d'Aube** (N°1) | Pear blossom, peony, white musk |
| Summer | **Soleil Salé** (N°2) | Sea salt, blood orange, neroli |
| Autumn | **Cuir d'Ambre** (N°3) | Saffron, soft leather, amber |
| Winter | **Givre Blanc** (N°4) | Frozen juniper, iris, cashmere woods |

**Live demo:** [
quatreaperfume](https://quatreaperfume.netlify.app/)

## What's inside

- **Home**: an animated quatrefoil logo, a brand story whose words light up as you scroll, and a pinned "journey" section. As you scroll through it, the background, bottle colour, falling particles and text change from Spring to Winter.
- **Four perfume pages**: each has its own colour palette and particles (petals, sun motes, leaves or snow). Every page has a bottle that fills with perfume, a story section, a notes pyramid that builds up as you scroll, "moments" cards with parallax, counting stats and a link to the next season.
- **The Craft**: a sideways-scrolling five-step process with icons that draw themselves, counters, a quote and expanding season links.
- **Page transitions**: a curtain in the colour of the season you clicked.
- **Responsive design**: works down to phone width and has a mobile menu.
- **Accessibility**: respects *Reduce motion*. With that setting on, or if the animation libraries fail to load, the site shows a calm, fully readable version without animation. It also has a skip link, visible keyboard focus and a semantic page structure.



## Built with

- HTML, CSS and plain JavaScript, with no build step
- [GSAP 3.12.5](https://gsap.com/) + ScrollTrigger for scroll animations (loaded from the cdnjs CDN)
- [Lenis 1.1.13](https://github.com/darkroomengineering/lenis) for smooth scrolling (loaded from the unpkg CDN)
- Google Fonts: *Cormorant Garamond* (headings) and *Manrope* (text)

## Project structure

```
quatrea-perfume/
├── index.html        Home
├── spring.html       Fleur d'Aube
├── summer.html       Soleil Salé
├── autumn.html       Cuir d'Ambre
├── winter.html       Givre Blanc
├── craft.html        About / The Craft
├── favicon.svg
├── css/style.css     All styles + the four season colour themes
└── js/main.js        Bottles, particles, smooth scroll, animations, transitions
```

## Credits

Designed and built by Faiza Mehram. 
