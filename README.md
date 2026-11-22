# Innerplexity — Ali Shabani, Learning Experience Designer

Static copy of [innerplexity.com](https://www.innerplexity.com), moved off Squarespace and hosted with GitHub Pages. The layout, fonts, colours and images match the original site.

## Structure

| Path | Page |
| --- | --- |
| `index.html` | Home |
| `videos-WIx4I/` | Micro-learning videos (and `v/…` for each video) |
| `my-approach/` | Approach |
| `about/` | About |
| `contact/` | Contact |
| `interior-design-program/`, `unconscious-bias/`, `bruce-tuckman/`, `building-high-performing-teams-1/` | Project pages |
| `css/` | Stylesheets (`site.css` holds the site's theme) |
| `assets/img`, `assets/fonts`, `assets/video` | Images, Inter font files, video files |

The folder names keep the old Squarespace URLs, so existing links still work.

## Editing

Each page is a single `index.html`. To change wording, open the file on GitHub, click the pencil icon, edit the text between the tags, and commit. The site updates within a minute or two.

To replace an image, upload a new file to `assets/img/` with the same name, or upload a new file and update the `src="…"` that points to it.

## Contact form

The form posts to [FormSubmit](https://formsubmit.co). The first message sent through it triggers a one-time activation email to the address in the form's `action`.
