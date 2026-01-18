# Hydration

It is basically react waking up the server rendered html.

## What happens in Next.js(App Router)

- Server renders HTML(fast,seo friendly)
- Browser recieves HTML -> page is visible
- ReactJs loads -> hydrates the html
- Event handlers(onClick,state,effects) attach

## Until hydration

- No useState
- No useEffect
- No localStorage
- No theme toggling
