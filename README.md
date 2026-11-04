# Imagine

A lightweight landing page for turning app and website ideas into real projects. Visitors can describe their idea and open a prefilled WhatsApp message to discuss it.

## Run locally

Open `index.html` in a browser, or serve the folder with:

```sh
python3 -m http.server 3000
```

Then visit `http://localhost:3000`. The landing page needs no build step; its styles and interactions are contained in `index.html`.

## Project files

- `index.html` — landing page, styles and interactions.
- `components/ui/` — optional React Flow Button and demo.
- [COMPONENT_SETUP.md](COMPONENT_SETUP.md) — React, Tailwind and shadcn setup notes.
- `LICENSE` — project license.

To change the WhatsApp recipient, update the `wa.me` number in `index.html` using the international format without `+` or spaces. The visitor reviews and sends the message in WhatsApp.
