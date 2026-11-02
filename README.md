# prechatavanich.github.io

Personal website of Natchanon (Knot) Prechatavanich, 張清鬆. The live site is at https://prechatavanich.github.io

It's a single static page, `index.html`, with three languages (EN / 中文 / ไทย) and a light/dark theme. There is no build step.

## Editing

- **Text:** every sentence appears three times, as `<span data-l="en">`, `<span data-l="zh">` and `<span data-l="th">`. Edit all three.
- **Images:** they live in `assets/img/`. To replace one, keep the same file name.
- **Contact card:** the contact details appear in three places: the contact card in `index.html`, `natchanon-prechatavanich.vcf` (the "Save contact" file) and the footer.
- **CV button:** to add a "Download CV" button, put `cv.pdf` in the root and add `<a class="btn ghost" href="cv.pdf" download>` inside `.btns`.

## Language links

`?lang=en`, `?lang=zh` or `?lang=th` opens the page in that language. Without one, the page uses the visitor's last choice or their browser language.

## Fonts

Chinese text uses DF-KaiTi (標楷體) where it is installed, which is usually on Windows. Everywhere else it falls back to LXGW WenKai TC from Google Fonts.
