# Divine Finish Detailing

One-page site for Divine Finish Detailing — mobile auto detailing, Austin TX.

## Deploying

Plain static HTML. No build step, no dependencies.

Netlify picks the settings up from `netlify.toml`:

- Build command: *(none)*
- Publish directory: `.`

Any push to `main` redeploys automatically.

## Editing

| What | Where |
|---|---|
| Copy, services, service area | `index.html` |
| Hero background video | `images/hero-loop.mp4` + `images/hero-poster.jpg` |
| Work strip photos/clips | the `WORK` array near the bottom of `index.html` |
| Quote form destination | `FORMSPREE_ENDPOINT` near the bottom of `index.html` |

Form submissions go to Formspree form `xaeejggv`, which delivers to
divinefinishdetailatx@gmail.com. Formspree only delivers once the address has
been confirmed by clicking the link in their confirmation email.

## Contact details used on the page

- Phone: (469) 922-0001
- Email: divinefinishdetailatx@gmail.com
- Service area: Austin, TX and surrounding cities
