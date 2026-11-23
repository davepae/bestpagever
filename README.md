# bestpagever

A side-by-side look at what frontier models build from one open-ended prompt: a single, self-contained HTML file.

## The prompt

> Create the most beautiful and stunning single HTML file you can possibly imagine that works in a Chrome or Edge browser.

Each model gets the same prompt and returns one `.html` file. No frameworks, no build step, no external assets required.

## Pages

| Page | Folder | Description |
| --- | --- | --- |
| Aetherium — interactive light & gravity observatory | [`neon/`](neon/aetherium.html) | An interactive observatory of light and gravity with glassy, amber-accented panels. |
| Abyssal | [`opus/`](opus/Abyssal.html) | A single-file page built from the same prompt. |

## Viewing

No install needed. Open any file directly in Chrome or Edge:

```sh
open neon/aetherium.html
open opus/Abyssal.html
```

Or double-click the file in Finder or Explorer.

## Adding a page

1. Generate a single HTML file from the prompt above.
2. Put it in a folder named for the model that produced it (for example `opus/`).
3. Keep the file self-contained so it opens without a server.
4. Add a row to the table above.
