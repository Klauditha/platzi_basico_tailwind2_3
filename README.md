# Platzi Básico Tailwind 2 y 3

- https://play.tailwindcss.com/
- https://v2.tailwindcss.com/docs/customizing-colors
- https://v2.tailwindcss.com/docs/breakpoints
- https://tailwindcss.com/docs/width
- https://tailwindcss.com/docs/height

- https://www.figma.com/file/aPbr2Rhd5SCUjNYu6NRPPB/Platzi-Travel-Mockups?type=design&node-id=0-1&mode=design

## Plugins

### Forms 

- npm install @tailwindcss/forms

module.exports = {
  theme: {
    // ...
  },
  plugins: [
    require('@tailwindcss/forms'),
    // ...
  ],
}

- Ejemplos : https://tailwindcss-forms.vercel.app/
  
### Typography 

- npm install -D @tailwindcss/typography

module.exports = {
  theme: {
    // ...
  },
  plugins: [
    require('@tailwindcss/typography'),
    // ...
  ],
}

- Ejemplos: https://play.tailwindcss.com/uj1vGACRJA?layout=preview

### Aspect ratio

- npm install @tailwindcss/aspect-ratio

module.exports = {
  theme: {
    // ...
  },
  plugins: [
    require('@tailwindcss/aspect-ratio'),
    // ...
  ],
}