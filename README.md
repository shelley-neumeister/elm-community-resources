# ELM Community Resources

Free games, frameworks, and tools from the ELM Lab (CEAMLS, Morgan State University) to help communities understand and shape decisions about AI and public infrastructure.

Live site: https://shelley-neumeister.github.io/elm-community-resources/

## Pages
- `index.html`: home
- `would-you-rather.html`: Would You Rather game (solo play, room tally, printable deck)
- `simulator.html`: Patuxent County civic simulator (15-minute challenges + full meter game)
- `right-to-understand.html`: Citizens' Right to Understand framework, worked PG County data center case, printable worksheet
- `links.html`: Helpful Links and infographics (content lives in `assets/resources.js`)

Plain HTML/CSS/JS with no build step. Shared styles live in `assets/style.css`.

## Adding links and infographics
Edit only `assets/resources.js`; the page builds itself from that file.

- **New link:** copy one entry in the `LINKS` list, paste it after the last one, and change the text. `group` sets the section heading; a new group name creates a new section.
- **New infographic:** upload the PDF and a preview image (.jpg or .png) to the `infographics/` folder, then copy an entry in the `INFOGRAPHICS` list and update `title`, `summary`, `image`, `pdf`, and `asOf`.
- Keep the commas between entries. If the page shows no links after an edit, a missing comma or quote is the usual cause.
