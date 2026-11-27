# hectorbenitez.com

Personal résumé site. Plain HTML and CSS, no build step, served by GitHub Pages from `master` (custom domain in `CNAME`).

- `index.html`: English (default). `es/index.html`: Spanish. Keep both in step.
- Design system: Modernist, accent Rojo Feria (the default). `css/modernist.vars.css` and `css/modernist.components.css` are copied unchanged from the design system; page layout lives in `css/site.css`.
- Printing the page (Cmd+P / Save as PDF) gives a clean résumé: the print styles hide navigation and drop the colored fields.
- `projects/bitcoinbot/tos.html` is the terms page for an old Messenger bot; kept so its link keeps working.

Preview locally:

```sh
python3 -m http.server 8000
```
